---
layout: post
title: 如何创建个人博客
category: aboutBlog
tags: [aboutBlog]
excerpt: 绝知此事要躬行
---
2020年春节，一场病毒🦠把我们困在了小小的屋子里。作为非医护的我们，只能乖乖呆在家里，精神上支持国家，支持辛苦的医护们！一觉醒来，假期余额变多了···那么多天的假期只能宅在不到9平方的小屋子里，天天面壁。那就找点事情来做吧！一时心血来潮，我就开启了搭建自己的博客之旅。
网上的教程说得可简单了！让我觉得真的就是30分钟就能搭建起来一个自己的博客！然后可以开始愉快地写我的微博。然鹅！**我还是太年轻了！**倒腾了一个多星期，才逐渐把博客改成了自己想要的样子。一路跌跌撞撞，摸着石头过河，终于把初始的框架搭出来了。尽管还有很多缺陷，界面也不是那么的友好，很多的问题有待改善。
## 1.注册github
进去全球最大的男性交友网站：<https://github.com/>，注册个人的账号。
## 2.购买独立域名
选购独立域名，个人选择了[腾讯云](https://cloud.tencent.com/act/domainsales?from=11394)，购买一个喜欢的域名就可以了，然后进行配置。具体如何配置自行搜索。
## 3.获取代码，准备环境
根据文档<https://www.cnblogs.com/ityouknow/p/9680137.html>进行操作，获取代码到自己的github上。  
**注意⚠️**  
* 项目名称必须要以.github.io结尾  
* github上设置 GitHub Pages，这样提交代码才会被部署到环境中。    
## 4.修改代码，部署程序
这个就要靠自己的代码能力了，把代码修改，让博客成为自己想设计的模样  
## 5.下载jupyter工具，学习markdown编写规则
### 1. 安装：
* 升级pip到最新版:pip install --upgrade pip    
* 安装Jupyter Notebooks:pip install jupyter    
### 2. 修改目录空间：  
* 先在本地创建一个文件夹，用来存放jupyter的工作目录，如：/Users/jupyter   
* 输入命令行：jupyter notebook --generate-config  
* 修改#c.NotebookApp.notebook_dir = ''此条配置，将#去掉，该目录地址填入为上述创建的jupyter工作目录：c.NotebookApp.notebook_dir = '/Users/jupyter'  
### 3. 启动jupyter：  
* jupyter notebook  
### 4. 设置主题颜色  
* pip install --upgrade jupyterthemes  
* jt -l  
* jt -t gruvboxl -N -T（设置主题并且显示toolbar)  
### 5. 编写文件，保存为md格式。把下载的文件放到这个项目的_posts目录中，推送到github上就可以成功发表文章了。  

