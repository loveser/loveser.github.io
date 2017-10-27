title: Java学习：基础
author: John Doe
date: 2017-03-16 02:38:03
tags:
---
## java基本类型和引用类型
#### 8种基本类型
1. 4种整型（byte，int，short，long）
 - byte 1字节 -128～127
 - short 2字节 -32768～32767
 - int 4字节 -2147483648～ 2147483657
 - long 8字节 
2. 2种浮点类型
 - float 4字节 32位 IEE 754单精度
 - double 8字节 64位 
3. 1种unicode编码的字符单元
 - char 2字节 整个Unicode字符集
4. 1种真值类型
 - boolean 1位 True和false

#### 3种引用类型
- 类 class
  可以是我们创建的，这里不多说，其中说几个特殊类
  - Object：是java的根类，是每个类的超类
  所有对象（包括数组）都实现这个类的方法。用Object可以定义所有的类 如： 
  
   `Object object= new Integer(1); 来定义一个Interger类` 

 - String：String类代表字符串，Java 程序中的所有字符串字面值（如"abc"）都作为此类的实例来实现。检查序列的单个字符、比较字符串、搜索字符串、提取子字符串、创建字符串副本、在该副本中、所有的字符都被转换为大写或小写形式。
 - Void： Void类是一个不可实例化的占位符类，它保持一个对代表 Java 关键字 void 的 Class 对象的引用。 
- 接口 interface
  可以是我们创建的，这里我不多讲，主要是讲解几个java库中的接口interface 
  

- 数组 array




## 两种类型区别
存储方式不同，基本类型其值直接保存在变量中，引用类型其值保存的只是指向实际对象的地址
