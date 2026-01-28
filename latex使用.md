### latex使用

1.换行     **\par**或者两个\n

2.居中对齐，放在

\begin{center}

\end{center}

3.左对齐

\begin{flushleft}

\end{flushleft}

4.**下划线**

\underline

**斜体**

\textit

**黑体**

\textbf

5.插入图片（默认左对齐）

\includegraphics[scale=1.5,angle=45]{图片名称}

6.浮动图片导入一个包

\begin{figure}[h]

\includegraphics[scale=1.5,angle=45]{图片名称}

\end{figure}

7.文字包围图片(没懂)

\use package {wrapfigure}

\begin{wrapfigure}{r}{0.25\textwidth}

\includegraphics[width=0.25\textwidth]{mesh}{图片名称}

\end{wrapfigure}

8.给图片插入题目

\caption{fdfd}

9.两个图片对应一个标题

先使用\usepackage{subcaption}

给每个图片首尾加两行代码

10.引用图片\ref{图片的名称}





