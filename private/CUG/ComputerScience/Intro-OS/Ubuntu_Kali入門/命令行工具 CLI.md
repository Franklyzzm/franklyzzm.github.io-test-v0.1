# 命令行工具 CLI

[TOC]

## 一、sudo 

## 二、apt-get（apt）的基本使用

1、安装软件 
apt-get（apt） install softname1 softname2...
2、卸载软件 
apt-get（apt） remove softname1 softname2...
3、卸载并清除配置 
apt-get（apt） remove --purge softname1
4、更新软件信息数据库
apt-get（apt） update
5、进行系统升级 
apt-get（apt） upgrade
6、修正依赖关系 
apt-get（apt） -f install
7、获取包的相关信息
apt-cache show sofname1（获取如说明、大小、版本等）
8、搜索软件包 
apt-cache search softname1 softname2...

## 三、dpkg的基本使用
1、安装软件 
dpkg -i xxx.deb （dpkg -i /share/google-chrome-stable_current_amd64.deb）
注意：如果通过dpkg –i安装软件后由于依赖关系没有安装成功,可通过apt-get –f install解决
2、安装一个目录下面所有的软件包
dpkg -R 目录路径 （dpkg -R /usr/local/src）
3、删除软件包 
dkpg -r xxx.deb
4、连同配置文件一起删除
dpkg -r --purge xxx.deb
5、查看软件包信息 
dpkg -info xxx.deb
6、查看文件拷贝详情 
dpkg -L xxx.deb
7、查看系统中已安装软件包信息
dpkg -l （ii表示安装成功，iU表示未安装成功）
8、查看已安装包的详细情况 
dpkg -s 安装包名称（包括版本和依赖之类的）





