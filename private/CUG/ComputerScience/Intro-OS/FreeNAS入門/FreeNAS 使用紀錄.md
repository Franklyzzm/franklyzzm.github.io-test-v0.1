# FreeNAS 使用紀錄

版本：FreeNAS-11.3-U3.2

## 安裝 install

1. 下載鏡像文件 
    下載地址：https://www.freenas.org/download-freenas-release/

    * [FreeNAS 11.3-U5](https://download.freenas.org/11.3/STABLE/U5/x64/FreeNAS-11.3-U5.iso)
    * [TrueNAS CORE 12.0-U1](https://download.freenas.org/12.0/STABLE/U1/x64/TrueNAS-12.0-U1.iso)
    
2. 準備 2 個 U盤
    甲、用於製作安裝盤（下稱 **安裝盤甲**，工具） 
    乙、為 FreeNAS 系統的安裝位置，（有多餘的硬盤，也可安裝在硬盤上，即可省去 U 盤，無論 U 盤或硬盤，下稱 **系統盤乙**）

3. 製作安裝盤
    用製作工具製作安裝盤

    * win 製作工具 rufus
    * mac 製作工具 etcher
    * linux 

4. 安裝系統
    將 **安裝盤** 和 **系統盤** 均連上NAS，啟動電腦，
    根據提示，

    * 選擇安裝系統選項 Install/Upgrade
    * 選擇安裝位置，即 **系統盤乙**，當有多個硬盤時，注意選對 系統盤！！！
    * 設置 root 密碼，確認 root 密碼

    安裝完成，重啓 reboot ，拔掉 安裝盤甲

5. 登陸
    啟動完成，會顯示 IP 地址，記下 IP 地址
    在另一台電腦瀏覽器中登入該 IP 地址，
    輸入 帳戶 和 密碼
    帳戶：root
    密碼：之前設置的 root 密碼



## 使用一

1. 更改語言
    登陸帳戶後，在初始界面，點擊左側列表 **系統System** 》**常規通用General** 
    在右側找到 Language語言，更改語言選項

    * English（en）英語 默認
    * Simple Chinese（zh-hans） 簡體中文
    * Traditional Chinese（zh-hant） 繁體中文

    選好後，點擊下方的 **SAVE保存**，語言立即變換，

    翻譯有些不準確的，需要結合英語一起來看。

2. 創建帳戶

    1. 創建 用戶組UserGroups 
        在初始界面，點擊左側列表 **帳戶Accounts** 》**群組Groups** 
        根據需要，創建 **管理用戶組AdminGroup** 和 **普通用戶組NormalGroup**，（非必須，名字自訂，本文以 admingroup 和normalgroup 為例） 
        * 管理用戶組AdminGroup
            點擊右側的 **ADD添加** ，
            GID：1000（默認1000起，不用改）
            Name：admingroup
            點擊下方的 **SAVE保存**，管理用戶組創建完成
        * 普通用戶組NormalGroup
            點擊右側的 **ADD添加** ，
            GID：1001
            Name：admingroup
            點擊下方的 **SAVE保存**，管理用戶組創建完成
    2. 添加 用戶Users
        點擊左側列表 **帳戶Accounts** 》**用戶Users** 
        根據需要，創建 **管理員帳戶Admin** 和 **普通用戶user** 
        （名字自訂，本文以 admin 和 user 為例）

