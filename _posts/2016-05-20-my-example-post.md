---
layout: page
title:  "个人博客的搭建"
subtitle: "一条很闲的鱼的生活"
date:   2020-09-10 21:21:21 +0530
categories: ["博客的搭建"]
---

#搭建个人技术博客

>GitHub Pages+Jekyll 快速部署个人博客

> - GitHud Pages:
>    - 定义：GitHud注册网站给用户提供一个个人主页
>    - 如何访问：个人域名：用户名：githud.io
>    - 然后编写主页：建立一个用个人域名为项目名的远程版本仓库，只需要向该远程版本仓库中的mastsr分支提交代码即可（该代码中必须有一个文件，叫index.html文件）
> - Jekyll
>     - 定义：可以将Maekaown语法自动翻译成html语法的工具
>     - 安装：不需要自己安装，在githud网站当中预安装的
>     - 使用：不用人为去使用，当你请求个人域名的时候githud服务器会读取仓库（以个人域名命名的那个远程版本仓库）中的mastsr分支中的代码，如果该代码为Markdown语法为自动调用jekyll将其编译为HTML代码病防护客户端

- 建立一个以个人域名为为项目名的远程版本仓库
- 访问一个网址：主题网址：http://jekyllthemes.org/，选择一个主题将其代码复制到我们仓库的mastsr分支
- 以上两步可以合并为一步，在主题仓库中点击fork，跳转页面之后，点击satting设置仓库名，即可 
- 将远程版本库中的代码克隆到本地
    - 点击头像，点code，复制链接
    - 从文件打开终端执行克隆https://github.com/cse-qingting/cse-qingting.githud.io.git
    -从远程版本仓库克隆下来的代码会自动创建本地版本仓库
- 修改配置文件以及页面内容
- 书写博客
