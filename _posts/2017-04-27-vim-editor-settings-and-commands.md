---
layout: post
title: vim editor 설정 및 단축키
---

##vim editor 설정
1. **$sudo apt-get install vim** 을 입력하여 **vim**을 설치한다.
2. **$vi ~/.vimrc**를 입력하여 **vim** 설정파일을 열어준다.
3. 아래 설정파일을 입력한다.
```vim
set num				"show line number
set ai				"auto indent
set si				"smart indent
set cindent			"C style indent
set shiftwidth=4		"shift width = 4 spaces
set tabstop=4		"tab width = 4 spaces
set hlsearch			"highlight search word
set title			"view title
set nowrap			"disable word wrap
``` 
######**set**은 **se**로 **num**은 **nu**로 입력 가능하다.
######**"**는 주석 기호이다.
4. **vim editor**의 설정이 완료 되었다.

##vim editor 단축키
![](http://i.imgur.com/27tjp8j.jpg "width:500px;")
![](http://i.imgur.com/hfgBIAy.jpg "width:500px;")