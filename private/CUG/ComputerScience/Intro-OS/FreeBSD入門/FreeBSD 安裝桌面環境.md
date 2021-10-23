# FreeBSD 安裝桌面環境

更換鏡像源
```bash

使用方法

FreeBSD pkg 包管理器的官方源配置是 /etc/pkg/FreeBSD.conf ，请先检查该文件内容。注意其中的 url 参数配置了官方仓库的地址，我们需要把它替换为镜像站的地址。

该配置文件是 FreeBSD 基本系统的一部分，会随着 freebsd-update 更新，请不要直接修改，而是创建 /usr/local/etc/pkg/repos/FreeBSD.conf 覆盖配置，文件内容如下：

FreeBSD: {
  url: "pkg+http://mirrors.ustc.edu.cn/freebsd-pkg/${ABI}/quarterly",
}

如果要使用滚动更新的 latest 仓库，把 url 配置最后的 quarterly 换成 latest 即可。

修改配置后，运行 pkg update -f 更新索引。

小技巧

使用 HTTPS 可以有效避免国内运营商的缓存劫持，但需要事先安装 security/ca_root_nss 软件包。


使用方法

在 /etc/make.conf 中添加以下内容（如果文件不存在，则新建之）：

MASTER_SITE_OVERRIDE?=http://mirrors.ustc.edu.cn/freebsd-ports/distfiles/${DIST_SUBDIR}/


```


Install Desktop Entertainment

````````


````````

root: 

 pkg update

 pkg install nano neofetch zsh

```bash
nano /etc/fstab

procf     /proc     procfs     rw    0  0

```









```

pkg install xorg gnome-desktop gdm 
gnome3-lite | gnome3 
```

```
pkg_delete gnome3-lite
cd /usr/prots/x11/gnome3
make install clean
```



`pkg install open-vm-tools  vim`

```
For example, to start sshd(8), the included OpenSSH daemon:

# echo 'sshd_enable="YES"' >> /etc/rc.conf

```

 

```
nano /etc/rc.conf

dbus_enable="YES"
hald_enable="YES"
gdm_enable="YES"
gnome_enable="YES"


moused_enable="YES"
allscreens_flags="-m on"


zfs_enable="YES"

linux_enable="YES"

ntpd_enable="YES"
ntpd_sync_on_start="YES"

devfs_enable="YES"
devfs_system_ruleset="devfsrules_common"

dbus_enable="YES"
lightdm_enable="YES"

webcamd_enable="YES"

cupsd_enable="YES"

avahi_daemon_enable="YES"
avahi_dnsconfd_enable="YES"

moused_enable="YES"

ipfw_enable="YES"
firewall_enable="YES"

ifconfig_em0="DHCP"

keymap="us.kbd"

hostname="frbsd.local"
```



 pkg install  gnome-terminal vlc firefox libreoffice gedit tree zsh



```
pw groupmod wheel -m uername

```









···



```
Please sit back and relax, since this process will take some times to finish. It will fetch around 600 files from the Internet. Ensure you have a fast and reliable internet connection.

$ pkg install gnome-desktop gdm xorg gnome3

To do this, edit file /etc/rc.conf using vi, and add these lines below, and do not forget to save using Esc :wq!:


dbus_enable="YES"
hald_enable="YES"
gdm_enable="YES"
gnome_enable="YES"
moused_enable="YES"

$ vi /etc/rc.conf
```



```
Install sudo and give user sudo privileges

Out of the box, you won't find sudo installed on FreeBSD. Because of this, you'll need to log in as root to install anything. That's a security issue. To fix this, you'll want to first install sudo and then give your user sudo privileges.

First, install sudo with the command:

pkg install security/ca_root_nss
pkg install security/sudo

Open the sudoers file for editing with the command:

visudo

At the bottom of this file, add the following:

USER ALL=(ALL) ALL

Where USER is the name of the user to be added.

Save and close that file.
```





```
Installation of Windowing Manager, X.org Server, & Desktop Environment

The majority of the installation process is behind us. Now, it is time to move forward with the additional steps that are needed to install additional packages (including the pkg package manager), Windowing Manager (gdm), Desktop Environment (DE) of choice (Gnome3), the X11 Window Manager (Xorg), reconfigure the /etc/fstab file, and wrap up by modifying the /etc/rc.conf file that will allow the dbus, gdm, gnome, and hald to be enabled on bootup. Let’s take these one at a time:

In order to be able to edit the files that need configuring in these final steps and interact with GitHub as well as installing a utility to monitor system resources, we can install them next using this one-line CLI command. But, when logging in for the first time after rebooting the system we can either log in as the standard user, then elevate our privileges by issuing:

$ su -

and entering the root credentials, or simply log in as root from the start. We need to be logged in as root user either way we choose to do it because in order to install anything in FreeBSD-13 Release, we need to be root user using the pkg command. Therefore, to install our editor of choice: nano, and git, py37-glances (for monitoring processes), htop (for monitoring resources), and neofetch (for monitoring system resources, we can do this as follows in the tty:

# pkg install nano git py37-glances htop neofetch

And, now each of these packages will be installed after we confirm that’s what we would like to do. Since nano is installed, we can now use it to update the /etc/fstab file by issuing the command:

# nano /etc/fstab

Then, once the file system table file is open for editing, we need to add the following line to the bottom of the file:

proc     /proc     procfs     rw    0  0

then, save and close the file by using Ctrl + X, then Y (signifying “Yes”) and Enter to close and save the file. Now, it’s time to install the X.org Server and the Gnome3 Desktop Environment. To do this, run the command:

# pkg install xorg gnome3

There are in excess of 500 packages that need to be installed, so this is going to take about 10 – 15 minutes to complete, so be patient. Once these two packages are installed, there is one final step to reaching our goal of a functioning FreeBSD-13 Release installation with login screen and Gnome 3 Desktop Environment. This final step is to modify the /etc/rc.conf file to enable some services at bootup allowing us to login. Issue this command in the tty to launch nano to edit the /etc/rc.conf:

# nano /etc/rc.conf

Editing /etc/rc.conf to Enable Services at Bootup

The lines that need to be added to this file are the last four lines in the file:

dbus_enable="YES"
gdm_enable="YES"
gnome_enable="Yes"
hald_enable="YES"

The first line enables dbus. The second line enables the Gnome Display Manager. The third line enables the Gnome DE itself (startx). And, the last line enables the Hardware Abstraction Layer Daemon, which monitors your hardware in the System.
The Final Moment Awaits



```







```
# pkg update -f
# pkg info packagename
# pkg install packagename

# pkg upgrade

查漏洞
# pkg audit -F

# pkg autoremove
# pkg clean

```



```



# freebsd-update fetch
# freebsd-update install

# freebsd-update upgrade -r 13.0-RELEASE
# freebsd-update install

```

