# 1 Introduction

## 1.1 Java语言概述
Java：Java语言是美国Sun公司（Stanford University Network），在1995年推出的高级的编程语言。所谓编程语言，是计算机的语言，人们可以使用编程语言对计算机下达命令，让计算机完成人们需要的功能

Java语言应用：Java语言主要应用在互联网程序的开发领域。常见的互联网程序比如天猫、京东、物流系统、网银系统等，以及服务器后台处理大数据的存储、查询、数据挖掘等也有很多应用。

## 1.2 基础知识
+ 二进制
- 计算机中数据采用二进制
- 逢二进一
- 十进制转二进制：除二取余
- 二进制转十进制：2的幂指数编码
+ DOS命令
- 盘符切换：c: （盘符名）
- 查看当前文件夹： dir
- 进入文件夹：cd
- 清屏：cls

# 2 Java语言开发环境
## 2.1 Java虚拟机--JVM
### JVM
JVM：Java虚拟机，简称JVM，是运行所有Java程序的假想计算机，是Java程序的
运行环境，是Java 最具吸引力的特性之一。我们编写的Java代码，都运行在 JVM 之上。

不同平台具有不同版本的JVM虚拟机，Java运行在JVM中，故Java语言具有跨平台的特性。

### JRE&JDK
* JRE(Java Runtime Environment): Java运行环境
* JDK(Java Development Kit): Java开发工具包

# 3 HelloWorld入门
## 3.1 程序开发流程
编写、编译、运行

## 3.2 HelloWorld编写
```
public class helloworld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## 3.3 Java程序编译

```
javac helloworld.java
```
编译成功之后，获得一个helloworld.class，是Java的可运行文件，称为字节码文件，有了字节码文件，就可以运行程序。


## 3.4 运行Java程序

```
java helloworld
```

## 3.5 说明

* 编译 ：是指将我们编写的Java源文件翻译成JVM认识的class文件，在这个过程中， javac 编译器会检查我们所写的程序是否有错误，有错误就会提示出来，如果没有错误就会编译成功。

* 运行 ：是指将 class 文件 交给JVM去运行，此时JVM就会去执行我们编写的程序了。

## 3.6 注释
* 单行注释以 // 开头 换行结束
* 多行注释以 /* 开头  以*/结束

## 3.7 关键字

abstract assert boolean break byte case catch char class const continue	default	do	double	else enum	extends	final	finally	float for	goto	if	implements	import instanceof	int	interface	long	native new	package	private	protected	public return	strictfp	short	static	super switch	synchronized	this	throw	throws transient	try	void	volatile	while true	false	null

## 3.8 标识符

+ 标识符 ：是指在程序中，我们自己定义内容。比如类的名字、方法的名字和变量的名字等等，都是标识符。

+ 命名规则： 硬性要求
- 标识符可以包含 英文字母 26个(区分大小写) 、 0 -9数字 、 $ （美元符号） 和 _ （下划线） 。
- 标识符不能以数字开头。
- 标识符不能是关键字。
+ 命名规范： 软性建议
- 类名规范：首字母大写，后面每个单词首字母大写（大驼峰式）。
- 方法名规范： 首字母小写，后面每个单词首字母大写（小驼峰式）。
- 变量名规范：全部小写。

