- 什么是软件
	- 软件是一系列按照**特定顺序组织**的计算机**数据**和**指令**的集合，有系统软件和应用软件之分
	- ```programs=data structures + algorithms```
- 人机交互方式
	- 图形化界面（GUI）
	- 命令行方式（GLI）：需要在控制台输入特定指令让计算机完成操作
- 常用DOS命令
	- 磁盘操作系统（DOS）：单用户单任务（只能执行一个任务）的操作系统
	- cd、md、dir、clear、del

- java语言概述
	- 是sun公司```1995年```推出的一门高级编程语言
	- java是印度尼西亚爪洼岛的英文名称，因盛产咖啡闻名![[Pasted image 20230712110642.png]]
	- 重要时间结点
		- | java 1.2  | java拆分成：J2SE（标准版）、J2EE（企业版）、J2ME（小型版）    |
		| --------- | ------------------------------------------------------------- |
		| java 5.0  | 1.版本号从1.4直接更新到5.0 2.平台更名为JavaSE、JavaEE、JavaME |
		| java 8.0  | 继5.0以外变化最大的版本，长期支持版本                                                  |
		| java 11.0 | JDK安装包取消独立JRE安装包，是长期支持版本（LTS）             |
		| java 17.0 | 版本号也称21.9，是长期支持版本                                                              |
	- java开发环境
		- JDK：java程序开发工具包
		- JRE：java程序运行环境，包含JVM和运行时所需的核心类库
		- JVM:java虚拟机，是java程序运行环境
			- 自动内存管理，减少了内存泄漏(与c语言最大的不同)
		- ![[Pasted image 20230712113217.png]]
	- java特有的文档注释
		- 文档注释可以被jdk提供的工具javadoc所解析，生产一套以网页文件形式体现的该程序的说明文档
			- javadoc -d mydoc(这是文件夹名) -author -version HelloWorld.java
			```
			 /**
			 这就是文档注释
			 @author emomo
			 @version 17.0
			 */
		 ```

![[Pasted image 20230729224123.png]]