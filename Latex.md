#### latex箭头使用

https://blog.csdn.net/J__Max/article/details/86549124

#### _使用 \_

#### 数学标记

$ $

$$ $$

#### 插入图片：

\includegraphics[scale=0.5]{x.png}

#### 居中
\begin{center}

				\includegraphics[scale=0.5]{1.png}
				
			\end{center}
      
#### latex字体字号设置
参考博客： http://www.cnblogs.com/shawncheer/p/5844925.html
```
%导言区
\documentclass[10pt]{article} %确定normalsize大小，为可选参数，在中括号内，此为10磅，只有10，11，12磅三个选项。

\usepackage{ctex} 

%自定义字体
\newcommand{\myfont}{\textit{\textbf{\textsf{Fancy Text}}}}

%文稿区
\begin{document}
    %字体族设置（罗马字体、无衬线字体、打印机字体）
    \textrm{Roman Family} \textsf{Sans Serif Family} \texttt{Typewriter Family}    
    
    {\rmfamily Roman Family} {\sffamily Sans Serif Family} {\ttfamily Typewriter Family}
    
    {\sffamily who you are? you find self on everyone around. take you as the same as others!}
    
    {\ttfamily Are you wiser than others? definitely on. in some days, my it is true. What can you achieve? a luxurious house? a brillilant car? an admirable career? who knows?}
    
    %字体系列设置（粗细、宽度）
    \textmd{Medium Series} \textbf{Boldface Series}
    
    {\mdseries Medium Series} {\bfseries Boldface Series}
    
    %字体形状（直立、斜体、伪斜体、小型大写）
    \textup{Upright Shape} \textit{Italic Shape} \textsl{Slanted Shape} \textsc{Small Caps Shape}
    
    {\upshape Upright Shape} {\itshape Italic Shape} {\slshape Slanted Shape} {\scshape Small Caps Shape}
    
    %中文字体
    {\songti 宋体} \quad {\heiti 黑体} \quad {\fangsong 仿宋} \quad {\kaishu 楷书}
    
    中文字体的 \textbf{粗体} 和 \textit{斜体} 。
    
    %字体大小,根据normalsize的大小确定，normalsize 在文档类的参数决定
    {\tiny           Hello}\\
    {\scriptsize     Hello}\\
    {\footnotesize   Hello}\\
    {\small          Hello}\\
    {\normalsize      Hello}\\
    {\large          Hello}\\
    {\Large          Hello}\\
    {\LARGE          Hello}\\
    {\huge           Hello}\\
    {\Huge           Hello}\\
    
    %中文字号设置命令、
    \zihao{-0} 你好！
    \zihao{5} 你好！
    
    \myfont
    
\end{document}

```

目录：
```
\tableofcontents %—— 制作目录(目录是根据标题自动生成的)
```
