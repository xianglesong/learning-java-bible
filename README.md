# Java 宝典

### 科学家实验失败了，他知道为什么失败了；工程师实验成功了，他不知道为什么成功。

### 十大名言：
	1. Talk is cheap，show me code.
	2. 没有银弹。
	3. 一开始就优化是万恶之源。
	4. 重构到模式。
	5. 源码面前了无秘密。
	6. 用户为中心。
	7. 不要重复发明轮子。
	8. Hadoop 不是建造更大的牛。
	9. 一个字：拆。
	10. 256K is OK.

## 计算机基础知识
1. ### 编程语言
	1. C
		1. C程序设计语言
		1. C程序设计语言(英文版)
		1. C指针
		2. [视频][C语言程序设计](http://study.163.com/curricula/cs.htm)
		
	1. C++
		1. http://www.cprogramming.com/里有个c-tutorial
		2. 高质量C++/C编程指南 林锐 博士
		3. GCC: The Complete Reference
		3. [源码][https://github.com/antirez/redis](https://github.com/antirez/redis) 
		4. [源码][https://github.com/nginx/nginx](https://github.com/nginx/nginx)

1. ### 数据结构和算法
	1. [数据结构与算法分析：Java语言描述](http://product.dangdang.com/23918741.html)
	1. [大话数据结构]()
	1. [Java数据结构和算法]() 英文《Data Structures & Algorithms in Java》Robert Lafore著，特别推荐。
	1. [视频][数据结构和算法](http://study.163.com/course/introduction/468002.htm)
	1. [数据学习的可视化网站http://zh.visualgo.net](http://zh.visualgo.net)
	
	1. [算法导论](http://product.dangdang.com/22927209.html) 算法的最好的图书之一。
		1. [视频][麻省理工学院公开课：算法导论](http://open.163.com/special/opencourse/algorithms.html) 老头讲的非常好，年轻的一般。
	1. [算法](http://product.dangdang.com/22880871.html) Knuth的学生写的，使用Java语言描述，值得一看。
	1. [leetcode](https://leetcode.com)

	1. [lintcode](https://www.lintcode.com/problem/?tag=lintcode-copyright)
	
	1. 大神的书[Donald E. Knuth:图灵奖得主]
		1. [计算机程序设计艺术 卷1 基本算法](http://product.dangdang.com/23839682.html)
		1. [计算机程序设计艺术 卷2 半数值算法](http://product.dangdang.com/24007299.html)
		1. [计算机程序设计艺术 卷3 排序与查找](http://product.dangdang.com/24195308.html)
			1. 这些图书我是看不了，只能翻一番，排序和查找可以看看。
			
1. ### 操作系统
	1. [操作系统设计与实现]() 此书告诉您如何实现一个操作系统，比学校里告诉您的更多，更好理解。当年Linus就是看这本书，编写的Linux。
	
	1. [GeekOS](http://geekos.sourceforge.net/) The goal of GeekOS is to be a tool for learning about operating system kernels.  As of version 0.2.0, it comes with a set of projects suitable for use in an undergraduate operating systems course, or for self-directed learning.  GeekOS has been used in courses at a number of colleges and universities.
	
	1. [操作系统学习笔记](https://blog.csdn.net/longronglin/article/category/536556)
	1. 深入理解计算机系统
	1. Orange‘s一个操作系统的实现
	1. 30天自制操作系统

1. ### 编译原理
	1. [编译原理]() 编译原理的水平与程序员水平正相关，光会写程序，不能理解编译原理，是很难写出高水平程序的。龙书非常出名，谁学谁知道。工作后您可能会使用各种各样的语言，他们是如何工作和执行的，编译原理是不可或缺的重要一环。
	2. 自制编程语言
	3. 编译原理及实现
	4. [文章][编译原理学习基本步骤](http://blog.csdn.net/longronglin/article/details/5920957)
	5. [文章][编译原理解析](http://blog.csdn.net/longronglin/article/details/1109436) 如果把我上面的内容学好，可以说编译原理掌握的不错了。特别是我的内容是参考上面的清华大学孙悦红老师的课本做的，还得到了其支持。

1. ### 数据库
	1. 关系数据库
		1. [Transact-SQL权威指南]() 经典。
		2. [Head First SQL]()
		3. [Teach Yourself SQL in 21 Days]()
		4. [SQL必知必会(第3版)]()
		2. [SQL教程（杨中科）](http://study.163.com/course/introduction/215012.htm#/courseDetail) 使用微软SQL Server讲解的。
		3. [MySQL数据库（高洛峰）](http://study.163.com/course/introduction/247003.htm#/courseDetail)
		4. [尚学堂马士兵Oracle视频教程](http://study.163.com/course/introduction/344012.htm#/courseDetail)
	
		1. Codd 12 Rules
			1. Rule 0: The Foundation rule:
For any system that is advertised as, or claimed to be, a relational data base management system, that system must be able to manage data bases entirely through its relational capabilities.
			1. Rule 1: The information rule:
All information in a relational data base is represented explicitly at the logical level and in exactly one way — by values in tables.
			1. Rule 2: The guaranteed access rule:
Each and every data (atomic value) in a relational data base is guaranteed to be logically accessible by resorting to a combination of table name, primary key value and column name.
			1. Rule 3: Systematic treatment of null values:
Null values (distinct from the empty character string or a string of blank characters and distinct from zero or any other number) are supported in fully relational DBMS for representing missing information and inapplicable information in a systematic way, independent of data type.
			1. Rule 4: Dynamic online catalog based on the relational model:
The data base description is represented at the logical level in the same way as ordinary data, so that authorized users can apply the same relational language to its interrogation as they apply to the regular data.
			1. Rule 5: The comprehensive data sublanguage rule:
A relational system may support several languages and various modes of terminal use (for example, the fill-in-the-blanks mode). However, there must be at least one language whose statements are expressible, per some well-defined syntax, as character strings and that is comprehensive in supporting all of the following items:
				1. Data definition.
				1. View definition.
				1. Data manipulation (interactive and by program).
				1. Integrity constraints.
				1. Authorization.
				1. Transaction boundaries (begin, commit and rollback).
			1. Rule 6: The view updating rule:
All views that are theoretically updatable are also updatable by the system.
			1. Rule 7: High-level insert, update, and delete:
The capability of handling a base relation or a derived relation as a single operand applies not only to the retrieval of data but also to the insertion, update and deletion of data.
			1. Rule 8: Physical data independence:
Application programs and terminal activities remain logically unimpaired whenever any changes are made in either storage representations or access methods.
			1. Rule 9: Logical data independence:
Application programs and terminal activities remain logically unimpaired when information-preserving changes of any kind that theoretically permit unimpairment are made to the base tables.
			1. Rule 10: Integrity independence:
Integrity constraints specific to a particular relational data base must be definable in the relational data sublanguage and storable in the catalog, not in the application programs.
			1. Rule 11: Distribution independence:
A relational DBMS has distribution independence.
			1. Rule 12: The nonsubversion rule:
If a relational system has a low-level (single-record-at-a-time) language, that low level cannot be used to subvert or bypass the integrity rules and constraints expressed in the higher level relational language (multiple-records-at-a-time).
	
	1. CAP理论
		1. 又称CAP定理，指的是在一个分布式系统中， Consistency（一致性）、 Availability（可用性）、Partition tolerance（分区容错性），三者不可得兼。	
			1. 理论首先把分布式系统中的三个特性进行了如下归纳：
				1. 一致性（C）：在分布式系统中的所有数据备份，在同一时刻是否同样的值。（等同于所有节点访问同一份最新的数据副本）
				1. 可用性（A）：在集群中一部分节点故障后，集群整体是否还能响应客户端的读写请求。（对数据更新具备高可用性）
				1. 分区容错性（P）：以实际效果而言，分区相当于对通信的时限要求。系统如果不能在时限内达成数据一致性，就意味着发生了分区的情况，必须就当前操作在C和A之间做出选择。

	1. NOSQL
		1. MongoDB
			1. MongoDB权威指南
		2. HBase
			1. HBase权威指南
		3. Cassandra
			1. Cassandra权威指南

1. ### 计算机网络
	1. [计算机网络自顶向下方法]()
	1. [TCP/IP详解卷1:协议]()
	1. [图解TCP/IP]()
	1. [图解HTTP]
	1. [视频][计算机网络技术与应用](http://study.163.com/course/courseMain.htm?courseId=1255007)
	2. [文章][从输入 URL 到页面加载完成的过程中都发生了什么事情？](http://fex.baidu.com/blog/2014/05/what-happen)
	3. [考证]CCNA学习指南

1. ### 软件工程
	1. 软件工程
	1. 代码大全
	1. [图书] 人月神话
	1. [图书] 敏捷软件开发(原则模式与实践)
	1. [图书] 重构
	1. [图书] 软件测试
	
1. ### CPU
	1. [CISC模型微处理器设计（VHDL实现）](https://blog.csdn.net/longronglin/article/details/1055388) 
		
1. ### 汇编语言
	1. [汇编语言](http://product.dangdang.com/25178843.html) 王爽的这版，我觉得入门是最好的。写的浅显易懂，更深入的需要看别的图书。
	1. Intel Architecture Software Developer's Manual Volume1: Basic Architecture
	2. Intel Architecture Software Developer's Manual Volume2:Instructions Set Reference 
	3. Intel Architecture Software Developer's Manual Volume3:System Programming Guide

1. ### 数据仓库

	1. ETL
		1. [Talend](https://www.talend.com/resources/what-is-etl/)

	1. Teradata
	1. DataStage

1. ### 数据挖掘及人工智能
	
## Java及JavaEE

1. ### Java

	1. [java.oracle.com](http://java.oracle.com) Java官方地址，Jaysva开发工具、文档、bug等信息权威发布。

	1. [Java 规范](https://docs.oracle.com/javase/specs) Java Language and Virtual Machine Specifications. 
	 
	1. [Javaee-spec](https://javaee.github.io/javaee-spec) Java EE Platform Specification.
	 
	1. [OpenJDK](http://openjdk.java.net) 开源JDK，JDK的编译是Java程序员需要了解的技能。
 
	1. [Linux](https://www.linux.org/) Java虽然是跨平台的，但是和Linux是完美搭配，做服务器端体会更深。
	
	1. 图书
		1. [图书] Core java 
		1. [图书] Effective java
		1. [图书] Java规范
		1. [图书] Java并发编程

	1. 面向对象软件设计
		1. [图书]Java编程思想 此书和《C++编程思想》是同一作者，现有C++版，后有Java，写的非常适合入门学习。
		1. [图书]设计模式 可复用面向对象软件的基础
		1. [图书]Java与模式
		1. [图书]Head First设计模式
		1. [图书]面向对象程序分析和设计
		1. [视频]设计模式有个微软的李建中视频，讲的非常到位，可以搜索看看。就是代码是C#的，但是思想是一样的，模式和语言无关。

1. #### Linux
	1. [图书]鸟哥的Linux私房菜:基础学习篇
	
	1. [图书]Linux命令行大全 从命令行学起，也是学习Linux的一个不错路径。
	
	1. VI
		1. $输入$vimtutor en可以进入自带教程，好好学习，天天向上。
		
		1. [http://www.linfo.org/vi/index.html](http://www.linfo.org/vi/index.html)
		
		1. Emacs和VIM：神的编辑器和编辑器之神。
	1. Shell
		
		1. [图书]Linux命令行与shell脚本编程大全
		
		1. [图书]Shell脚本学习指南
		
		1. [视频][Linux 入门基础（苏勇）](http://study.163.com/course/introduction/232007.htm)
		
		1. [视频][李明老师讲Linux（李明）](http://study.163.com/course/courseMain.htm)
		
		1. [视频][Linux视频教程（传智播客的韩顺平）](http://study.163.com/course/introduction/215011.htm)
		
		1. [视频][计算机专业导论](http://study.163.com/curricula/cs.htm)

		1. [认证][LPI Linux认证权威指南]()
		
1. #### 其他语言
	1. Python
	1. JavaScript
	1. Android
	1. iOS
	1. PHP
	1. 其他
		1. 编码的奥秘

1. 产品
	1. Axure
	
1. #### 项目管理
	1. PMP
	2. 敏捷开发
	3. ISO认证
	
1. #### 其他
	1. 	SEO
	2. 点石成金
	3. 用户体验

1. 图灵奖
	1. 图灵：计算机之父。
	1. 历届图灵奖得主及贡献


1. ### HTML & CSS
	1. [http://www.w3.org/TR/2014/REC-html5-20141028](http://www.w3.org/TR/2014/REC-html5-20141028) HTML官方文档，仔细研究就可以算入门。
	1. [CSS: Cascading Style Sheets](https://www.w3.org/TR/2011/REC-CSS2-20110607) CSS官方文档，仔细研究就可以算入门。
	1. [图书][HTTP权威指南]()
	1. [图书][HTML & CSS 设计与构建网站]()
	1. [图书][JavaScript & jQuery交互式Web前端开发]()
	1. [图书][HTML5权威指南]()
	1. [文章][https://developer.mozilla.org/zh-CN/docs/Web](https://developer.mozilla.org/zh-CN/docs/Web)
	1. [视频][8小时学会HTML网页开发](http://study.163.com/course/courseMain.htm?courseId=432008)
	1. [视频][8小时学会HTML网页开发](http://study.163.com/course/courseMain.htm?courseId=432008)
	1. [视频][翁恺 HTML5入门](http://study.163.com/course/introduction/171001.htm#/courseDetail)
	1. [视频][麦子学院 HTML5+CSS3快速入门](http://study.163.com/course/courseMain.htm?courseId=999036)
	1. [视频][妙味 HTML5前端开发实战1](http://study.163.com/course/courseMain.htm?courseId=717031#/courseDetail)
	1. [视频][妙味 HTML5前端开发实战2](http://study.163.com/course/introduction/717017.htm#/courseDetail)
	
	1. [图书][CSS权威指南]() 必读
	1. [图书][CSS揭秘]() 书的序是《CSS权威指南》的作者写的。
	1. [图书][CSS禅意花园]() 是通过一个html，不同的css显示不同效果的实例，非常值得学习。
	1. [文章][CSS的核心之一：盒子模型]()
	1. [文章][CSS的核心之一：position](http://www.barelyfitz.com/screencast/html-training/css/positioning)
	
	1. [源码][CSS ZEN GARDEN](http://www.csszengarden.com)
	1. [Bootstrap](https://getbootstrap.com/) Bootstrap is an open source toolkit for developing with HTML, CSS, and JS.

	1. [EasyUI](https://www.jeasyui.com/) EasyUI for jQuery provides easy to use components for web developers, which is built on the popular jQuery core and HTML5. These make your applications suitable for today's web. 

1. ### JavaScript
	1. JavaScript是web开发必须学习的，ECMAScript是其规则来源。
		1. Developed by Brendan Eich of Netscape, under the name of  Mocha, then LiveScript, and finally JavaScript. 
		1. 1995 - JavaScript 1.0 in Netscape Navigator 2.0 (Dec)
		1. 1996 - JavaScript 1.1 in Netscape Navigator 3.0 (Aug), JScript 1.0 in Internet Explorer 3.0 (Aug). JavaScript had no standards governing its syntax or features. 
		1. 1997 - ECMAScript 1.0 (ECMA-262, based on JavaScript 1.1) (Jun), JavaScript 1.2 in Netscape Navigator 4.0 (Jun), JScript 3.0 in Internet Explorer 4.0 (Sep) 
		1. 1998 - JavaScript 1.3 in Netscape 4.5 (ECMAScript 1.0) (Oct) 
		1. 2005 - JavaScript 1.6 in Firefox 1.5 
		1. …...

	1. [图书]
	2. 《O’Reilly精品图书系列:JavaScript权威指南 》
《JavaScript高级程序设计 》
《JavaScript DOM编程艺术 》
《JavaScript语言精粹 》
《编写可维护的JavaScript 》
《高性能JavaScript  》
《深入理解JavaScript 》
《JavaScript函数式编程 》：函数是JavaScript的一等公民。
《JavaScript设计模式  》
《JavaScript模式 》
《JavaScript经典实例 》
《数据结构与算法JavaScript描述 》：用来打基础。
《编写可测试的JavaScript代码 》
jQuery基础教程
精通jQuery

	1. [jQuery](https://jquery.com/) jQuery is a fast, small, and feature-rich JavaScript library.

	1. [AngularJS](https://angularjs.org/) AngularJS is a JavaScript framework. 
	 
	1. [视频][李炎恢JavaScript教程 第一季](http://study.163.com/course/introduction/252008.htm)
	1. [视频][JavaScript（翁恺）](http://study.163.com/course/introduction/195001.htm)
	1. [视频][JavaScript面试题系列](http://study.163.com/course/introduction/742021.htm)
	
1. DashBoard
	1. [RDash](https://github.com/rdash/rdash-angular) AngularJS implementation of the RDash admin dashboard theme.
		
1. ### XML
	Extensible Markup Language
	http://www.w3school.com.cn/xml/
   XML入门经典
   无废话XML

1. ### JavaEE
	1. Servlet
		A servlet is a Java technology based web component, managed by a container, that generates dynamic content. Like other Java-based components, servlets are platform independent Java classes that are compiled to platform neutral bytecode that can be loaded dynamically into and run by a Java enabled web server. Containers, some- times called servlet engines, are web server extensions that provide servlet function- ality. Servlets interact with web clients via a request/response paradigm implemented by the servlet container. 
		The servlet container is a part of a web server or application server that provides the network services over which requests and responses are sent, decodes MIME based requests, and formats MIME based responses. A servlet container also contains and manages servlets through their lifecycle. 

		1. [图书][Head First Servlets & Jsp]()
		1. [图书][JSP设计]()
		1. [图书][Java Servlet & JSP Cookbook]()
		1. [文章][Servlet 工作原理解析](http://www.ibm.com/developerworks/cn/java/j-lo-servlet)
		1. [视频][Servlet Java  Web 编程（郭宏志）](http://study.163.com/course/introduction/648001.htms)
	2. Jsp
		JSP: JavaServer Pages is a technology for developing web pages that include dynamic content. Unlike a plain HTML page, which contains static content that always remains the same, a JSP page can change its content based on any number of variable items, including the identity of the user, the user's browser type, information provided by the user, and selections made by the user.
		JSP is a specification, not a product. 
		
		1. [视频][尚学堂Jsp快速入门（高淇）](http://study.163.com/course/courseMain.htm?courseId=1067001)
	3. Tomcat
       Tomcat权威指南
       深入剖析Tomcat（How Tomcat Works）

	4. JavaEE
		1. 疯狂软件教育标准教材·轻量级Java EE企业应用实战(第4版):Struts 2+Spring 4+Hibernate整合开发(附光盘)
		2. [][JavaEE视频教程（郭宏志）](http://study.163.com/course/courseMain.htm?courseId=320027)
		2. [][30天轻松掌握JavaWeb视频（方立勋）](http://study.163.com/course/courseMain.htm?courseId=214022)
		2. 《J2EE Development without EJB》
《J2EE设计开发编程指南》
《IBM WebSphere Studio J2EE应用开发》可以看看。
《精通Spring》
JMS／JNDI／JTA／JACP／JAX-RPC／JCA／JMX／JACC／JavaMail／JAF／JTA／JTS 


1. ### 开发工具(Tools)
	1. 版本管理
		1. [git](https://git-scm.com) Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
			
		1. [gitlab](https://about.gitlab.com/) GitLab is the leading integrated product for modern software development. Connecting issue management, version control, code review, CI, CD, and monitoring.
	
		1. [bitbucket](https://bitbucket.org/product) 类似github的功能，不过是可以闭源。(Bitbucket is more than just Git code management. Bitbucket gives teams one place to plan projects, collaborate on code, test and deploy.)

		1. [mercurial](https://www.mercurial-scm.org) 源码控制管理工具。(Mercurial is a free, distributed source control management tool.)
	
	1. IDE
		1. [eclipse](https://www.eclipse.org) The Platform for Open Innovation and Collaboration. 我们主要使用其Java的开发工具。
	
		1. [intellij](https://www.jetbrains.com/idea) 一款IDE工具，个人感觉比Eclipse要好，推荐使用。

		1. [netbeans](https://netbeans.org) 不推荐使用。Quickly and easily develop desktop, mobile and web applications with Java, JavaScript, HTML5, PHP, C/C++ and more.

		1. Android Studio
		
			1. 编码规范
				1. [Google Java 格式化](https://github.com/google/google-java-format) 推荐使用，插件比较多，各IDE支持好，程序员喜欢。Reformats Java source code to comply with Google Java Style.
				2. [Alibaba Java 编码规范](https://github.com/alibaba/Alibaba-Java-Coding-Guidelines) 
		   2. checkstyle
		
	1. 构建工具
		1. [maven](http://maven.apache.org) Apache Maven is a software project management and comprehension tool.
	
		1. [ant](http://ant.apache.org) Apache Ant is a Java library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other.
		
		1. [gradle](https://gradle.org/) Build Tool.
		
	1. web容器
		1. [Tomcat](https://tomcat.apache.org/) The Apache Tomcat® software is an open source implementation of the Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket technologies. 
		
		1. [Jetty](https://www.eclipse.org/jetty/) Eclipse Jetty provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations. These components are open source and available for commercial use and distribution.
	
	1. 私服
		1. [nexus](https://www.sonatype.com/nexus-repository-sonatype) Maven私服。

	1. 持续集成
		1. [jenkins](https://jenkins.io/) The leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project.
	
		1. [teamcity](https://www.jetbrains.com/teamcity/) Powerful Continuous Integration out of the box.

	1. IDE插件
		1. [findbugs](http://findbugs.sourceforge.net) 一般用在IDE插件，帮助发现bug。(This is the web page for FindBugs, a program which uses static analysis to look for bugs in Java code. )

		1. checkstyle
		1. test

	1. 需求管理
		1. [redmine](http://www.redmine.org/) Redmine is a flexible project management web application. 
			
	1. Bug管理
		1. [Bugzilla](https://www.bugzilla.org/) Bugzilla is server software designed to help you manage software development.
		
		1. [Jira](https://www.atlassian.com/software/jira) 
		
	1. 其他
		1. [Postman](https://www.getpostman.com/) API访问工具。(Postman Makes API Development Simple.)

	1. [wiki] 
	
	1. [shadowsocks]

	1. confluence
	
	1. cloujure
	
	1. sonar
		1. sonarcube
	
1. #### Java基础(Java Basic)

	1. [Java并发](https://github.com/xianglesong/learning-javas/blob/master/basic/Java并发.md)  Java并发包的使用是中高级程序员必须掌握的技能之一。


1. ### Java 库和框架等介绍

	1. Java常用库
	
		1. [Spring](https://spring.io)
		
		1. [MyBatis](http://www.mybatis.org/mybatis-3)
		 
		1. [Hibernate](http://hibernate.org)
		 
		1. [Struts](https://struts.apache.org)
		
		1. [SpringCloud](http://projects.spring.io/spring-cloud)
			
		1. [Guava](https://github.com/google/guava)  Google core libraries for Java.

	1. 日志
		1. Log4j
		2. SLF4j
		3. Logback
		4. Common-Log
	
	1. 缓存
		1. [EHCache](http://www.ehcache.org/)
		2. OSCache
	
	1. IOC
		1. [guice](https://github.com/google/guice) Guice (pronounced 'juice') is a lightweight dependency injection framework for Java 6 and above, brought to you by Google.
		
	1. AOP
	
	1. 定时调度
		1. [Quartz](http://www.quartz-scheduler.org/)  Java任务调度库。(open source job scheduling library that can be integrated within virtually any Java application - from the smallest stand-alone application to the largest e-commerce system. Quartz can be used to create simple or complex schedules for executing tens, hundreds, or even tens-of-thousands of jobs; jobs whose tasks are defined as standard Java components that may execute virtually anything you may program them to do. The Quartz Scheduler includes many enterprise-class features, such as support for JTA transactions and clustering.)
		
		1. [Elastic-job](https://github.com/xianglesong/learning-javas/blob/master/platform/Elastic-job.md) 当当网出品的这款产品也不错，可以进行分布式分片调度。开箱即用，很方便。(A distributed scheduled job framework, based on Quartz and Zookeeper.)
		
	 
	1. 内存数据库
		1. [MapDB](http://www.mapdb.org/)  MapDB provides Java Maps, Sets, Lists, Queues and other collections backed by off-heap or on-disk storage. It is a hybrid between java collection framework and embedded database engine.
		
	1. 数据库连接池
		1. [Druid](https://github.com/alibaba/druid)  为监控而生的数据库连接池！
		
		1. [DBCP](https://commons.apache.org/proper/commons-dbcp/)
		
	1. Http工具
		1. [HttpClient](https://hc.apache.org/httpcomponents-client-ga/)
		
		1. [okhttp](http://square.github.io/okhttp/) An HTTP+HTTP/2 client for Android and Java applications.
		
	1. 时间工具
		1. [Joda](http://www.joda.org/joda-time/)  Joda-Time provides a quality replacement for the Java date and time classes.
		
	1. IO高性能库
		1. [Netty](https://github.com/xianglesong/learning-javas/blob/master/lib/Netty.md)   Netty算是Java的高级库了，掌握他，IO高级没问题。
		(Netty is an asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.)
	
	1. 内存检测
		1. [Leakcanary](https://github.com/square/leakcanary)  A memory leak detection library for Android and Java.
		
	1. 分布式数据库
		1. [Sharding-jdbc](https://github.com/xianglesong/learning-javas/blob/master/lib/Sharding-jdbc.md)  分库分表的轻量级解决方法之一。
		(Distributed database middleware.)
		
	1. RPC工具
		1. [Thrift](https://github.com/xianglesong/learning-javas/blob/master/lib/Thrift.md)  RPC实现有多种方式，Thrift算是其中不错的框架之一。
		(The Apache Thrift software framework, for scalable cross-language services development, combines a software stack with a code generation engine to build services that work efficiently and seamlessly between C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C#, Cocoa, JavaScript, Node.js, Smalltalk, OCaml and Delphi and other languages.)
		
		1. [Dubbo](https://github.com/xianglesong/learning-javas/blob/master/framework/Dubbo.md) 
		Dubbo作为一个分布式RPC框架，对于Java程序员来说，还是有必要学习一下的。(Apache Dubbo™ (incubating) is a high-performance, java based open source RPC framework.)
		
	1. 统一配置中心
		1. [Apollo](https://github.com/xianglesong/learning-javas/blob/master/platform/Apollo.md)  这款配置中心的功能不错，推荐一下。
		(Apollo阿波罗是携程框架部门研发的分布式配置中心，能够集中化管理应用不同环境、不同集群的配置，配置修改后能够实时推送到应用端，并且具备规范的权限、流程治理等特性，适用于微服务配置管理场景。)
		
	1. 网络爬虫
		1. [Nutch](http://nutch.apache.org/)  分布式爬虫。(Highly extensible, highly scalable Web crawler.)
		
		1. [Heritrix](https://github.com/internetarchive/heritrix3)  一款网络爬虫。(Heritrix is the Internet Archive's open-source, extensible, web-scale, archival-quality web crawler project.)
		
		1. [Jsoup](https://jsoup.org/)  jsoup is a Java library for working with real-world HTML. It provides a very convenient API for extracting and manipulating data, using the best of DOM, CSS, and jquery-like methods.

	1. 搜索引擎
		1. [Lucene](http://lucene.apache.org/) 建立索引和查询库。(The goal of Apache Lucene and Solr is to provide world class search capabilities.)
		
		1. [Solr](http://lucene.apache.org/solr) 企业级搜索平台基于Lucene的封装。(Solr is the popular, blazing-fast, open source enterprise search platform built on Apache Lucene™.)
		
		1. [ElasticSearch](https://github.com/xianglesong/learning-javas/blob/master/platform/ElasticSearch.md) 分布式搜索利器，广泛使用。
		(Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases. As the heart of the Elastic Stack, it centrally stores your data so you can discover the expected and uncover the unexpected.)
		
		1. [elasticsearch-analysis-ik](https://github.com/medcl/elasticsearch-analysis-ik) The IK Analysis plugin integrates Lucene IK analyzer into elasticsearch, support customized dictionary.
		
		1. [jpinyin](https://github.com/stuxuhai/jpinyin) JPinyin是一个汉字转拼音的Java开源类库。

		1. [pinyin4j](https://github.com/belerweb/pinyin4j) A copy of http://sourceforge.net/projects/pinyin4j, then deploy it to maven central repository.
		
	1. 分布式存储和计算
		1. [Hadoop](https://github.com/xianglesong/learning-javas/blob/master/platform/Hadoop.md) 分布式文件存储和技术框架，云计算的利器。(The
		Apache™ Hadoop® project develops open-source software for reliable, scalable, distributed computing.)
		
		1. hive
		
	
	1. 分布式协调器
		1. [Zookeeper](https://github.com/xianglesong/learning-javas/blob/master/platform/Zookeeper.md) Zookeeper提供分布式同步功能，在今天的分布式系统中有广泛使用。(A high-performance coordination service for distributed applications.)
		
	1. 分布式数据库
		1. [HBase](http://hbase.apache.org/) 建立在Hadoop上的分布式数据库。(Apache HBase™ is the Hadoop database, a distributed, scalable, big data store.)
		
		1. [Cassandra](http://cassandra.apache.org/) 分布式数据库(The Apache Cassandra database is the right choice when you need scalability and high availability without compromising performance.)
	
	1. 工作流调度
		1. [Oozie](http://oozie.apache.org/) Hadoop工作流调度工具。(Apache Oozie Workflow Scheduler for Hadoop.)
		
	1. 性能测试
		1. [JMeter](http://jmeter.apache.org/) The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance. It was originally designed for testing Web Applications but has since expanded to other test functions.

   1. 二维码
	    1. [ZXing](https://github.com/zxing/zxing) ZXing ("Zebra Crossing") barcode scanning library for Java, Android.
	    
	1. 图像处理
	    1. [ImageMagick](https://www.imagemagick.org/script/index.php) Use ImageMagick® to create, edit, compose, or convert bitmap images.
	
	1. [Neo4j](https://neo4j.com/) The graph database platform.
	
	1. 分布式跟踪
		1. [PinPoint](https://github.com/naver/pinpoint) Pinpoint is an open source APM (Application Performance Management) tool for large-scale distributed systems written in Java. http://naver.github.io/pinpoint
		
		1. [CAT](https://github.com/dianping/cat) Central Application Tracking.
		
		1. [Zipkin](https://github.com/openzipkin/zipkin) Zipkin is a distributed tracing system http://zipkin.io
	
	1. 分布式存储
	    1. [Ceph](https://ceph.com/)

	1. 数据挖掘
	    1. [Weka](https://www.cs.waikato.ac.nz/ml/weka/) Weka is a collection of machine learning algorithms for data mining tasks. 
	    
	    1. [Mahout](http://mahout.apache.org/) For Creating Scalable Performant Machine Learning Applications.
	    
	    1. [Spark](https://spark.apache.org/) A unified analytics engine for large-scale data processing.
	    
    1. 深度学习
	    1. [DeepLearning](https://github.com/yusugomori/DeepLearning) Deep Learning (Python, C, C++, Java, Scala, Go) http://yusugomori.com
	 
	 1. Kylin
	 
	 
	 1. SpringCloud
    boot
    eureka
    zuul
    zipkin
    config
    hystrix
    ...

	1. velocity
	2. freemark
	3. zookeeper（curator）


1. ### 其他工具

	1. 数据库
		1. MySQL
		2. Teradata
	1. 缓存
		1. Redis
		1. MemCache
	1. 消息
		1. RabbitMQ
		1. Kafka
	1. 代理、反向代理
		1. Nginx
		1. HAProxy
	1. 缓存
		1. Varnish
		1. Sequid
	1. 虚拟机
		1. [VirtualBox](https://www.virtualbox.org)
		
		1. [VMware](https://www.vmware.com) 
	
	1. Docker
	
	1. k8s
	1. mesos
	
	1. 序列化、反序列化
		1. [Protobuf](https://github.com/google/protobuf) Protocol Buffers - Google's data interchange format https://developers.google.com/protocol-buffers .

	1. MQTT
		1. mosquito
		
	1. storm
	1. kafka
	
1. ### GitHub

	1. [https://github.com/akullpp/awesome-java](https://github.com/akullpp/awesome-java)  A curated list of awesome frameworks, libraries and software for the Java programming language.
	
	1. [https://github.com/jobbole/awesome-java-cn](https://github.com/jobbole/awesome-java-cn)  Java资源大全中文版。
	 
	1. [https://github.com/Vedenin/useful-java-links](https://github.com/Vedenin/useful-java-links)  A list of useful Java frameworks, libraries, software and hello worlds examples.
	
	1. [https://github.com/Blankj/awesome-java-leetcode](https://github.com/Blankj/awesome-java-leetcode)  LeetCode of algorithms with java solution(updating).
	
	1. [https://github.com/TheAlgorithms/Java](https://github.com/TheAlgorithms/Java)  All Algorithms implemented in Java.
	
	1. [https://github.com/DuGuQiuBai/Java](https://github.com/DuGuQiuBai/Java)  27天成为Java大神。
	
	1. [https://github.com/iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns)  Design patterns implemented in Java [http://java-design-patterns.com](http://java-design-patterns.com).
	
	1. [spring-boot](https://github.com/spring-projects/spring-boot)
	
	1. [dubbo](https://github.com/apache/incubator-dubbo)  Apache Dubbo (incubating) is a high-performance, java based, open source RPC framework.
	
	1. [interviews](https://github.com/kdn251/interviews)  Everything you need to know to get the job.




1. ### 自动化测试及运维

	1. [Selium](https://www.seleniumhq.org)  A browser automation framework and ecosystem. 
	
	1. [Azkaban](https://azkaban.github.io/) Open-source Workflow Manager.
	
	1. CDN
		1. 其实是域名劫持技术黑科技的好应用。 
		1. [网宿科技](http://www.wangsu.com)
		1. [七牛云](https://www.qiniu.com)

	1. [JumpServer](http://www.jumpserver.org/) 是全球首款完全开源的堡垒机,使用GNU GPL v2.0开源协议,是符合 4A 的专业运维安全审计系统。
	
1. ### 网络安全

1. ### 云平台
	1. [阿里云](https://www.aliyun.com) 我个人也购买过，我以前的公司沪江购买过。
	
	1. [腾讯云](https://cloud.tencent.com)
	
	1. [青云](https://www.qingcloud.com) 我以前的公司微鲸印象中，使用的是这个。减去了自己搭建服务器和运维的很多麻烦，还是相当不错的。
	
	1. [AWS](https://aws.amazon.com)
	
	1. [搬瓦工](http://banwagong.cn)
	
1. ### 期刊杂志

	1. [电脑报](http://www.icpcw.com) 
	
	1. [ACM](https://www.acm.org/)

	1. [IEEE](https://www.ieee.org/)

1. ### 论文(Paper)
	1. 搜索下载
		1. [万方数据](http://www.wanfangdata.com.cn/index.html) 整合数亿条全球优质学术资源，集成期刊、学位、会议、科技报告、专利、视频等十余种资源类型，覆盖各研究层次，感知用户学术背景，智慧你的搜索。万方智搜致力于帮助用户精准发现、获取与沉淀学术精华。万方数据愿与合作伙伴共同打造知识服务的基石、共建学术生态。
		
		1. [中国知网](http://cnki.net) 中国知网知识发现网络平台—面向海内外读者提供中国学术文献、外文文献、学位论文、报纸、会议、年鉴、工具书等。
		
		1. [维普](http://cqvip.com)

	1. 经典论文
		1. AQS
		1. HDFS
		1. MapReduce
		1. Zookeeper
		1. CAP

1. ### 会议(Meeting)

1. ### 文档(Documents)
	1. 缓存
		1. 缓存那些事 https://tech.meituan.com/cache_about.html

1. ### 标准规范

	1. [HTML](https://www.w3.org/TR/html)
	
	1. [CSS](https://www.w3.org/TR/CSS/)
	
	1. [Hypertext Transfer Protocol -- HTTP/1.1](https://www.w3.org/Protocols/rfc2616/rfc2616.html)

1. ### API

	1. [Google API Design Guide](https://cloud.google.com/apis/design)

1. ### RESTful API

	1. [RESTful API 论文](http://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)

1. ### Mac工具

   1. Alfred
   2. Foxmail
   3. wuderlist
   4. sougou
   5. evernote
   6. xmind
   7. filezilla
   8. gns3
   9. chromeiterm
   10. luyten
   11. wireshark
   12. cleanmymac
   13. resucetime
   14. jetbeans 一套
   15. staruml
   16. skype
   17. sketch
   18. sequel pro
   19. parall client

	1. [Dash](https://kapeli.com/dash)  快速访问API。(Dash gives your Mac instant offline access to 200+ API documentation sets.)
	
	1. [Redis Desktop Manager](https://redisdesktop.com/)  访问Redis的工具。(Redis Desktop Manager (aka RDM) — is a fast open source Redis database management application for Windows, Linux and MacOS.)
	
	1. [Robo 3T](https://robomongo.org/)  访问MongoDB的工具。(Robo 3T (formerly Robomongo) is the free lightweight GUI for MongoDB enthusiasts.)
	
	1. [MongoHub](https://github.com/jeromelebel/MongoHub-Mac)  访问MongoDB的工具。(Mac Native Mongodb Client.)
	
	1. [SourceTree](https://www.sourcetreeapp.com)  版本控制管理工具。(The friendly GUI for Mercurial and Git on your Mac.)
	
	1. [SnailSVN]  访问svn工具。
	
	1. [MacDown] MarkDown编写工具。
	
	1. [Sublime Text](http://www.sublimetext.com)  免费的文本编辑工具。(A sophisticated text editor for code, markup and prose.)
	
	1. [iterm2](https://www.iterm2.com/index.html) 替换官方的terminal。(iTerm2 is a replacement for Terminal and the successor to iTerm.)

	1. [LaTeX](https://www.latex-project.org) LaTeX is a high-quality typesetting system.

1. ### 考试认证

	1. OCJP Oracle公司的Java工程师认证。通过该考试表明较好的掌握Java基础知识。
	
	1. [PMP](https://www.pmi.org/) 美国项目管理工程师协会认证，全球认可，做项目管理的一定要学习。和国内软考的信息系统项目管理师考试雷同，考个国内的也可以，国外贵，单易考。
	
	1. Linux 有红帽认证等。
	
	1. Database 有Oracle和DB2等认证。
	
	1. [软考](http://www.ruankao.org.cn/)
		1. 考试介绍 [http://www.ruankao.org.cn/platform](http://www.ruankao.org.cn/platform)
			1. 软件设计师  个人觉得大三学生可以开始考这个，工作的就更容易了。
			
			1. 信息系统项目管理师  这个偏管理的，主要是论文会卡人，容易的考个中级的系统集成项目管理工程师就可以，这个不考论文。

1. ### 图灵奖
	艾伦·麦席森·图灵（Alan Mathison Turing，1912年6月23日－1954年6月7日），英国数学家、逻辑学家，被称为计算机之父，人工智能之父。

	1. Ken Thompson(肯·汤普森) 1969年，Bell实验室的Ken Thompson 写了第一个版本的操作系统，这时，这个操作系统还没有名字，这个操作系统是用DEC PDP-7 小型机的汇编语言写成。1970年，Thompson的操作系统命名为 Unics，全称是Uniplexed Information and Computing Service 这是一个 “被阉割了的微型的 Multics”。 （后来，这个名字被神秘地改成了Unix）
	
	2. Dennis M.Ritchie(丹尼斯·里奇) 丹尼斯·里奇，C语言之父，UNIX之父。丹尼斯·里奇与肯·汤普逊两人发展了C语言，同时发展了Unix操作系统。在电脑工业史上占有重要的席位。
	
	3. Donald Knuth(高德纳) 《计算机程序设计的艺术》系列，开始于他念博士期间，计划出七卷，第一卷《基本算法》于1968年出版，第二卷《半数字化算法》于1969年出版，第三卷《排序与搜索》于1973年出版，第四卷《组合算法》尚在写作之中。《计算机程序设计的艺术》一书以其内容的丰富和深刻喻为经典，有人甚至称之为“计算机的圣经”，被译为俄、日、西、葡、匈牙利、罗马尼亚等多种文字在世界各国广泛流传，其发行量创造了计算机类图书的最高记录，直至20世纪80年代中期，都一直保持着月销售量每卷达2000册的势头，成为Addison-Wesley出版社成立以来销路最好的图书。我国也由苏运霖翻译并出版了《计算机程序设计艺术》一书。
	4. James Gosling（詹姆斯·高斯林 ）詹姆斯·高斯林 （James Gosling，1955年5月19日－，出生于加拿大），软件专家，Java编程语言的共同创始人之一，一般公认他为“Java之父”。
	5. Tim Berners-Lee（蒂姆·伯纳斯-李）昵称为蒂姆·伯纳斯-李（Tim Berners-Lee），英国计算机科学家。他是万维网的发明者，麻省理工教授。1989年12月，蒂姆为他的发明正式定名为World Wide Web，即我们熟悉的WWW；1991年5月WWW在 Internet上首次露面，立即引起轰动，获得了极大的成功被广泛推广应用。
	6. 佛瑞德·布鲁克斯（Frederick P. Brooks, Jr.）曾任万国商用机器公司（即IBM公司或国际商务用机器公司）系统部主任，主持开发过OS/360等大型计算机用的操作系统软体。
	7. 阿达·奥古斯塔，19世纪英国诗人拜伦的女儿，数学家。穿孔机程序创始人，建立了循环和子程序概念。为计算程序拟定“算法”，写作的第一份“程序设计流程图”，被珍视为“第一个给计算机写程序的人”。
	8. 冯·诺伊曼对世界上第一台电子计算机ENIAC(电子数字积分计算机)的设计提出过建议，1945年3月他在共同讨论的基础上起草ENIAC(电子离散变量自动计算机)设计报告初稿，这对后来计算机的设计有决定性的影响，特别是确定计算机的结构，采用存储程序以及二进制编码等，至今仍为电子计算机设计者所遵循。
	9. Linus Benedict Torvalds （林纳斯·本纳第克特·托瓦兹）Software is like sex: it's better when it's free.
	10. Richard Matthew Stallman（理查德·马修·斯托曼）（生于1953年），自由软件运动的精神领袖、GNU（GNU IS NOT UNIX）计划以及自由软件基金会（Free Software Foundation）的创立者、著名黑客。他的主要成就包括Emacs及后来的GNU Emacs，GNU C 编译器及GNU 调试器。 他所写作的GNU通用公共许可证（GNU GPL）是世上最广为采用的自由软件许可证，为copyleft观念开拓出一条崭新的道路。




1. ### 微信公众号
1. ### 推荐网站(WebSite)
	1. 源码学习
		1. [github](https://github.com) 全球最大的程序员交友网，也说全球最大的同性交友网站^-^。

		1. [maven仓库](https://mvnrepository.com) 方便查找库应用。
		
		1. [apache](http://apache.org) 很多著名的开源项目在里面，比如Tomcat Hadoop Maven等。
		
		1. [sourceforge](http://www.sourceforge.net) 很多开源库也放在这里，特别是没有github之前。
	
	1. Linux
		1. http://linuxcommand.org
		
	1. 规范
		1. [w3c](https://www.w3.org)
		
	1. 综合
		1. [csdn](http://www.csdn.net) 中国最大的程序员网站。
		
		1. [infoq](http://www.infoq.com) 架构师网站。
		
		1. [chinaunix](http://www.chinaunix.net) 中国最大的Linux/Unix技术社区网站

		1. [博客园](https://www.cnblogs.com) 博客园是一个面向开发者的知识分享社区。
	
	1. 资料
		1. [slideshare](https://www.slideshare.net)  技术ppt下载。
	
	1. 技术博客
		1. [阿里中间件团队博客](http://jm.taobao.org)
		
		1. [美团技术团队](https://tech.meituan.com)
		
		1. [网易乐得技术团队](http://tech.lede.com)

	1. 论坛
		1. [Lucene](http://lucene.472066.n3.nabble.com)
		
		1. [Solr](http://lucene.472066.n3.nabble.com)
		
	1. 视频
		1. [极客学院](http://www.jikexueyuan.com)
		
		1. [网易云课堂](http://study.163.com)
		
		1. [YouTube](http://youtube.com)
		
		1. 吴恩达视频

       1. 传智播客视频

	1. 翻译
		1. [Google翻译]()
		
		1. [有道](http://youdao.com/)
		
	1. 名人
		1. 李刚 我是买过[疯狂Android讲义](http://product.dangdang.com/23699102.html)，感觉挺适合新手入门的，推荐一下。
		
		1. 马士兵 我看过其Java视频，讲的不错，推荐一下。
		
	1. 其他
		1. [gnu](https://www.gnu.org/home.en.html)
		
		1. [stackoverflow.com](https://stackoverflow.com) 问答网。

		1. [在线JSON校验格式化工具bejson](http://www.bejson.com/)

1. ### 我的源码阅读、论文、项目及视频（仅供参考）
	1. 源码阅读(Source Reading)
	
		1. [JDK](http://java.oracle.com) Java自身的就是最好的阅读资料之一。
		
		1. [Log4j](http://logging.apache.org) 值得一读，Log4j作为一款Java日志基础库，使用非常广泛，推荐一读。
		
		1. [Spring](https://spring.io) 有点大，我是没读完。
			1. 推荐阅读一个[tiny-spring](https://github.com/code4craft/tiny-spring)。
		 
		1. [Struts](https://struts.apache.org) 我是用过类似的公司框架，没仔细阅读过，目前直接spring boot，意义不大了。
		
		1. [Hibernate](http://hibernate.org) 我是写过类似的框架，不过肯定没他好，有兴趣的阅读。
		
		1. [MyBatis](http://www.mybatis.org/mybatis-3) 类似Hibernate实现。
		
		1. [Lucene](http://lucene.apache.org) 也不错，对搜索引擎感兴趣的可以一读。
		
		1. [Hadoop](http://hadoop.apache.org) 对于想了解分布式存储和计算的人来说，推荐阅读。
		
		1. [HBase](http://hbase.apache.org) 对于了解NOSQL的也值得一读。
		
		1. [Tomcat](http://tomcat.apache.org) 我是理解其处理过程，没有完全看过。
		
		1. [ActiveMQ] (http://activemq.apache.org) 看过，后来也忘了。
		
		1. [Nutch] (http://nutch.apache.org) 研究过代码，学习Hadoop和搜索引擎的可以看看。
		
		1. [Netty] (https://netty.io) 看过DEMO，没仔细研究过。
	
		1. Linux(Minix) 我的终结结论就是一句话，就是一切都是逻辑。
		
	2. 论文
		1. [一种哈希表快速查找的改进方法]()
		
		2. [基于贝叶斯方法和信息指纹的博客评论过滤]()
		 
	3. 项目
		1. [github xianglesong](https://github.com/xianglesong)
		 
	4. 视频
		1. [网易云课堂课程](http://study.163.com/provider/825396/course.htm)

1. ### 特别推荐

	1. #### `享乐颂官方网站 ` [http://www.xianglesong.com](http://www.xianglesong.com)
	
		1. 学习是一种习惯。
		
		1. 我们的口号是  省时 省心 省力 省钱。
		
		1. 官方网站提供部分内容讲解，帮助快速学习掌握技术。
		
	1. #### `QQ群:` 557373922(申请加入，请告诉我从哪里看到的，谢谢！)
	   1. 联系 rulinma#qq.com 替换#为@

1. ### 参考文献

1. ### 贡献
	1. 欢迎大家Fork、Star和贡献。 


