---
title: "MySQL数据库学习笔记 Chapter 1 ——通用语法"
pubDate: "2024-01-06"
description: "开启新的篇章的学习~"
heroImage: "http://localhost:4321/@fs/D:/code/Hope-second-try/src/theme-simple/assets/media/11.jpg?origWidth=2176&origHeight=1224&origFormat=jpg" 
tags: ["数据库"]
---

## 目录
+ DDL —— 数据定义语言 definition 。用于定义数据库对象（数据库、表、字段）
+ DML —— 数据操作语言 manipulation 。用于对数据库中的数据进行增删改
+ DQL —— 数据查询语言 query 。用于查询数据库中表的记录
+ DCL —— 数据控制语言 control 。用于创造数据库的访问权限

***********************

##### 通用语法
+ 不区分大小写
+ 以逗号结尾
+ --后面接着的表示注释

### DDL
+ 数据库操作
![](https://imgcdn.hope-blog.top/2024-1-6/11.png)

+ 表操作
![](https://imgcdn.hope-blog.top/2024-1-6/22.png)
（attention：创建表时最后一个项目不需要添加逗号）

+ 数据类型



+ 表的相关操作
![](https://imgcdn.hope-blog.top/2024-1-6/33.png)
![](https://imgcdn.hope-blog.top/2024-1-6/44.png)
![](https://imgcdn.hope-blog.top/2024-1-6/55.png)

+ 图形化界面操作
使用 datagrip 完成安装和连接 mysql 数据库之后可以在应用中直接以图形化的操作完成上面的操作
![](https://imgcdn.hope-blog.top/2024-1-6/66.png)

### DML
+ 表内容的修改
关键字：updata 表名 set 字段名1=值1 ，字段名2=值2，[where 条件]；
不加条件表示对所有内容进行修改，需要做进一步确认。

![](https://imgcdn.hope-blog.top/2024-1-6/77.png)
![](https://imgcdn.hope-blog.top/2024-1-6/88.png)

+ 表内容的删除
delate语句不能删除某个字段的值，要删除某个字段的值可以使用上面的关键字update为NULL；
关键字：delate from 表名 [where 条件]

![](https://imgcdn.hope-blog.top/2024-1-6/99.png)



