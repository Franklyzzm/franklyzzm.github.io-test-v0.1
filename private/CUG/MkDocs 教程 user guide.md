# MkDocs 教程 user guide

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.



## 創建項目

創建 項目 `my_project_name` ，並到 項目目錄；

在 終端 中輸入以下命令: `my_project_name` 為妳自己的項目名稱。

```
mkdocs new my_project_name
cd path/my_project_name
```

<img src="https://www.mkdocs.org/img/initial-layout.png" alt="The initial MkDocs layout" style="zoom:100%;" />

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.



## 修改配置文件

打開配置文件 `mkdocs.yml`，更改網站名字 `site_name` 並保存。 

```
site_name: your_site_name
```



## 添加頁面

### 添加導航標題欄

在 配置文件 中加入以下信息：

```
site_name: your_site_name # 你的網站名字
nav: # 導航
    - Home: index.md # 首頁
    - About: about.md # 關於
```

## 添加主題

在 配置文件 中加入 **主題** 設置：

```
site_name: your_site_name # 你的網站名字
nav: # 導航
    - Home: index.md # 首頁
    - About: about.md # 關於
theme: readthedocs # 主題：主題名字
```

## 添加網站圖標

在 `docs` 目錄下創建名為 `img` 的目錄文件，將自定義圖標文件 `favicon.ico` 放在此目錄中。

## 構建網站

至此，你的 `your_site_name` 網站相關文件已經準備就緒，我們可以構建網站了。

```
mkdocs build
```

這會創建一個叫 `site` 的新目錄，裡邊內容如下：

```
$ ls site
about  fonts  index.html  license  search.html
css    img    js          mkdocs   sitemap.xml
```

