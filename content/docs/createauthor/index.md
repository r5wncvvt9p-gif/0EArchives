+++
date = '2025-07-10 12:30:23'
title = '成为贡献者'
description = ""
categories = ['文档']
showAuthor = false
authors = ["Gu-f"]
weight = 50
+++

## 成为贡献者

成为贡献者，你至少要在0E档案中有属于你的一份0E档案，如果还没有，请先创作一个档案，再来看该文档。

## 创建authors

打开目录`data/authors/`,然后创建一个新的json文件，文件名为`你的昵称.json`,比如你的昵称叫`zhangsan`，那么你的文件名应该是`zhangsan.json`，并且内容的name应该为`zhangsan`内容格式如下：

```json
{
  "name": "Gu-f",
  "image": "https://avatars.githubusercontent.com/u/39210634?v=4",
  "bio": "0EArchives Creator",
  "social": [
    {
      "github": "https://github.com/Gu-f"
    }
  ]
}
```  

name：你的昵称（会以作者名显示）
image：你的头像（仅接受Github头像地址URL链接，在Github的个人首页Profile页面，找到头像，右键头像，选择复制图片地址即可）  
bio：你的一句话简介  
social：你的社交相关地址，如果有多个，需要满足如下格式：

```text
"social": [
 {
   "github": "https://github.com/Gu-f"
 },
 {
   "link": "你的博客网址"
 },
 .....如果有更多，你可以按照该格式添加更多.....
]
```

可使用的key值如下：  
`github`, `link`, `email`, `amazon`, `apple`, `blogger`, `bluesky`, `codepen`, `dev`, `discord`, `dribbble`, `facebook`, `flickr`, `foursquare`, `gitlab`, `google`, `hashnode`, `instagram`, `itch-io`,
`keybase`, `kickstarter`, `lastfm`, `linkedin`, `mastodon`, `medium`, `microsoft`, `orcid`, `patreon`, `pinterest`, `reddit`, `researchgate`, `slack`, `snapchat`, `soundcloud`, `spotify`,
`stack-overflow`, `steam`, `telegram`, `threads`, `tiktok`, `tumblr`, `twitch`, `twitter`, `x-twitter`, `whatsapp`, `youtube`, `ko-fi`, `codeberg`

添加完成后，再打开目录文件`content/contributor.md`，在里面添加你的昵称  
比如你的昵称是`zhangshan`建的是`zhangsan.json`文件，那么你应该在`authors`下添加`zhangsan`进来,如下：

```text
---
.....省略
showRelatedContent: false
authors:
  - Gu-f
  - zhangsan
---

感谢每一位0e档案的贡献者.  
```  

至此，当你再有新的档案贡献的时候，只需要在档案的头部信息参数位置，authors里面添加你的id就可以了，如下：  
```text
+++
date = '2025-07-08 08:58:35'
title = '样例-白霜离'
description = ""
tags = ['样例标签']
categories = ['样例分类']
showAuthor = false
authors = ["zhangsan"]
+++
```

恭喜你完成本节内容！    








