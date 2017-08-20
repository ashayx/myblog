---
title: JavaScript项目
date: 2017-06-08 21:22:22
tags:
	  - demo
	  - JavaScript

---
#JavaScript 自动生成随机迷宫
---
```javascript
	for (var line=1; line<60; line++) {
		  for(var i=1;i<29;i++) {
		    var s = (Math.floor((Math.random()*2)%2)) ? "╱" : "╲";
		    document.write(s);
		  }
		  document.writeln("<br>");
		}
```
- [Demo](https://ashayx.github.io/JavaScript-demo/JavaScript练手项目/JS迷宫.html)