# Ubuntu 使用

[toc]

## 安装 install 

### 1. wps

文档

### 2. sublime

文本

### 3. typora

文档

### 4.synaptic 

软件管理 **S**oft **P**ackage **M**anager

### 5.gdebi

deb安装

### 6.gimp

位图 处理

### 7.inkscape

矢量图 处理

### 8.krita

绘画

### 9.foliate / calira

阅读

### 10.homebank

家庭理财

### 11.virtualbox

虚拟机

### 12.pycharm

python

### 13.stellarium

天文

### 14. goldendict

词典

sudo apt install goldendict

### 15. Adobe reader / forit reader

sudo apt-get install gdebi-core

Enter the root password to complete the gdebi installation. If it doesn’t prompt for one, nothing to worry. Wait for the installation complete notification in the Terminal.

STEP 4: We shall install Adobe Reader now. Copy and Paste the following command in the Terminal. Use the right-click context menu to paste. Ctrl +V won’t work in Terminal. This command will download the pdf installer Debian binary from Adobe’s official servers.

wget ftp://ftp.adobe.com/pub/adobe/reader/unix/9.x/9.5.5/enu/AdbeRdr9.5.5-1_i386linux_enu.deb

STEP 5: Use the gdebi command to install the downloaded .deb binary package.

sudo gdebi Adbe*.deb

### 16. xxx





## 高级安装 

### 1.ssh

openssh



### 2.vim



### 2. samba



### 3. vnc



### 3.latex

```
See /usr/local/texlive/2020/index.html for links to documentation.
The TeX Live web site (https://tug.org/texlive/) contains any updates and
corrections. TeX Live is a joint project of the TeX user groups around the
world; please consider supporting it by joining the group best for you. The
list of groups is available on the web at https://tug.org/usergroups.html.
Add /usr/local/texlive/2020/texmf-dist/doc/man to MANPATH.
Add /usr/local/texlive/2020/texmf-dist/doc/info to INFOPATH.
Most importantly, add /usr/local/texlive/2020/bin/x86_64-linux
to your PATH for current and future sessions.
Logfile: /usr/local/texlive/2020/install-tl.log

```

#### 3.1miktex


a. Register GPG key

sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys D6BC243565B2087BC3F897C9277A7293F59E4889

b. Register installation source
Ubuntu 20.04 LTS (Focal Fossa):

echo "deb http://miktex.org/download/ubuntu focal universe" | sudo tee /etc/apt/sources.list.d/miktex.list

Ubuntu 18.04 LTS (Bionic Beaver):

echo "deb http://miktex.org/download/ubuntu bionic universe" | sudo tee /etc/apt/sources.list.d/miktex.list

Ubuntu 16.04 LTS (Xenial Xerus):

echo "deb http://miktex.org/download/ubuntu xenial universe" | sudo tee /etc/apt/sources.list.d/miktex.list

c. Install MiKTeX

sudo apt-get update
sudo apt-get install miktex

d. Finish the setup



macOS

MiKTeX executables can be found

    in ~/bin, if you have installed MiKTeX for your private use
    or in /usr/local/bin, if you have installed MiKTeX system-wide

Setting PATH for Terminal

Since /usr/local/bin is usually in the PATH for Terminal, it remains the case of a private installation. Run this command to add ~/bin permanently to the Terminal PATH:

echo export 'PATH=~/bin:$PATH'>> ~/.bash_profile

Setting PATH for GUI applications

You can use the command-line utility launchctl to modify PATH for GUI applications. Either

sudo launchctl config user path "$HOME/bin:$PATH"

if you have a private installation, or

sudo launchctl config system path "/usr/local/bin:$PATH"

for a system-wide setup.




### 4.桌面mac化

sudo apt install gnome-tweaks gnome-tweak-tool



https://www.gnome-look.org/p/1241688/#files-panel



http://ubuntuhandbook.org/index.php/2020/08/mac-os-catalina-theme-ubuntu-20-04/ 
https://www.linuxmi.com/ubuntu-20-04-mac-os-catalina.html

### 5.gimp ps化

```mac``````curl -L "https://github.com/Diolinux/PhotoGIMP/releases/download/1.0/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip" -o ~/Downloads/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip && unzip ~/Downloads/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip -d ~/Downloads && sudo cp -R ~/Downloads/PhotoGIMP\ by\ Diolinux\ v2020\ for\ Flatpak/.var/app/org.gimp.GIMP/config/GIMP/2.10/ ~/Library/Application\ Support/GIMP/2.10 && rm ~/Downloads/PhotoGIMP.by.Diolinux.v2020.for.Flatpak.zip```

### 6.filezilla

sftp:

### 7.lantern

science surfing
https://github.com/getlantern/lantern

