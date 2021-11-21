# $LaTex$ 教程

[TOC]

所有文章，创意，想法，都应该先完成内容，最后再去关注格式。

LaTex是一款非常高效的文档准备系统，支持图书，文章，论文，演示文档等。



## 内容

### 普通文字

```latex
\documentclass{article}

\begin{document}
First document. This is a simple example, with no 
extra parameters or packages included.
\end{document}
```

### 標題 作者 日期 注釋

```latex
\documentclass[12pt, letterpaper, twoside]{article}
\usepackage[utf8]{inputenc}

\title{First document}
\author{Hubert Farnsworth \thanks{funded by the Overleaf team}}
\date{February 2017}

\begin{document}

\maketitle

We have now added a title, author and date to our first \LaTeX{} document!

% This line here is a comment. It will not be printed in the document.

\end{document}
```



### 图片表格

單圖

```latex
\documentclass{article}
\usepackage{graphicx}
\graphicspath{ {images/} }

\begin{document}
The universe is immense and it seems to be homogeneous, 
in a large scale, everywhere we look at.

\includegraphics{universe}

There's a picture of a galaxy above
\end{document}
```

圖片標題，参考引用

```latex
\begin{figure}[h]
    \centering
    \includegraphics[width=0.25\textwidth]{mesh}
    \caption{a nice plot}
    \label{fig:mesh1}
\end{figure}

As you can see in the figure \ref{fig:mesh1}, the 
function grows near 0. Also, in the page \pageref{fig:mesh1} 
is the same example.
```

表格

無邊框

```latex
\begin{center}
\begin{tabular}{ c c c }
 cell1 & cell2 & cell3 \\ 
 cell4 & cell5 & cell6 \\  
 cell7 & cell8 & cell9    
\end{tabular}
\end{center}
```

有外框

```la
\begin{center}
\begin{tabular}{ |c|c|c| } 
 \hline
 cell1 & cell2 & cell3 \\ 
 cell4 & cell5 & cell6 \\ 
 cell7 & cell8 & cell9 \\ 
 \hline
\end{tabular}
\end{center}
```

```latex
Table \ref{table:data} is an example of referenced \LaTeX{} elements.

\begin{table}[h!]
\centering
\begin{tabular}{||c c c c||} 
 \hline
 Col1 & Col2 & Col2 & Col3 \\ [0.5ex] 
 \hline\hline
 1 & 6 & 87837 & 787 \\ 
 2 & 7 & 78 & 5415 \\
 3 & 545 & 778 & 7507 \\
 4 & 545 & 18744 & 7560 \\
 5 & 88 & 788 & 6344 \\ [1ex] 
 \hline
\end{tabular}
\caption{Table to test captions and labels}
\label{table:data}
\end{table}
```



```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
 
\title{Sections and Chapters}
\author{Gubert Farnsworth}
\date{ }
  
\begin{document}
  
\maketitle
  
\tableofcontents

\section{Introduction}
   
This is the first section.
      
Lorem  ipsum  dolor  sit  amet,  consectetuer  adipiscing  
elit.   Etiam  lobortisfacilisis sem.  Nullam nec mi et 
neque pharetra sollicitudin.  Praesent imperdietmi nec ante. 
Donec ullamcorper, felis non sodales...
       
\section*{Unnumbered Section}
\addcontentsline{toc}{section}{Unnumbered Section}

Lorem ipsum dolor sit amet, consectetuer adipiscing elit.  
Etiam lobortis facilisissem.  Nullam nec mi et neque pharetra 
sollicitudin.  Praesent imperdiet mi necante...

\section{Second Section}
       
Lorem ipsum dolor sit amet, consectetuer adipiscing elit.  
Etiam lobortis facilisissem.  Nullam nec mi et neque pharetra 
sollicitudin.  Praesent imperdiet mi necante...
         
\end{document}
```



### 列表

- 無序列表

  ```latex
  \begin{itemize}
    \item The individual entries are indicated with a black dot, a so-called bullet.
    \item The text in the entries may be of any length.
  \end{itemize}
  ```



- 有序列表

  ```latex
  \begin{enumerate}
    \item This is the first entry in our list
    \item The list numbers increase with each entry we add
  \end{enumerate}
  ```

### 数学公式

#### 行内公式

```latex
In physics, the mass-energy equivalence is stated 
by the equation $E=mc^2$, discovered in 1905 by Albert Einstein.
```

#### 單獨公式

```latex
The mass-energy equivalence is described by the famous equation
\[ E=mc^2 \]
discovered in 1905 by Albert Einstein. 
In natural units ($c = 1$), the formula expresses the identity
\begin{equation}
E=m
\end{equation}
```



```latex
Subscripts in math mode are written as $a_b$ and superscripts are written as $a^b$. These can be combined an nested to write expressions such as

\[ T^{i_1 i_2 \dots i_p}_{j_1 j_2 \dots j_q} = T(x^{i_1},\dots,x^{i_p},e_{j_1},\dots,e_{j_q}) \]
 
We write integrals using $\int$ and fractions using $\frac{a}{b}$. Limits are placed on integrals using superscripts and subscripts:

\[ \int_0^1 \frac{dx}{e^x} =  \frac{e-1}{e} \]

Lower case Greek letters are written as $\omega$ $\delta$ etc. while upper case Greek letters are written as $\Omega$ $\Delta$.

Mathematical operators are prefixed with a backslash as $\sin(\beta)$, $\cos(\alpha)$, $\log(x)$ etc.
```



程序代码

摘要

```latex
\begin{document}

\begin{abstract}
This is a simple paragraph at the beginning of the 
document. A brief introduction about the main subject.
\end{abstract}
\end{document}
```





乐谱



## 格式

格式，使用統一固定模板，基本一次成型，後續同一類型即可不用改動。

### 文档类型

```latex
\documentclass[12pt, a4paper]{article}
\usepackage[utf8]{inputenc}
```

 \documentclass[12pt, a4paper]{article} 
定義文檔類型，字體大小和紙張大小，默認字體大小為10pt，

 \usepackage[utf8]{inputenc}
文檔編碼，可以省略或改爲其他，中文内容建議添加。

### 页面格式

纸张大小

a0paper, a1paper, a2paper, a3paper, a4paper, a5paper, a6paper,
b0paper,  b1paper, b2paper, b3paper, b4paper, b5paper, b6paper,
c0paper, c1paper,  c2paper, c3paper, c4paper, c5paper, c6paper,
b0j, b1j, b2j, b3j, b4j,  b5j, b6j,ansiapaper, ansibpaper, ansicpaper, ansidpaper, ansiepaper,letterpaper, executivepaper, legalpaper

页边距

geometry包

```latex
\usepackage[legalpaper, landscape, margin=2in]{geometry}
```

```latex
\usepackage{geometry}
\geometry{legalpaper, landscape, margin=2in}
```



```latex
\documentclass{article}
\usepackage{blindtext}
\usepackage{geometry}
 \geometry{
 a4paper,
 total={170mm,257mm},
 left=20mm,
 top=20mm,
 }
\begin{document}
\section{Some dummy text}
\blindtext[10]
\end{document}
```



layout包

```latex
\documentclass{article}
\usepackage{layout}
\begin{document}
\section{Default \LaTeX{} layout}
Here's the default layout:

\vspace{10pt}
\layout
\section{Make some changes}
Make changes to the margin paragraph settings and use the command \verb|layout*| to redraw the page layout diagram:
\vspace{10pt}
\setlength{\marginparwidth}{0pt}
\setlength{\marginparsep}{0pt}

\layout*
\end{document}
```



### 段落格式

章節标题

```latex
\chapter{First Chapter}

\section{Introduction}

This is the first section.

Lorem  ipsum  dolor  sit  amet,  consectetuer  adipiscing  
elit.   Etiam  lobortisfacilisis sem.  Nullam nec mi et 
neque pharetra sollicitudin.  Praesent imperdietmi nec ante. 
Donec ullamcorper, felis non sodales...

\section{Second Section}

Lorem ipsum dolor sit amet, consectetuer adipiscing elit.  
Etiam lobortis facilisissem.  Nullam nec mi et neque pharetra 
sollicitudin.  Praesent imperdiet mi necante...

\subsection{First Subsection}
Praesent imperdietmi nec ante. Donec ullamcorper, felis non sodales...

\section*{Unnumbered Section}
Lorem ipsum dolor sit amet, consectetuer adipiscing elit.  
Etiam lobortis facilisissem
```

The command **`\section{}`** marks the beginning of a  new section, inside the braces is set the title. Section numbering is  automatic and can be disabled by including a **`\*`** in the section command as **`\section\*{}`**. We can also have **`\subsection{}`**s, and indeed **`\subsubsection{}`**s. The basic levels of depth are listed below:

| -1   | **`\part{part}`**                   |
| ---- | ----------------------------------- |
| 0    | **`\chapter{chapter}`**             |
| 1    | **`\section{section}`**             |
| 2    | **`\subsection{subsection}`**       |
| 3    | **`\subsubsection{subsubsection}`** |
| 4    | **`\paragraph{paragraph}`**         |
| 5    | **`\subparagraph{subparagraph}`**   |

Note that **`\part`** and **`\chapter`** are only available in *report* and *book* document classes.





字体

粗體 \textbf{...}
斜體 \textit{...}
下劃綫 \underline{...}

```latex
Some of the \textbf{greatest}
discoveries in \underline{science} 
were made by \textbf{\textit{accident}}.
```



```latex
\begin{document}

\begin{abstract}
This is a simple paragraph at the beginning of the 
document. A brief introduction about the main subject.
\end{abstract}
 
Now that we have written our abstract, we can begin writing our first paragraph.
 
This line will start a second Paragraph.
\end{document}
```

章節





多列



頁眉頁脚

頁碼

脚注



超鏈接

