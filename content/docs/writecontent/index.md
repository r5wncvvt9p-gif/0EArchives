+++
date = '2025-07-10 12:20:25'
title = '6.开始写作'
description = ""
categories = ['文档']
showAuthor = false
authors = ["Gu-f"]
weight = 6
+++

## 了解写作基本规范

到这里，你已经完成了所有的准备工作，可以开始你的写作之路了。  
在真正开始写作之前，你需要了解基本的写作规范，目的是为了方便管理以及方便其他协作者阅读，毕竟没有人愿意阅读一个混乱的内容。  
**基本规范**：

1. 文件夹及文件分布

- 0E档案内容统一放到content/posts目录下面，并以文件夹作为最小单位。
- 每个档案文件夹下面至少要存在index.md文件，该文件是你的写作区域。
- 对应档案的其他相关资源，如档案中出现的一些资源、图片，均放到档案文件夹下，与index.md文件同级，并使用相对引用。

2. index.md文件内容格式
   index.md文件夹至少要有一个文件头部信息，样例如下：

   ```text
   +++
   date = '2025-07-08 08:58:35'
   title = '样例-白霜离'
   description = ""
   tags = ['样例标签']
   categories = ['样例分类']
   showAuthor = false
   authors = ["Gu-f"]
   +++
   
   xxxxxxx具体内容
   ```  
   `date`：该篇档案的写作时间  
   `title`：该篇档案的标题，通常是对应的具体的人或物的名字  
   `description`：该篇档案的简单描述  
   `tags`：该篇档案的标签，可以有多个['标签1','标签2']，至少有一个，并且能提现档案中的人或物  
   `categories`: 该篇档案的分类，可以有多个['分类1','分类2']，至少有一个，并且能准确归类档案中的人或物  
   `showAuthor`：统一值为false，只有0E档案公告性质的内容才允许设置为true  
   `authors`：该档案作者，请填写你的名称ID，如何创建一个名称ID详情见[成为贡献者](/docs/createauthor/)  
   `xxxxxxx具体内容`：是你要写作的具体位置，你可以任意发挥，支持Markdown语法和HTML语法

   在进行填写tags和categories的时候，请优先查阅[现有的分类](https://0e.pw/categories/)和[现有的标签](https://0e.pw/tags/)，如果已经存在，请不要创建新的，而应该使用现有的。  
   以上为常规档案格式，更多设置见[文章头部参数]()

   已经提前写好了一个[档案样例](https://0e.pw/posts/exatemples/)，在`content/posts/exatemples`目录下，供参考，不一定非要使用这种格式，内容部分可任意发挥。

恭喜你完成本节内容！    








