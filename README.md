# Unique CV

一个使用LaTex编写的简历模板，尽量使用了一些简单的LaTex语句，方便使用者改写。

forked from [dyinnz/uniquecv](https://github.com/dyinnz/uniquecv)

### 我的改动

+ 增加了下划线链接支持
+ 调整了版面样式以容纳更多内容
+ 增加更适合英文简历排版的unqiuecv_en

### 依赖

+ 使用XeLatex编译
+ 依赖包：ctex, titlesec, color, setspace, fontawesome

#### Fedora 25:
+ 使用`dnf install texlive`安装texlive
+ 使用`dnf install texlive-ctex`安装依赖包，其他包类似

### 参考

+ https://github.com/billryan/resume
+ https://www.sharelatex.com/blog/2013/06/28/how-to-write-a-latex-class-file-and-design-your-own-cv.html

### 依赖包说明
+ ctex: 支持中文
+ titlesec: 定制section/subsection的标题
+ color: 定义颜色
+ setspace: 设置行间距
+ fontawesome: 设置常用icon，如电话、邮箱、Github等

### 定制建议
+ \tiny \small \normalsize \large \Large \LARGE \huge \Huge 改变字体大小
+ \makebox 对齐中间的文字
+ \begin{spacing}{1.0} 改变行间距
+ \smallskip \medskip \bigskip 插入垂直空白
+ ~ \quad \qquad 插入水平空白
+ \hspace{1.0em} \vspace{1.0ex} 插入水平/垂直空白
+ \textbf 加粗 \textit 斜体/楷体

### 提示
不同平台下的latex渲染效果可能不同，mac可能会出现ctex使用字体不正常的情况，需要修改ctex安装目录下的字体设置。