---
layout:     post
title:      "个人博客搭建笔记"
subtitle:   "基于ubuntu14.04.2、Github和Jekyll"
category:    blog
date:       2015-03-08 
author:     "L-Cubed"
---

## 安装Jekyll

1. 添加taobao源

        $ gem sources --remove https://rubygems.org/    
        $ gem sources --remove http://rubygems.org/    
        $ gem sources -a https://ruby.taobao.org/  

2. 安装rvm和ruby

        $ sudo apt-get install curl
        $ sudo gem install rvm
        $ \curl -sSL https://get.rvm.io | bash
        $ source /home/username/.rvm/scripts/rvm
        $ rvm install ruby-2.2.1
        $ rvm use ruby-2.2.1
        
3. 安装js runtime

        $ sudo apt-get install nodejs
        
        $ gem install execjs
        
4. 安装Jekyll

        $ gem install jekyll
        
## 创建远程仓库

在Github上新建以 `username.github.io` 命名的远程仓库。

## 使用Jekyll themes

在  [**jekyll themes**](http://jekyllthemes.org/)选择自己喜欢的主题下载到本地，解压缩。将其对应的文件夹重名为 `username.github.io` ，并进行个人信息修改。

## Push本地仓库到Github

    git remote add origin git@github.com:username/username.github.io.git          
    git push -u origin master
        
 等待大约10分钟左右，就可以通过访问 `http://username.github.io` 对博客进行查看了。
        


