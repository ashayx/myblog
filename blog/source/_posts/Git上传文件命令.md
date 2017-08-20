---
title: Git上传文件命令
date: 2017-06-09 15:05:31
tags:
	  - Git

---
#### 上传单个文件
$ git add readme.txt
#### 上传全部文件
$ git add -A
#### 提交
<!-- more -->
$ git commit -m "备注"
#### 如果远程地址存在
$ git remote rm origin
#### 提交远程仓库
$ git remote add origin 地址
#### 执行代码合并
$ git pull --rebase origin master
#### 上传
$ git push -u origin master


