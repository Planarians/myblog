---
layout: post
title: Hello World～
cover: /img/cover/hello-world.png
tags: ['blog','Jekyll', '技术']
---

第一篇blog理所当然的是要讲怎么建站hhh

<!-- more -->

## 关于这个blog 

这个blog是用`jekyll`搭的，主题用的是[王爵的一亩三分地](https://github.com/biezhi/blog/){:target="_blank"}(原主题已经改了原原主题是[H2O](https://github.com/kaeyleo/jekyll-theme-H2O){:target="_blank"})  
目前挂在`github`上,评论系统是`Disqus`

## 为什么会有这个blog

嘛 其实我想搭一个blog很久了  
blog就好像自己的家一样，什么都可以放在上面感觉很舒服很，一直都好想要一个这样的地方！  
这也是我把这里叫做文具盒的原因  
想要一个可以安心把自己所有的思考 自己的残渣暂时存放记录一下的地方   
分享一下技术和兴趣

想要交到朋友 一个人好寂寞的说

自己的写作水平很差也想通过写blog来锻炼一下自己的写作和表达能力  
所以也会去参考一些写作的文字格式和风格规范  
但是我也应该不会完全按照那些建议来  
毕竟如果不能让我自由的写我想写的东西的话那就没有意义了  

## 搭这个blog的步骤
开始是想用`wordpress`，按照这篇文章来的[手把手建网教程](https://www.flyzy2005.com/build-page/){:target="_blank"}  
但是wordpress老是装不好，不知道哪一步出问题了  
访问自己的域名总是会到Nginx欢迎页面 最后也没有找到解决方法

后来又找到了一个叫`宝塔`的神奇东西可以一键帮你搭建`LNMP`和`wordpress`  
可是有一个只要之前建过站清空之后再次建站就会报错的bug  
导致我还是没能建站成功(-_＼)  
翻了半天论坛也没搞明白该怎么解决(装`wordpress`失败X2 

遂开始寻找其他的方案 ~~实在对wordpress有阴影了~~  
真的有好多啊  
这里推荐两种`jekyll`和`hexo`  
`hexo`相对`jekyll`简单一些  
而且因为作者是台湾人中文文档和教程相对较多  
很多人用的都是其中的`next主题`

我最后选择用`jekyll`来搭建博客  
用的主题是这个[王爵的blog](https://github.com/biezhi/blog/){:target="_blank"}  
基本就是把他的主题原封不动的拿过来使用了 _(:_」∠)_  

另外本站的评论系统是`Disqus`所以想要评论和看到评论需要`魔法上网`如果对你造成了麻烦还请谅解
<!-- [魔法上网](https://www.flyzy2005.com/fan-qiang/shadowsocks/install-shadowsocks-in-one-command/){:target="_blank"} -->

其实我用`Jekyll`搭建博客还有一个很重要的原因就是他在`YouTube`上发了很详细的[视频教程](https://www.youtube.com/watch?v=Zt_QzSbyDcw&list=PLK2w-tGRdrj7vzX7Y-GqKPb2QPrHCYZY1&index=1){:target="_blank"}  
用的系统刚好和我一样也是也是`Mac OS`对我有很大的参考价值感觉可以学到许多

整一个建站的过程也确实学到了很多东西  
`git`和`github`的用法  
`vscode`的使用  
`terminal`和`vim`的使用  
`markdown`语法  
……

说了这么久好像建站很复杂的样子  
但现在想想其实也是很简单的  
是我太没用了_(-ω-`_)⌒)_  
建bolg很好玩的 如果大家喜欢的话也要尝试一下啊

整理一下搭blog的方法  
如果你正好想建站而我的这篇文章能帮你在建站的过程中少走一点弯路那就太好了
1. 如果你想用最少的时间在建站上面可以考虑使用`wordpress`直接用[`宝塔`](https://www.bt.cn){:target="_blank"}来搭建
这个blog里的搭建方法也写的挺简洁 [手把手建网教程](https://www.flyzy2005.com/build-page/){:target="_blank"}
lnmp装不好可以或者找`github`上的[`lnmp一键安装包`](https://github.com/lj2007331/lnmp){:target="_blank"}
2. 如果你想在建站的过程中学多比较多的东西可以使用`jekyll`或`hexo`
`jekyll`可以看这里 [视频教程](https://www.youtube.com/watch?v=Zt_QzSbyDcw&list=PLK2w-tGRdrj7vzX7Y-GqKPb2QPrHCYZY1&index=1){:target="_blank"}我看的也是这个教程

一般途中肯定会出现一些问题的 这时候就要用好`google`和`stackflow`

## blog的内容
### 我打算写点啥
1. 碎碎念和日常思考 
2. 好用软件和技术分享 因为我还比较弱，所以会先从一些小技巧开始
3. 观后感玩后感 
动漫啊 番剧啊 轻小说啊 某个steam上新发布的独立游戏之类的
4. blog变化的过程 
想改造这个blog 比如技术和日常短文分开分别在到一个page上显示 
这个过程也会记录下来
5. 学到的技能记录
6. ……


## 其他
这篇文章是好久以前写的不过到现在这篇文章才发布出来 _(:_」∠)_  
如果你有什么建议也请告诉我

### 问题
~~那个，请问大家有办法把换行符自动转为`<br>`标签吗    
虽然在`vscode`的`markdown`预览的时候是显示有换行的，但是一旦在`jekyll`生成的blog上都是没有的。即使打开设置里面关于Markdown break里的两项还是不起作用，只能写完文章后自己在每次换行手动补上一个`<br>`真的很麻烦    
如果有人知道怎么解决的话请联系我 非常感谢〈（_  _）〉~~

（已经解决了 找到了一个叫Markdown-AutoLinefeed的VScode插件）

那个大家发现了吗，就是我很不喜欢用标点符号  
一般写点东西都是只用空格和换行  
剩下的就靠`Markdown`的语法基本能搞定  
因为这样写很方便，结构也很清晰(个人感觉一团的文字看起来很臃肿)      
所以逗号和句号用的不多  

如果大家没有逗号和句号看着很难受的话请告诉我  
我也正在学着习惯用标点符号(>﹏<)
