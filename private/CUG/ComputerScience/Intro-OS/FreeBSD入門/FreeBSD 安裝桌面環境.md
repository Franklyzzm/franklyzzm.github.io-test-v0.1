# FreeBSD 安裝桌面環境

更換鏡像源



Install Desktop Entertainment

````````


````````

root: 

 pkg update

 pkg install nano neofetch

```
nano /etc/fstab

proc     /proc     procfs     rw    0  0

```



`pkg install xorg gnome-desktop gdm ` 

`gnome3-lite`

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

