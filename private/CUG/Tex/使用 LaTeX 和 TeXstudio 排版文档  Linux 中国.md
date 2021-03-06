## 使用 LaTeX 和 TeXstudio 排版文档 | Linux 中国

LaTeX 是一个服务于高质量排版的[文档准备系统](https://mp.weixin.qq.com/s?__biz=MjM5NjQ4MjYwMQ==&mid=2664630413&idx=3&sn=41da668036dfb54b4d31f8a33e753997&chksm=bdcf33cb8ab8badd14b0eaa9457d02c01f1b7e8c8f3470b7c08d32686f863b1482b1d2cca5ff&scene=126&sessionid=1614071489&key=11181a169f195a6ce7ba448095fff4b96b33e382ad9c7b420f91b46473402cb7fe81f82667b257dbdb62d6727419db1c362905fa89e99510736e1a90b8323992106db51343b9878e7ab82dc7db4c1bab250ee0ba1d6d0750cbcbe0743216b2a862bbf3018ee45e880cb29ac10b74be736c5bb235145edfca1eacf973ca2dffcd&ascene=1&uin=Mjg5MTY2ODAw&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=ASRWX0aM%2Fdfl6UQ%2B8MY7xUc%3D&pass_ticket=p5wDckb0NilXhEzO6vQFD%2FtjA4g4zxj4S2S9Oe1obZMV3%2BnektYknlCGoWhME9He&wx_header=0)。通常用于大量的技术和科学文档的排版。不过，你也可以使用 LaTex 排版各种形式的文档。教师可以编辑他们的考试和教学大纲，学生可以展示他们的论文和报告。这篇文章让你尝试使用 TeXstudio。TeXstudio 是一个便于编辑 LaTeX 文档的软件。

启动 TeXstudio

如果你使用的是 Fedora Workstation，请启动软件管理，然后输入 TeXstudio 以搜索该应用程序。然后选择安装并添加 TeXstudio 到你的系统。你可以从软件管理中启动这个程序，或者像以往一样在概览中启动这个软件。

或者，如果你使用终端，请输入 `texstudio`。如果未安装该软件包，系统将提示你安装它。键入 `y` 开始安装。

```
$ texstudiobash: texstudio: command not found...Install package 'texstudio' to provide command 'texstudio'? [N/y] y
```



你的第一份文档

LaTeX 命令通常以反斜杠 `\` 开头，命令参数用大括号 `{}` 括起来。首先声明 `documentclass` 的类型。这个例子向你展示了该文档的类是一篇文章。

然后，在声明 `documentclass` 之后，用 `begin` 和 `end` 标记文档的开始和结束。在这些命令之间，写一段类似以下的内容：

```
\documentclass{article}\begin{document}The Fedora Project is a project sponsored by Red Hat primarily to co-ordinate the development of the Linux-based Fedora operating system, operating with the vision that the project "creates a world where free culture is welcoming and widespread, collaboration is commonplace, and people control their content and devices". The Fedora Project was founded on 22 September 2003 when Red Hat decided to split Red Hat Linux into Red Hat Enterprise Linux (RHEL) and a community-based operating system, Fedora.\end{document}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc68icfibB00RRSwLaUUnicrrp4mtF9kutmUR1ws7NsmxAvMiaAiajrc2hQ0onLpoDxLV5UXPB1MqYzBgqpw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



使用间距

要创建段落分隔符，请在文本之间保留一个或多个换行符。下面是一个包含四个段落的示例：

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc68icfibB00RRSwLaUUnicrrp4mN36RJxebcnoHHhzk3zC4AZ2Z5hzQAVe4MvbPHGkmmE19xX6yCNwzCQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

从该示例中可以看出，多个换行符不会在段落之间创建额外的空格。但是，如果你确实需要留出额外的空间，请使用 `hspace` 和 `vspace` 命令。这两个命令分别添加水平和垂直空间。下面是一些示例代码，显示了段落周围的附加间距：

```
\documentclass{article}\begin{document}\hspace{2.5cm} The four essential freedoms\vspace{0.6cm} A program is free software if the program's users have the 4 essential freedoms:The freedom to run the program as you wish, for any purpose (freedom 0).\vspace{0.2cm}The freedom to study how the program works, and change it so it does your computing as you wish (freedom 1). Access to the source code is a precondition for this.\vspace{0.2cm}The freedom to redistribute copies so you can help your neighbour (freedom 2).\vspace{0.2cm}The freedom to distribute copies of your modified versions to others (freedom 3). By doing this you can give the whole community a chance to benefit from your changes. Access to the source code is a precondition for this.\end{document}
```

如果需要，你也可以使用 `noindent` 命令来避免缩进。这里是上面 LaTeX 源码的结果：

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc68icfibB00RRSwLaUUnicrrp4m6JqvZjDbQHAsz21ZqibO81aBRefDI38ib00TzNg9IGvJZtrMYiaukJptw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



使用列表和格式

如果把自由软件的四大基本自由列为一个清单，这个例子看起来会更好。通过在列表的开头使用`\begin{itemize}`，在末尾使用 `\end{itemize}` 来设置列表结构。在每个项目前面加上 `\item` 命令。

额外的格式也有助于使文本更具可读性。用于格式化的有用命令包括粗体、斜体、下划线、超大、大、小和 textsc 以帮助强调文本：

```
\documentclass{article}\begin{document}\hspace{2cm} {\huge The four essential freedoms}\vspace{0.6cm} \noindent {\large A program is free software if the program's users have the 4 essential freedoms}:\begin{itemize}\item \vspace{0.2cm}\noindent \textbf{The freedom to run} the program as you wish, for any purpose \textit{(freedom 0)}. \vspace{0.2cm}\item \noindent \textbf{The freedom to study} how the program works, and change it so it does your computing as you wish \textit{(freedom 1)}. Access to the source code is a precondition for this.\vspace{0.2cm}\item \noindent \textbf{The freedom to redistribute} copies so you can help your neighbour \textit{(freedom 2)}.\vspace{0.2cm}\item \noindent \textbf{The freedom to distribute copies of your modified versions} to others \textit{(freedom 3)}. \tiny{By doing this you can give the whole community a chance to benefit from your changes.\underline{\textsc{ Access to the source code is a precondition for this.}}}\end{itemize}\end{document}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc68icfibB00RRSwLaUUnicrrp4mgPdtzKcle90yoIs649UUmdAxK4b96Yuz9C3iavQC6h0d0XNScMjo5vA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



添加列、图像和链接

列、图像和链接有助于为文本添加更多信息。LaTeX 包含一些高级功能的函数作为宏包。`\usepackage` 命令加载宏包以便你可以使用这些功能。

例如，要使用图像，可以使用命令 `\usepackage{graphicx}`。或者，要设置列和链接，请分别使用 `\usepackage{multicol}` 和 `\usepackage{hyperref}`。

`\includegraphics` 命令将图像内联放置在文档中。（为简单起见，请将图形文件包含在与 LaTeX 源文件相同的目录中。）

下面是一个使用所有这些概念的示例。它还使用下载的两个 PNG 图片。试试你自己的图片，看看它们是如何工作的。

```
\documentclass{article} \usepackage{graphicx}\usepackage{multicol}\usepackage{hyperref}\begin{document}  \textbf{GNU} \vspace{1cm} GNU is a recursive acronym for "GNU's Not Unix!", chosen because GNU's design is Unix-like, but differs from Unix by being free software and containing no Unix code. Richard Stallman, the founder of the project, views GNU as a "technical means to a social end". Stallman has written about "the social aspects of software and how Free Software can create community and social justice." in his "Free Society" book. \vspace{1cm} \textbf{Some Projects} \begin{multicols}{2} Fedora \url{https://getfedora.org} \includegraphics[width=1cm]{fedora.png} GNOME \url{https://getfedora.org} \includegraphics[width=1cm]{gnome.png} \end{multicols}\end{document}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc68icfibB00RRSwLaUUnicrrp4mxJg8kecCiaKfOo7aoicxbLlQicfClJibW36rV9kOkfXBjZY4gME1KPsE6Q/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这里的功能只触及 LaTeX 功能的表面。你可以在该项目的[帮助和文档站点](https://mp.weixin.qq.com/s?__biz=MjM5NjQ4MjYwMQ==&mid=2664630413&idx=3&sn=41da668036dfb54b4d31f8a33e753997&chksm=bdcf33cb8ab8badd14b0eaa9457d02c01f1b7e8c8f3470b7c08d32686f863b1482b1d2cca5ff&scene=126&sessionid=1614071489&key=11181a169f195a6ce7ba448095fff4b96b33e382ad9c7b420f91b46473402cb7fe81f82667b257dbdb62d6727419db1c362905fa89e99510736e1a90b8323992106db51343b9878e7ab82dc7db4c1bab250ee0ba1d6d0750cbcbe0743216b2a862bbf3018ee45e880cb29ac10b74be736c5bb235145edfca1eacf973ca2dffcd&ascene=1&uin=Mjg5MTY2ODAw&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=ASRWX0aM%2Fdfl6UQ%2B8MY7xUc%3D&pass_ticket=p5wDckb0NilXhEzO6vQFD%2FtjA4g4zxj4S2S9Oe1obZMV3%2BnektYknlCGoWhME9He&wx_header=0)了解更多关于它们的信息。

------

via: https://fedoramagazine.org/typeset-latex-texstudio-fedora/