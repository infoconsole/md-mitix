# Markdown --从入门到精通
#### 导语： ####
[Markdown](http://www.jianshu.com/p/1e402922ee32/)是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的 HTML 标记语言来说，Markdown 可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。
## 一、认识Markdown ##
> 在刚才的导语里提到，Markdown 是一种用来写作的轻量级「标记语言」，它用简洁的语法代替排版，而不像一般我们用的字处理软件 Word 或 Pages 有大量的排版、字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。目前来看，支持 Markdown 语法的编辑器有很多，包括很多网站（例如简书）也支持了 Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出 HTML 格式的文件用来网站发布，也可以十分方便的导出 PDF 格式，这种格式写出的简历更能得到 HR 的好感。甚至可以利用 CloudApp 这种云服务工具直接上传至网页用来分享你的文章，全球最大的轻博客平台 Tumblr，也支持 Mou 这类 Markdown 工具的直接上传。
### Markdown官方文档 ###
> 这里可以看到官方文档Mrakdown语法文档，当然，**后面我也会用自己的方式阐述这些语法的具体使用**

* [创始人 John Gruber 的 Markdown 语法说明](http://daringfireball.net/projects/markdown/syntax)
* [Markdown 中文版语法说明](http://wowubuntu.com/markdown/#list)

### 使用Markdown的有点 ###

> * 专注你的文字编辑工作而不是排版的问题
* 轻松的导出HTML、PDF、和本身的.MD文档格式
* 纯文本文件可以使用任何的编辑器
* 随时修改你的文章版本，不必像文字处理软件一样生成若干个版本导致的混乱
* 可读，直观，学习成本低

### 使用Markdown的误区 ###
> We believe that writing is about content, about what you want to say – not about fancy formatting. 
> 我们坚信写作写的是内容，所思所想，而不是花样格式。
> — Ulysses for Mac

- Markdown 旨在简洁、高效，也由于 Markdown 的易读易写，人们用不同的编程语言实现了多个版本的解析器和生成器，这就导致了目前不同的 Markdown 工具集成了不同的功能（基础功能大致相同），例如流程图与时序图，复杂表格与复杂公式的呈现，虽然功能的丰富并没有什么本质的缺点，但终归有些背离初衷，何况在编写的过程中很费神，不如使用专业的工具撰写来的更有效率，所以如果你需实现复杂功能，专业的图形界面工具会更加方便。**当然，你如果对那些不同客户端带来的高级特性感兴趣，那也无可厚非**

## 二、我们该使用什么工具 ##

### Mac os ###
> - 在 Mac OS X上，我强烈建议使用[Mon](http://25.io/mou/ "好看的Markdown工具")这款免费且十分好看并且十分好用的markdown编辑工具，他支持**实时预览**，即左边是你编辑的markdown语言，右边会实时生成效果。不仅如此，Mon还有些有趣的偏好设置 ，例如主题（Themes）和样式（css），他可以配置出个性化的编辑效果和文本编辑效果，如果你对自带的主题和样式不满意，可以到[GitHub](https://github.com/search?utf8=%E2%9C%93&q=Mou "Mon主题") 上搜索自己喜欢的样式。

> - 如果是文字工作者，强烈建议购买[Ulysses for Mac](https://ulyssesapp.com/)，这款软件入围了Mac App Store的The Best of  2013。他支持更多的写作格式、多文档的支持。Mon iAwriter 这些软件都是基于单文档管理方式，而Ulysses支持Folder、Filter的管理，一个Folder里面可以创建过个sheet.sheet之间也可以进行combine处理 

### Windows ###
> - windows下可以使用[Markdown](http://www.markdownpad.com/),[MarkPad](http://code52.org/DownmarkerWPF/)

## 三、Markdown的语法 ##

### 换行 ###

默认空行就会被识别成换行

就像

这样

### 标题 ###

> 标题是每个文章都需要也是最常用的格式，在markdown中，如果一段文字为标题，那么在这段文字前加#即可

> \# 一级标题

> \## 二级标题

> \### 三级标题

> 以此类推，一共可以使用6级标题 

### 列表 ###

> 熟悉HTML的同学肯定知道，有序列表和无序列表的区别

> 在Markdown下，无序列表显示需要在文字前面加上 \- 或者 \* 或者 \+

> * 1
> + 2
> - 3

> 在Markdown下，有序列只需要输入数字

> 1.XXX
> 
> 2.33aaa
> 
> 3.llll

### 引用 ###

如果你需要引用一小段别处的句子，那么就要增加引用格式。

> 这段就是一个引用
> 只需要在引用的文字前面增加一个 \> 就可以了

### 图片与链接 ###

插入图片的语法:  \!\[\]\(\)

插入链接的语法： \[\]\(\)

当然，在markdown工具下一般都是有快捷键的，可以尝试使用 

![](http://i.imgur.com/qC5XufV.png)  

### 自动链接 ###

<http://www.163.com/>

这样就可以自动链接到网站地址了


### 粗体和斜体  强调语法 ###

_markdown_  and   *markdown*  这两个效果好像是一样的

__markdown__ and **markdown** 这两个效果好像是一样的

___markdown___ and ***markdown*** 这两个效果好像是一样的


### 表格语法 ###

姓名 | 年龄 |爱好 |
---|---|---|
oldflames                | 表格的对其其实不太容易掌握|看自己的编辑习惯
测试一下表格的长度怎么计算的 | xxxxxxxxxx |aaaaa
自带了隔行功能|看看效果      |

### 代码语法 ### 

使用··来标记代码  就是键盘1旁边的那个键,一般单句代码就这么标记就可以了

`System.out.println("编辑一句代码")`

使用缩进处理整个代码
	
    public void setup() throws MalformedObjectNameException {
		this.mBeanServer = ManagementFactory.getPlatformMBeanServer();
	}

### 分割线 ###

使用***进行分个操作

***

### 实用的中划线功能 ###

该功能可以用来注释文档什么的   看一下例子

~~Delete~~  

这个方式   在github风格上面是支持的   不一定所有的编辑器都能支持

### 特殊符号转意 ###

下列符号前加上\ 将表示原来的意思  需要经过转意

|符号|意义
|---|---
|\  |反斜杠
|'  |引号
|*  |星号
|_  |下划线
|{} |花括号
|[] |方括号
|() |括号
|#  |＃号
|+ - |+ -
|.   |英文点号
|!   |感叹号

e.g例子

\\  \'  \*  \_  \{\}  \[\]  \(\)  \# \. \! 


## 三、推荐相关技巧 ##

### 图片保存 ###

1.自己新建github账户，新建git仓库  
2.图片上传到git仓库  然后进去找到图片地址
3.在markdown插入图片  github的图片地址就可以   这样图片保存内容可控

e.g ![](https://raw.githubusercontent.com/infoconsole/md-mitix/master/2017/eclipse32.png)

### markdown同步工具 ###

> 推荐使用有道云笔记  话说大黄易是不是要给我广告费