# Ubuntu OS 入門

本篇文章从Ubuntu安装后的首次开机使用开始，安装方法请看另一篇文章《Ubuntu的安装》。

## 介绍 Introduce

### 术语

首先明确一些基本的术语：

* 终端 Terminal：命令行工具，快捷键：”Alt+Ctrl+T“
* sudo：以管理员权限执行
* apt：包管理器
* update：更新
* upgrade：升级
* full-upgrade：版本升级
* 所有的命令行输完，都是按回车确认，执行。

## 安装基本软件

在安装Ubuntu系统时，如果是最小化（Minimal）安装，则没有这些基础软件，需要手动安装；如果是完全（Full）版本的，就已经安装完成了，无需手动安装。

1. 检查更新：`sudo apt update` 
2. 确认升级：`sudo apt upgrade -y` 
3. 安装软件：`sudo apt install [softname]`
    * `sudo apt install net-tool vlc` vlc视频播放，Firefox播放网页视频需要依赖
    * `sudo apt install libreoffice` 办公软件

至此，已经基本满足家庭影音、文字办公需求。



## 常見問題 F Q&A

1. 問：Ubuntu 休眠 睡眠 鍵盤、鼠標無法喚醒。
   答：



# Kali OS 入門

## 介绍 Introduce

## 版本 **Kali [Branches](https://www.kali.org/docs/general-use/kali-branches/)：**

- **kali-rolling**
- **kali-last-snapshot** yyyy.1/yyyy.2/...

