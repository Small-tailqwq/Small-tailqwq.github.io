---
layout: page
title: 关于
permalink: /about/
icon: heart
type: page
---



## 介绍

这里本该是主题作者的个人介绍，但慢慢开始摸索这玩意了，所以先把这里改了吧～（毕竟最简单  
高三废物，基本都是无所事事的状态。搞博客完全是兴趣使然，虽然支出的确可能有超预期…  
**但是开心就好～**难道不是吗？

## 兴趣

玩游戏吧？当然最好是有人一起的那种…  
平时R6、FF14什么的都有在玩。
偶尔看看日轻、漫画、番剧什么的…总而言之就是一个肥宅啦～手办什么的入了潜坑…不过立马就跳了（不能温水煮青蛙了  
其实要说的话摄影也有点兴趣…不过穷是原罪…  
不说了，感觉什么有趣的都能吸引我的兴趣，不过要我深入了解熟悉一件事可是蛮困难的（毕竟我是懒狗嘛）

## 你可以……

[康康我的GitHub](https://github.com/Small-tailqwq)|[发邮件骚扰](mailto:Small_tailqwq@qq.com)  
[关注我的微勃](http://weibo.com/u/5610377163)|[订阅我的推忑](https://twitter.com/123_Smalltail)  
[Steam好友喜加一（假的](http://weibo.com/u/5610377163)

## 关于本站

直接fork的徐代龙大佬的源码  
基于GitHub Pages  
未来会慢慢改进
原本的一些博文可能会删除，取而代之会将徐佬的博客加入显而易见的地方以便观摩（坑  
收藏夹不打算删除。保留一些干货，另外会加上我自己收集的一些网站。  
衷心感谢徐代龙大佬的教程与源码，另外赞美一下github这美妙的速度（比WP的托管不知道高到哪里去了

## 友情链接（建设中…优先级别低）
[DreamMaker](https://fordes123.github.io/friends/)

## 留言
可在此添加友链（要求不多，博客名字和链接就行，可以的话加个图标也不是不可以（应该能实现的吧…））

{% include comments.html %}


### 更新日志（保留）
*2019.10.28*
* `[^]`添加来必力评论系统：本来是disqus体验不错的，可惜被墙）
* `[^]`绑定百度统计：谷歌的之前也绑了…虽然都没什么用…底栏与文章👀图标浏览量预计下次修复
* `[^]`虽然不知道这是什么格式，但是照着些就完事了！ （关于节目添加留言）（其实就是评论）
* 域名被QQ搞了，心烦…


*2017.2.28*

- `[^]` 修复目录滚动 bug [#22](https://github.com/Gaohaoyang/gaohaoyang.github.io/issues/22), [#48](https://github.com/Gaohaoyang/gaohaoyang.github.io/issues/48)

*2016.6.20*

* `[+]` 在文章页中添加上一篇和下一篇文章链接。
* `[^]` 修改 font-family 顺序，避免微软雅黑将单引号解析为全角。
* `[^]` 修复标签云算法中被除数为零的 bug。[#26](https://github.com/Gaohaoyang/gaohaoyang.github.io/issues/26), [#28](https://github.com/Gaohaoyang/gaohaoyang.github.io/issues/28), [#30](https://github.com/Gaohaoyang/gaohaoyang.github.io/issues/30)

*2016.5.11 v2.0.1*

* `[^]` 优化代码，将页面中的大段评论相关代码抽离出来，放入`comments.html`
* `[+]` 添加百度统计和Google分析代码，在`_config.yml`中配置相关参数即可
* `[+]` 更新文档，添加博客主题使用方法，便于上手
* `[+]` 添加了`favicon.ico`
* `[^]` 修复 bug，目录太长时，滚动到最底部时隐藏到footer下面。修复后长目录在滚动到底部时使用`position:absolute`
* `[^]` 修改目录区的滚动条样式（仅针对`webkit`内核浏览器）
* `[^]` 修改 demo 页中 disqus 评论区 a 标签的颜色 bug，修改 blockqoute 中 p 标签的 margin
* `[+]` 添加不蒜子计数功能，在footer上显示访问量
* `[+]` 添加回到顶部功能

*2016.4.27 v2.0.0*

* `[^]` 基于 jekyll 3.1.2 重构了所有代码
* `[+]` 主页添加了摘要，在正文中使用4个换行符来分割，可在`_config.yml`中修改
* `[+]` 主页添加了近期文章、分类列表和标签云
* `[+]` 主页导航区做了视觉优化，阴影效果
* `[+]` 增加了归档、标签和分类页面
* `[+]` 增加了收藏页面
* `[+]` 评论插件可以选择 disqus 或 多说，直接在`_config.yml`中修改
* `[+]` 适配移动端
* `[+]` 页面滚动时，文章目录固定在右侧
* `[+]` 页面内容较少时，固定 footer 在页面底部
* `[^]` 使用 GitHub 风格的代码高亮写法，即\`\`\`的写法，去除`highlight.js`代码高亮插件的使用
* `[^]` 使用 Masonry 重写了 Demo 页中的瀑布流布局，响应式交互体验更好
* `[-]` 去除了 jQuery 和 BootStrap，使得加载速度更快

* 2016.3-2016.4 进行了一次大的改版和重构，详见 [README](https://github.com/Gaohaoyang/gaohaoyang.github.io/blob/master/README.md) 和博文 [对这个 jekyll 博客主题的改版和重构](http://gaohaoyang.github.io/2016/03/12/jekyll-theme-version-2.0/)
* 2015.3-2015.4 完成了这个博客主题的第一版。
