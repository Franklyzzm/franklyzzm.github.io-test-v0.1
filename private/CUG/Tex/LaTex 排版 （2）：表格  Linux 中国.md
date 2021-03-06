## LaTex 排版 （2）：表格 | Linux 中国

**导读：**LaTeX 提供了许多工具来创建和定制表格　 　 　 　 　 　 　 　 　 　 　 　 　 　 　 　 

LaTeX 提供了许多工具来创建和定制表格，在本系列中，我们将使用 `tabular` 和 `tabularx` 环境来创建和定制表。

基础表格

要创建表，只需指定环境 `\begin{tabular}{列选项}`：

```
\begin{tabular}{c|c}    Release &Codename \\ \hline    Fedora Core 1 &Yarrow \\    Fedora Core 2 &Tettnang \\    Fedora Core 3 &Heidelberg \\    Fedora Core 4 &Stentz \\\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHSxxzr22dy7u7iadR2oWeWb3kwJWH28miby1qad1WmzHibusdicJOpNOL6g/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Basic Table*

在上面的示例中，花括号中的 ”{c|c}” 表示文本在列中的位置。下表总结了位置参数及其说明。

< 如显示不全，请左右滑动 >

| 参数      | 位置               |
| --------- | ------------------ |
| `c`       | 将文本置于中间     |
| `l`       | 将文本左对齐       |
| `r`       | 将文本右对齐       |
| `p{宽度}` | 文本对齐单元格顶部 |
| `m{宽度}` | 文本对齐单元格中间 |
| `b{宽度}` | 文本对齐单元格底部 |



> `m{宽度}` 和 `b{宽度}` 都要求在最前面指定数组包。

使用上面的例子，让我们来详细讲解使用的要点，并描述你将在本系列中看到的更多选项：

< 如显示不全，请左右滑动 >

| 选项            | 意义                                                   |
| --------------- | ------------------------------------------------------ |
| `&`             | 定义每个单元格，这个符号仅用于第二列                   |
| `\\`            | 这将终止该行并开始一个新行                             |
| `|`             | 指定表格中的垂直线（可选）                             |
| `\hline`        | 指定表格中的水平线（可选）                             |
| `*{数量}{格式}` | 当你有许多列时，可以使用这个，并且是限制重复的有效方法 |
| `||`            | 指定表格中垂直双线                                     |



![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)

定制表格

学会了这些选项，让我们使用这些选项创建一个表。

```
\begin{tabular}{*{3}{|l|}}\hline	\textbf{Version} &\textbf{Code name} &\textbf{Year released} \\\hline	Fedora 6 &Zod &2006 \\ \hline	Fedora 7 &Moonshine &2007 \\ \hline	Fedora 8 &Werewolf &2007 \\\hline\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHiawiabUxzHlsmOv3SBRdK3FU7fO5fxEpxplm2FJa3ibMAFYkWuRtyVtTw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Customise Table*



管理长文本

如果列中有很多文本，那么它的格式就不好处理，看起来也不好看。

下面的示例显示了文本的格式长度，我们将在导言区中使用 `blindtext`，以便生成示例文本。

```
\begin{tabular}{|l|l|}\hline	Summary &Description \\ \hline	Test &\blindtext \\\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHHcH95br4XrYqQKFJhyup1P5eFBRldxUwTp8T6b9Diay5MjusicAiasAUw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Default Formatting*

正如你所看到的，文本超出了页面宽度；但是，有几个选项可以克服这个问题。

◈ 指定列宽，例如 `m{5cm}`

◈ 利用 `tablarx` 环境，这需要在导言区中引用 `tablarx` 宏包。

![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)

使用列宽管理长文本

通过指定列宽，文本将被折行为如下示例所示的宽度。

```
\begin{tabular}{|l|m{14cm}|} \hline	Summary &Description \\ \hline	Test &\blindtext \\ \hline\end{tabular}\vspace{3mm}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHfxEaiaDzB9PVkEoU1sJkM62bzqh17OjHgluOZqjia1nGZ86eIgTbYnsg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Column Width*



使用 tabularx 管理长文本

在我们利用表格之前，我们需要在导言区中加上它。`tabularx` 方法见以下示例：`\begin{tabularx}{宽度}{列选项}`。

```
\begin{tabularx}{\textwidth}{|l|X|} \hlineSummary & Tabularx Description\\ \hlineText &\blindtext \\ \hline\end{tabularx}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHFmwxJjcSejicjkoFGHIeHMXmvyXU8MoC2DpA57Cj5UzInicyFyduMCQw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Tabularx*

请注意，我们需要处理长文本的列在花括号中指定了大写 `X`。



合并行合并列

有时需要合并行或列。本节描述了如何完成。要使用 `multirow` 和 `multicolumn`，请将 `multirow` 添加到导言区。

![img](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)

合并行

`multirow` 采用以下参数 `\multirow{行的数量}{宽度}{文本}`，让我们看看下面的示例。

```
\begin{tabular}{|l|l|}\hline	Release &Codename \\ \hline	Fedora Core 4 &Stentz \\ \hline	\multirow{2}{*}{MultiRow} &Fedora 8 \\	&Werewolf \\ \hline\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHdjWZLNwGEk84TfCmH3PfAhjSHl6JSvKzPao3XTCbkdyle2WPXbC52A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*MultiRow*

在上面的示例中，指定了两行，`*` 告诉 LaTeX 自动管理单元格的大小。



合并列

`multicolumn` 参数是 `{multicolumn{列的数量}{单元格选项}{位置}{文本}`，下面的示例演示合并列。

```
\begin{tabular}{|l|l|l|}\hline	Release &Codename &Date \\ \hline	Fedora Core 4 &Stentz &2005 \\ \hline	\multicolumn{3}{|c|}{Mulit-Column} \\ \hline\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHMASnibJQnXnChwBwpJkBUjdZ3ItF6cb0QxnI4BmNCiaT628gicc06erbg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Multi-Column

使用颜色

可以为文本、单个单元格或整行指定颜色。此外，我们可以为每一行配置交替的颜色。

在给表添加颜色之前，我们需要在导言区引用 `\usepackage[table]{xcolor}`。我们还可以使用以下颜色参考 [LaTeX Color](https://mp.weixin.qq.com/s?__biz=MjM5NjQ4MjYwMQ==&mid=2664630553&idx=2&sn=7abe0e520397aec0cca9ab51093122c0&chksm=bdcf325f8ab8bb496260812e5ab317799fa6bda7d67380f8f0a8b17ea653fcc76c11872738db&scene=126&sessionid=1614071032&key=927fcfeac83feaf86d48d92599f67d77b7bb996f6ce3db41ca7d37ba16c356167a81c5f5dff4c7bd2302722901f8fd15f6ba7bda6a434db8253803ed6ffa834be664452b7893a7c240b6570ce12021ef2c1e711d87dc90fd325e74467cd3fae928c94d2b6d281d8cb31ecce61e3b25b79134f6094b3f0737656d135cc4ee3839&ascene=1&uin=Mjg5MTY2ODAw&devicetype=Windows+10+x64&version=62090538&lang=zh_CN&exportkey=AS31wVjY6IWDmvd2Oo%2BQ5LM%3D&pass_ticket=p5wDckb0NilXhEzO6vQFD%2FtjA4g4zxj4S2S9Oe1obZMV3%2BnektYknlCGoWhME9He&wx_header=0) 或在颜色前缀后面添加感叹号（从 0 到 100 的阴影）来定义颜色。例如，`gray！30`。

```
\definecolor{darkblue}{rgb}{0.0, 0.0, 0.55}\definecolor{darkgray}{rgb}{0.66, 0.66, 0.66}
```

下面的示例演示了一个具有各种颜色的表，`\rowcolors` 采用以下选项 `\rowcolors{起始行颜色}{偶数行颜色}{奇数行颜色}`。

```
\rowcolors{2}{darkgray}{gray!20}\begin{tabular}{c|c}	Release &Codename \\ \hline	Fedora  Core 1 &Yarrow \\	Fedora Core 2 &Tettnang \\	Fedora Core 3 &Heidelberg \\	Fedora Core 4 &Stentz \\\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHeQGuFlXymb10fvnwIsJYk9Bugnwm1bPicxibhSI5plIZeF6gndEjhvLQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Alt colour table*

除了上面的例子，`\rowcolor` 可以用来指定每一行的颜色，这个方法在有合并行时效果最好。以下示例显示将 `\rowColors` 与合并行一起使用的影响以及如何解决此问题。

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHDmxFNnIMQJjiciaJQ4kjPAupJctPfB6EeiaDYsNO2Ilk5ibrOU6DHQ2UhQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Impact on multi-row*

你可以看到，在合并行中，只有第一行能显示颜色。想要解决这个问题，需要这样做：

```
\begin{tabular}{|l|l|}\hline	\rowcolor{darkblue}\textsc{\color{white}Release}  &\textsc{\color{white}Codename} \\ \hline	\rowcolor{gray!10}Fedora Core 4 &Stentz \\ \hline	\rowcolor{gray!40}&Fedora 8 \\	\rowcolor{gray!40}\multirow{-2}{*}{Multi-Row} &Werewolf \\ \hline\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHSTRIxcKB91zJ37eV3uMr2UBnveVb38bc0XGaYcMYrGzickMYa5m8j6A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Multi-row*

让我们讲解一下为解决合并行替换颜色问题而实施的更改。

◈ 第一行从合并行上方开始

◈ 行数从 `2` 更改为 `-2`，这意味着从上面的行开始读取

◈ `\rowcolor` 是为每一行指定的，更重要的是，多行必须具有相同的颜色，这样才能获得所需的结果。

关于颜色的最后一个注意事项是，要更改列的颜色，需要创建新的列类型并定义颜色。下面的示例说明了如何定义新的列颜色。

```
\newcolumntype{g}{>{\columncolor{darkblue}}l} 
```

我们把它分解一下：

◈ `\newcolumntype{g}`：将字母 `g` 定义为新列

◈ `{>{\columncolor{darkblue}}l}`：在这里我们选择我们想要的颜色，并且 `l` 告诉列左对齐，这可以用 `c` 或 `r` 代替。

```
\begin{tabular}{g|l} 	\textsc{Release}  &\textsc{Codename} \\ \hline	Fedora Core 4 &Stentz \\	&Fedora 8 \\	\multirow{-2}{*}{Multi-Row} &Werewolf \\\end{tabular}\
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHFYFnlAtnEjdqEksYpB3hJRBx9jmOotDoc2uxn8kms98saqWD3YJ8fA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Column Colour*

横向表

有时，你的表可能有许多列，纵向排列会很不好看。在导言区加入 `rotating` 包，你将能够创建一个横向表。下面的例子说明了这一点。

对于横向表，我们将使用 `sidewaystable` 环境并在其中添加表格环境，我们还指定了其他选项。

◈ `\centering` 可以将表格放置在页面中心

◈ `\caption{}` 为表命名

◈ `\label{}` 这使我们能够引用文档中的表

```
\begin{sidewaystable}\centering\caption{Sideways Table}\label{sidetable}\begin{tabular}{ll}	\rowcolor{darkblue}\textsc{\color{white}Release}  &\textsc{\color{white}Codename} \\	\rowcolor{gray!10}Fedora Core 4 &Stentz \\	\rowcolor{gray!40} &Fedora 8 \\	\rowcolor{gray!40}\multirow{-2}{*}{Multi-Row} &Werewolf \\\end{tabular}\vspace{3mm}\end{sidewaystable}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHSiafS7uTTeVmBKsoNBUDOfR3VzXarOEEw7DPn9E5xicXTC7SS8ibYvlzQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*Sideways Table*



列表和表格

要将列表包含到表中，可以使用 `tabularx`，并将列表包含在指定的列中。另一个办法是使用表格格式，但必须指定列宽。

用 tabularx 处理列表

```
\begin{tabularx}{\textwidth}{|l|X|} \hline	Fedora Version &Editions \\ \hline	Fedora 32 &\begin{itemize}[noitemsep]		\item CoreOS		\item Silverblue		\item IoT	\end{itemize} \\ \hline\end{tabularx}\vspace{3mm}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHP5ldrAAbv0JspbEzYABw1M9XFAQGaM1ibaxFS5hIeqQ9KKCnE34IVLA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*List in tabularx

用 tabular 处理列表

```
\begin{tabular}{|l|m{6cm}|}\hline        Fedora Version &amp;amp;amp;Editions \\\ \hline    Fedora 32 &amp;amp;amp;\begin{itemize}[noitemsep]        \item CoreOS        \item Silverblue        \item IoT    \end{itemize} \\\ \hline\end{tabular}
```

![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHUBfqF70IMA0JK9pA4MbTlG8NjNiciaJWEtVvCZj2SFjl0ibia8MWAOw0AQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

*List in tabular*



总结

LaTeX 提供了许多使用 `tablar` 和 `tablarx` 自定义表的方法，你还可以在表环境 （`\begin\table`） 中添加 `tablar` 和 `tablarx` 来添加表的名称和定位表。



LaTeX 宏包

所需的宏包有如下这些：

```
\usepackage{fullpage}\usepackage{blindtext}  % add demo text\usepackage{array} % used for column positions\usepackage{tabularx} % adds tabularx which is used for text wrapping\usepackage{multirow} % multi-row and multi-colour support\usepackage[table]{xcolor} % add colour to the columns\usepackage{rotating} % for landscape/sideways tables
```





![图片](https://mmbiz.qpic.cn/mmbiz_png/W9DqKgFsc6ib5guA2SanCay0AWXCY9peHFYFnlAtnEjdqEksYpB3hJRBx9jmOotDoc2uxn8kms98saqWD3YJ8fA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

------

via: https://fedoramagazine.org/latex-typesetting-part-2-tables/