# 如何高效的整理文献并做综述（使用docear）
阅读大量的paper是研究生一项基本的工作，尤其是在做一项课题研究的初期，而有些文献我们在读过一遍时就会被束之高阁，当我们想再次查阅时就会变得特别不方便。或者，当我们阅读一定量文献之后，想要利用手头的资源做一篇文献综述，那么如果前期就对文献做了细致的管理和标记则又可以是我们事半功倍，本文介绍了如何使用docear高效的管理我们的文献。

本博客主要分为两部分，第一部分即使用docear来整理文献，第二部分即进一步的使用docear来做文献综述或其他文章。

* <b> 下载并安装docear </b>

   [下载地址](http://www.docear.org/software/download/) ,双击后安装。然后创建第一个项目。
 
* <b> 创建项目 </b>
 
 ![project](https://www.pianshen.com/images/36/017adbbb6f26a2ee6b08d1140130dd7c.JPEG)
 
 一次打开docear,或者在主视图里面选择create new project，即可创建一个新的项目。
  + 注意两点：
   1. 现有的数据资源如pdf最后放在home文件夹下（用PDFs/Literature）add 来添加路径。
   2. 如果文献已经生成.bib文件则最好也按照上述方式添加路径。

* <b>项目组织结构</b>

![struct](https://www.pianshen.com/images/38/fcaeca21c5e7bb81c7f7e0453c7887ae.JPEG)

例如上图显示的是我创建的一个名为sentiment的project, 其中papers是我创建的用来存放paper的，而bib文件是我创建的用来存放.bib文件的。（在创建项目时指定，如果忘记指定会使用默认的，后期也可以更改）

* <b>整体预览</b>

如果papers文件里包含多篇论文，则点击Library中的Literature&Annotations,然后再点击里面头结点也就是箭头所指的刷新按钮。
![view](https://www.pianshen.com/images/224/2e7bf2d8227ba4e2145d5dc08f3c2638.JPEG)

When you click the refresh icon on the root-node, Docear searches for new PDFs and annotations in your literature repository. All new PDFs are listed in the Incoming node. New annotations are attached to existing PDFs or listed in the Incoming node if the corresponding PDF is not linked in the mind map.）点击之后即可导入所包含的论文pdf,导入之后的论文的都会放在Incoming节点下，然后我们也可以新建子节点或者兄弟节点，也可以拖动论文至我们需要的地方。例如我们新建的”survey”节点下，有子节点”sentiment analysis”, “sentiment analysis”下有我们拖过来的一篇论文。这样的话就可以把我们所有的论文合理的归类和整理。
需要注意的是，每次点击箭头所指的刷新按钮，都会添加文件夹中新的pdf和笔记（annotations）到Incoming节点中。

* <b>细节方法</b>

    1. 笔记
    
    PDF和Annotations（笔记）是docear中重要的概念，annotations可以是pdf里的书签或者是高亮之后的标注。首先我们看一下书签形式：
    
    ![note](https://www.pianshen.com/images/166/350427ac8641bc54f579a9d68cf7444e.JPEG)
    
    如果一篇paper有书签结构则可以直接在图中paper节点下显示。
    接下来我们关注我们在pdf中做的批注，我们用pdf阅读器打开一篇文章做批注一下图为例：
    
    ![note1](https://www.pianshen.com/images/264/14469012d442e62937423a4497c42fe8.JPEG)
    
    然后保存之后，再点击整体预览图中箭头所指的刷新按钮。
    
    ![note2](https://www.pianshen.com/images/764/2a56342456c19e4c201ee893e65330bc.JPEG)
    
    
