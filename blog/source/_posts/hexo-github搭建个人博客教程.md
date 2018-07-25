---
title: hexo+github搭建个人博客教程
date: 2018-07-24 11:34:38
tags:
---
# hexo
## 特点：快速、简洁且高效的博客框架
## 环境：基于node（v8.11.3)
1、环境检测：win+r输入cmd
 cmd窗口输入

```
 node -v
```
 如果提示node不是内部或外部命令
 则需要安装node
2、安装node环境
[下载](https://www.nodejs.org/zh-cn/)
 百度搜索node进入官网
点击v8.11.3下载,直接双击运行 
原声、插件、框架
# 安装git(版本控制器）
 [下载](https://www.git-scm.com/download/win)
# 安装hexo
 cmd命令：
```
 npm install hexo-cli -g
 ```
npm:基于node的包管理器，类似于ios的app stre
通过npm可以下载安装需要的插件或框架
install:安装、导入
-g:表示全局安装（在任何目录都可以使用）
# 初始化一个博客项目
1、
 ```
hexo init blog
```
2、切换到项目目录
cd 项目名
3、安装项目依赖包
```
npm install
```
4、启动服务
```
ctrl+~ hexo s
```
```
hexo new "文章名"
```
资源网站
[小图标：](http://www.easyicon.net)
[miho主题：](https://github.com/WongMinHo)

[素材](http://jspang.com/)