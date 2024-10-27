---
title: 博客搭建历程
date:  2024-10-15
tags: [hexo,NexT]
categories: Hexo
---
> 如何从零开始搭建博客
在开始搭建个人博客之前，需要准备以下事项：
1. GitHub账户
2. Zeabur账户
3. Hexo
步骤一   安装Hexo
在电脑上安装Node.js 打开命令提示符， 输入以下命令以安装Hexo
```
cnpm install -g hexo-cli
```
安装完成后 使用以下命令初始化一个新的Hexo项目
```
hexo init myblog
cd myblog
npm install
```
步骤二：配置Hexo
在项目的根目录下，会有一个名为_config.yml的文件 可以在这里改网站的相关内容
步骤三：选择主题
可以通过以下命令安装一个新的主题：
```
npm install hexo-theme-landscape
```
在_config.yml文件中指定主题
```
theme: landscape
```
步骤四：生成静态文件
完成Hexo和主题的配置后，使用以下命令生成静态文件：
```
hexo g
```
此命令会在您项目目录下生成一个public文件夹
步骤五：部署到GitHub
现在，将这些静态文件部署到GitHub上。创建一个新的GitHub仓库。在本地的Hexo项目目录下，初始化Git并将代码推送到GitHub：
```
git init
git add.
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yourusername/yourrepo.git
git push -u origin main
```
请将yourusername和yourrepo替换成您的GitHub用户名和仓库名称。
步骤六 使用Zeabur部署
使用Zeabur进行一键部署。在注册Zeabur账户后，按照平台的指示将您的GitHub仓库与Zeabur关联
