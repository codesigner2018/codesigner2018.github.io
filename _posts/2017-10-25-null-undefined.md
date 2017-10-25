---
title: 理解 null 和 undefined
date: 2017-10-25 11:06:49
categories:
- blog
tags: js null undefined
---
### 相同点
1. undefine 和 null 都只有一个值
2. 参与判断都返回 false
3. undefined 和 null 都没方法
### 不同点
1. null 是关键字, undefined 不是关键字
2. undefined 代表的是未初始化的东西, null 是已经初始化
3. 转化为数字的时候, undefined 返回 NAN,null 转成数字为0
