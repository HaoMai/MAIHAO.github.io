---
layout:     post
title:      "How to use github and jekyll to build a personal blog"
subtitle:   "Easy to build a blog"
date:       2016-07-23
author:     "MAI HAO"
header-img: "img/post-bg-js-version.jpg"
tags:
    - github
    - jekyll
---


github在过去的几年里取得了很大的进展。开发者不断的推动Git应用的发展极限。虽说，现在博客对比起朋友圈，略显落后，但仍然有很多愿意折腾的人想着自己搭建一个属于自己的博客。而github就恰恰提供了这个功能。下文就会介绍如何通过github来搭建自己的个人博客

* 首先注册github网站的账号<img src="img/firstBlog/01.jpg">

* 然后建立一个仓库<br /><img src="img/firstBlog/02.jpg"><br />

> Respository name(仓库名)必须是you_user_name.github.io

* 接着仓库实际上已经建好了，但网络上的其他教程都会说需要布置ssh的key。我是直接使用github for window的客户端的，安装成功后再登陆自己的github账号就可以自动生成ssh key了，省去了一大步骤。<a herf="http://windows.github.com/">github for window 安装官网</a><img src="img/firstBlog/03.jpg">
* 然后在网页上选择setting按钮<img src="img/firstBlog/04.jpg"><br />并点击**Launch automatic page generator**按钮，就会跳转到一个页面需要你填入一些信息

* 按照要求，填写你想写的blog资料并点击**Continue to layouts**
<img src="img/firstBlog/05.jpg">

* 最后选择模板，github就会帮你自动生成一个页面
<img src="img/firstBlog/06.jpg">

* 此时如果你只满足于这样，其实博客就已经建好了，每一次只需要按照步骤进去修改index.html中的内容就可以的了。但是，这明显与要折腾这一初衷相违背了，我们想要自己去定义layout，想有更多的灵活性。这时候jekyll就是一个不错的选择
<br /><img src="img/firstBlog/07.jpg">

> <a herf="http://jekyll.bootcss.com/" >jekyll中文官网</a>

* 随便下载一个模板下来，然后把自己的文件全部删掉**（没有看错，全部删掉）**替换为下载下来的模板的文件，大概是这样的：
<img src="img/firstBlog/08.jpg">

* 把本地文件**commit**和**sync**到服务器上，再登入你的页面，就会变成你下载的模板的样式了。接着就是各路大神自己发挥的时候了。



