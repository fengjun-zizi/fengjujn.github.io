# 数据库的基础
## 目录
- [1.1 数据库（Database）](#数据库database)
    - [1.2 表（table）](#表table)
    - [1.3 表名](#表名)
    - [1.4 模式](#模式)
- [2.1 列和数据类型](#列和数据类型)
## 数据库（database）
保存有组织的数据的容器（通常是一个文件夹或者一组文件）
#### 注意导致混淆

数据库管理系统也就 Database Management System.(DBMS)

### 表（table）
某种特定数据类型的结构化清单

### 表名
表名成为唯一的，实际上是数据库名和表名等的组合。但是在不同的数据库中完全可以使用相同的表名。

### 模式
关于数据库和列的布局及特性信息

### 列和数据类型
## 列（column）
表中的一个字段。所有表都是由一个或多个列表组成的
#### 数据类型
允许什么类型的数据。每个列表都有相应的数据类型（或允许） 该在列中储的数据
#### 注意
数据类型以及名称是SQL不兼容的一个主要原因
### 行（row）
**表中的一个记录** 
表中的数据是按行储存的，所保存的每个记录储存在自己的行内。
#### 说明：是记录还是行
record还有row，这两个术语多半是可以互通的，但从技术上来讲，行才是正确的术语
## 主键（primary Key）
**主键，只能用来表示特定的行，不能够用来表示列**
#### 提示
虽然并不总是需要主键，但是多数数据库设计者都会保证他们创建的每个表都具有一个主键，以便以后数据操作和管理
### 主键的条件
* 任意两行都不具有相同的主键值
* 每一行都必须具有一个主键值（主键列不允许空值NULL）
* 主键列表中值不允许修改或更新
* 主键值不能重用<br>
**主键通常定义在表的一列上，但并不是必须这么做，也可以一起使用多个列作为主键。**
## 检索数据

