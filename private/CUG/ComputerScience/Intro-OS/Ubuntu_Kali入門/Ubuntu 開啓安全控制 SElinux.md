# Ubuntu 開啓安全控制 SElinux

## 介紹 Introduction

SELinux 非Ubuntu自帶的 MAC，屬於REHL系列，但也可以安裝在Ubuntu上。 
SELinux is a Mandatory Access Control (MAC) system which is a kernel  (LSM) enhancement to confine programs to a limited set of resources. 

**SELinux如何工作**

考虑一下SELinux的相关概念:

主体Subjects

目标Objects

策略Policy

模式Mode

当一个主体Subject（如一个程序）尝试访问一个目标Object（如一个文件），SELinux安全服务器SELinux Security Server（在内核中）从策略数据库Policy Database中运行一个检查。基于当前的模式mode，如果 SELinux  安全服务器授予权限，该主体就能够访问该目标。如果SELinux安全服务器拒绝了权限，就会在/var/log/messages中记录一条拒绝信息。

听起来相对比较简单是不是？实际上过程要更加复杂，但为了简化介绍，只列出了重要的步骤。

**模式**

SELinux 有三个模式（可以由用户设置）。这些模式将规定 SELinux 在主体请求时如何应对。这些模式是：

Enforcing 强制— SELinux 策略强制执行，基于 SELinux 策略规则授予或拒绝主体对目标的访问

Permissive 宽容— SELinux 策略不强制执行，不实际拒绝访问，但会有拒绝信息写入日志

Disabled 禁用— 完全禁用SELinux

## SELinux 的运行状态

SELinux 有三个运行状态，分别是disabled, permissive 和 enforcing

-  Disable： 禁用SELinux，不会给任何新资源打Label，如果重新启用的话，将会给资源重新打上Lable，过程会比较缓慢。
-  Permissive：如果违反安全策略，并不会真正的执行拒绝操作，替代的方式是记录一条log信息。
-  Enforcing: 默认模式，SELinux的正常状态，会实际禁用违反策略的操作

(getenforce[命令](https://www.linuxcool.com/)显示SELinux的状态是Enforcing启用状态)

查看当前的运行状态

```bash
~]# getenforce
Enforcing
```

临时改变运行状态为Permissive

```bash
~]# setenforce 0
~]# getenforce
Permissive
```

临时改变运行状态为 Enforcing

```bash
~]# setenforce 1
~]# getenforce
Enforcing
```

使用`sestatus`可以查看完整的状态信息

```bash
~]# sestatus
SELinux status:                 enabled
SELinuxfs mount:                /sys/fs/selinux
SELinux root directory:         /etc/selinux
Loaded policy name:             targeted
Current mode:                   enforcing
Mode from config file:          enforcing
Policy MLS status:              enabled
Policy deny_unknown status:     allowed
Max kernel policy version:      30
```





默认情况下，大部分系统的SELinux设置为Enforcing。你要如何知道你的系统当前是什么模式？你可以使用一条简单的[命令](https://www.linuxcool.com/)来查看，这条命令就是 getenforce。这个命令用起来难以置信的简单（因为它仅仅用来报告SELinux的模式）。要使用这个工具，打开一个终端窗口并执行  getenforce 命令。命令会返回 Enforcing、Permissive，或者Disabled（见上图）。

设置SELinux的模式实际上很简单——取决于你想设置什么模式。记住：永远不推荐关闭  SELinux。为什么？当你这么做了，就会出现这种可能性：你磁盘上的文件可能会被打上错误的权限标签，需要你重新标记权限才能修复。而且你无法修改一个以 Disabled 模式启动的系统的模式。你的最佳模式是Enforcing或者Permissive。

你可以从命令行或/etc/selinux/config文件更改SELinux的模式。要从命令行设置模式，你可以使用setenforce工具。要设置Enforcing模式，按下面这么做：

1.打开一个终端窗口
 2.执行su然后输入你的管理员密码
 3.执行setenforce 1
 4.执行getenforce确定模式已经正确设置（如下图）

要设置模式为Permissive，这么做：
 1.打开一个终端窗口
 2.执行su然后输入你的管理员密码
 3.执行setenforce 0
 4.执行getenforce确定模式已经正确设置（如下图）

注：通过命令行设置模式会覆盖 SELinux 配置文件中的设置。
 如果你更愿意在SELinux命令文件中设置模式，用你喜欢的编辑器打开那个文件找到这一行：

```
SELINUX=permissive
```

你可以按你的偏好设置模式，然后保存文件。
 还有第三种方法修改SELinux的模式（通过 bootloader），但我不推荐新用户这么做。

**策略类型**

SELinux策略有两种：
 Targeted目标 — 只有目标网络进程（dhcpd，httpd，named，nscd，ntpd，portmap，snmpd，squid，以及 syslogd）受保护
 Strict严格 — 对所有进程完全的SELinux保护
 你可以在/etc/selinux/config文件中修改策略类型。用你喜欢的编辑器打开这个文件找到这一行：

```
SELINUXTYPE=targeted
```

修改这个选项为targeted或strict以满足你的需求。

**检查完整的SELinux状态**

有个方便的SELinux 工具，你可能想要用它来获取你启用了SELinux的系统的详细状态报告。这个命令在终端像这样运行：

```
sestatus -v
```

你可以看到像下图这样的输出。

## SELinux Log

SELinux 的Log日志默认记录在`/var/log/audit/audit.log`

```bash
~]# cat /var/log/audit/audit.log
type=AVC msg=audit(1223024155.684:49): avc:  denied  { getattr } for  pid=2000 comm="httpd" path="/var/www/html/file1" dev=dm-0 ino=399185 scontext=unconfined_u:system_r:httpd_t:s0 tcontext=system_u:object_r:samba_share_t:s0 tclass=file
```

`/var/log/message` 也会记录相应的信息，例如：

```bash
May 7 18:55:56 localhost setroubleshoot: SELinux is preventing httpd (httpd_t) "getattr" to /var/www/html/file1 (samba_share_t). For complete SELinux messages. run sealert -l de7e30d6-5488-466d-a606-92c9f40d316d
```

## SELinux 配置文件

SELinux的配置文件位于`/etc/selinux/config`。默认配置文件主要两部分，一个是SELinux的运行状态和SELinuxType。直接在配置文件中修改SELinux将会在下次启动时生效。











## 安裝 Install

`sudo apt-get install selinux`

```bash
sudo apt install selinux-utils

sudo apt install policycoreutils
sudo apt-get install policycoreutils selinux-utils selinux-basics -y

When the installation completes, activate SELinux with the command:

sudo selinux-activate

Set SELinux to enforcing mode with:

sudo selinux-config-enforcing

Finally, reboot your system once again with:

sudo reboot

When the system comes back up, check to make sure SELinux is enabled with the command:

sestatus
```









## More information

- [SELinux Project](http://selinuxproject.org/page/User_Resources) 
- [Ubuntu Security mailing list](http://lists.ubuntu.com/mailman/listinfo/ubuntu-hardened) 
- Ubuntu Blueprints: 
  - [Initial](https://wiki.ubuntu.com/SpecSELinux) 
  - [Hardy](https://wiki.ubuntu.com/HardySELinux)







