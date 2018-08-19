# Java 宝典
### 一切都是逻辑。

### 十大名言：

* Talk is cheap, show me code.(知易行难) -- Linus Torvalds(Linux创始人)
* 源码面前了无秘密。-- 侯捷 《STL源码剖析》作者
* 不要重复发明轮子。-- Rod Johnson(Spring Framework创始人)
* 过早的优化是万恶之源。-- Donald Knuth(1974年图灵奖)
* 用户为中心。
* 没有银弹。-- Fred Brooks(1999年图灵奖)
* 从重构到模式。-- Joshua Kerievsky(本书荣获2005年《软件开发》杂志图书通用类的效率大奖)
* 当一头牛拉不动车时，很少有人去找一头更大更强壮的牛，而是找来更多的牛一起拉。 -- 《Hadoop权威指南》
* 一个字：拆。
* 256K is OK.(256K应该足够了。) -- Bill Gates

## 目录
1. [Java及JavaEE](#user-content-Java及JavaEE)
	1. [Java](#user-content-java)
	1. [HTML&CSS](#user-content-html--css)
	1. [JavaScript](#user-content-javascript)
	1. [XML](#user-content-xml)
	1. [JavaEE](#user-content-javaee)
	1. [开发工具](#user-content-开发工具)
	1. [Java库和框架及其他介绍](#user-content-java库和框架及其他介绍)
1. [Linux](#user-content-编程语言)
	1. [Linux命令](#user-content-linux命令)
	1. [Shell](#user-content-shell)
	1. [Vim](#user-content-vim)
	1. [Linux源码](#user-content-linux源码)
1. [计算机基础知识](#user-content-计算机基础知识)
	1. [编程语言](#user-content-编程语言)
	1. [数据结构和算法](#user-content-数据结构和算法)
	1. [操作系统](#user-content-操作系统)
	1. [编译原理](#user-content-编译原理)
	1. [数据库](#user-content-数据库)
	1. [计算机网络](#user-content-计算机网络)
	1. [软件工程](#user-content-软件工程)
	1. [CPU](#user-content-cpu)
	1. [汇编语言](#user-content-汇编语言)
	1. [数据仓库及数据挖掘](#user-content-数据仓库及数据挖掘)
	1. [机器学习及人工智能](#user-content-机器学习及人工智能)
	1. [图灵奖](#user-content-图灵奖)
1. [科学研究](#user-content-编程语言)
	1. [期刊杂志](#user-content-期刊杂志)
	2. [论文](#user-content-论文)
	3. [会议](#user-content-会议)
1. [综合](#user-content-综合)
	1. [考试认证](#user-content-考试认证)
	1. [自动化测试及运维](#user-content-自动化测试及运维)
	1. [网络安全](#user-content-网络安全)
	1. [云平台](#user-content-云平台)
	1. [精华文档](#user-content-精华文档)
	1. [标准规范](#user-content-标准规范)
	1. [API](#user-content-api)
	1. [RESTful API](#user-content-restful-api)
	1. [Mac工具](#user-content-mac工具)
	1. [第三方工具](#user-content-第三方工具)
	1. [推荐GitHub](#user-content-推荐github)
	1. [微信公众号](#user-content-微信公众号)
	1. [其他语言](#user-content-其他语言)
	1. [面试](#user-content-面试)
	1. [项目管理](#user-content-项目管理)
	1. [产品](#user-content-产品)
	1. [其他](#user-content-其他)
1. [关于我们](#user-content-关于我们)
	1. [我](#user-content-我)
	2. [感谢](#user-content-感谢)


## Java及JavaEE
1. ### Java
	1. [Java官网](http://java.oracle.com) Java官方地址，Jaysva开发工具、文档、bug等信息权威发布。
	1. [Java规范](https://docs.oracle.com/javase/specs) Java Language and Virtual Machine Specifications.(Java语言和虚拟机规范) 
	1. [Javaee-spec](https://javaee.github.io/javaee-spec) Java EE Platform Specification.(Java EE平台规范。)
	1. [OpenJDK](http://openjdk.java.net) 开源JDK，JDK的编译是Java程序员需要了解的技能。
	1. [Linux](https://www.linux.org/) Java虽然是跨平台的，但是和Linux是完美搭配，做服务器端体会更深。 
	1. [图书][Java核心技术 卷I：基础知识](http://product.dangdang.com/24035306.html) 
	1. [图书][Java核心技术卷II：高级特性](http://product.dangdang.com/25171892.html) 
	1. [图书][Java编程思想](http://product.dangdang.com/9317290.html) 此书和《C++编程思想》是同一作者，现有C++版，后有Java，写的非常适合入门学习。
	1. [图书][Effective Java中文版](http://product.dangdang.com/20459091.html)
	1. [图书][Java编程规范](http://product.dangdang.com/9187067.html) 此书个人强热推荐，Java之父编写。
	1. [图书][Java并发编程实战](http://product.dangdang.com/22606835.html)
	1. [图书][Java性能优化权威指南](http://product.dangdang.com/23421069.html)
	1. [图书][深入理解Java虚拟机：JVM高级特性与最佳实践](http://product.dangdang.com/23259731.html)
	1. [图书][Java并发](https://github.com/xianglesong/learning-javas/blob/master/basic/Java并发.md) Java并发包的使用是中高级程序员必须掌握的技能之一。
	1. [图书][Java网络编程](http://product.dangdang.com/23560594.html)
	1. [GitHub][Modern Java - A Guide to Java 8(现代Java - Java指南8)](https://github.com/winterbe/java8-tutorial)
	1. 面向对象软件设计
		1. [图书][设计模式 可复用面向对象软件的基础](http://product.dangdang.com/71052.html)
		1. [图书]Java与模式
		1. [图书][Head First设计模式](http://product.dangdang.com/20021171.html)
		1. [图书]面向对象程序分析和设计
		1. [视频]设计模式有个微软的李建中视频，讲的非常到位，可以搜索看看。就是代码是C#的，但是思想是一样的，模式和语言无关。
		1. [GitHub][Design patterns implemented in Java(Java实现的设计模式)](https://github.com/iluwatar/java-design-patterns)
		
1. ### HTML & CSS
	1. [http://www.w3.org/TR/2014/REC-html5-20141028](http://www.w3.org/TR/2014/REC-html5-20141028) HTML官方文档，仔细研究就可以算入门。
	1. [CSS: Cascading Style Sheets](https://www.w3.org/TR/2011/REC-CSS2-20110607) CSS官方文档，仔细研究就可以算入门。
	1. [图书][HTTP权威指南](http://product.dangdang.com/22840157.html)
	1. [图书][HTML & CSS 设计与构建网站](http://product.dangdang.com/23780195.html)
	1. [图书][JavaScript & jQuery交互式Web前端开发](http://product.dangdang.com/23731286.html)
	1. [图书][HTML5权威指南](http://product.dangdang.com/23386583.html)
	1. [文章][https://developer.mozilla.org/zh-CN/docs/Web](https://developer.mozilla.org/zh-CN/docs/Web)
	1. [视频][8小时学会HTML网页开发](http://study.163.com/course/courseMain.htm?courseId=432008)
	1. [视频][翁恺 HTML5入门](http://study.163.com/course/introduction/171001.htm#/courseDetail)
	1. [视频][麦子学院 HTML5+CSS3快速入门](http://study.163.com/course/courseMain.htm?courseId=999036)
	1. [视频][妙味 HTML5前端开发实战1](http://study.163.com/course/courseMain.htm?courseId=717031#/courseDetail)
	1. [视频][妙味 HTML5前端开发实战2](http://study.163.com/course/introduction/717017.htm#/courseDetail)
	1. [图书][CSS权威指南](http://product.dangdang.com/20050535.html) 必读
	1. [图书][CSS揭秘](http://product.dangdang.com/23953090.html) 书的序是《CSS权威指南》的作者写的。
	1. [图书][CSS禅意花园](http://product.dangdang.com/22806937.html) 是通过一个html，不同的css显示不同效果的实例，非常值得学习。
	1. [文章]CSS的核心之一：盒子模型
	1. [文章][CSS的核心之一：position](http://www.barelyfitz.com/screencast/html-training/css/positioning)
	1. [源码][CSS ZEN GARDEN](http://www.csszengarden.com)
	1. [框架][Bootstrap](https://getbootstrap.com/) Bootstrap is an open source toolkit for developing with HTML, CSS, and JS.(Bootstrap是一个用于使用HTML，CSS和JS进行开发的开源工具包。)
	1. [框架][EasyUI](https://www.jeasyui.com/) EasyUI for jQuery provides easy to use components for web developers, which is built on the popular jQuery core and HTML5. These make your applications suitable for today's web.(EasyUI for jQuery为Web开发人员提供了易于使用的组件，它基于流行的jQuery核心和HTML5构建。 这些使您的应用程序适合当今的Web。) 
	1. [GitHub][Material Design icons by Google(Google的Material Design图标)](https://github.com/google/material-design-icons)

1. ### JavaScript
	1. JavaScript是web开发必须学习的，ECMAScript是其规则来源。
		1. Developed by Brendan Eich of Netscape, under the name of  Mocha, then LiveScript, and finally JavaScript.(由Netscape的Brendan Eich开发，名为Mocha，然后是LiveScript，最后是JavaScript。) 
	1. [图书][JavaScript权威指南](http://product.dangdang.com/22722790.html)
	1. [图书][JavaScript高级程序设计](http://product.dangdang.com/22628333.html)
	1. [图书][JavaScript DOM编程艺术](http://product.dangdang.com/21049601.html)
	1. [图书][JavaScript语言精粹](http://product.dangdang.com/22872884.html)
	1. [图书][编写可维护的JavaScript](http://product.dangdang.com/23200995.html)
	1. [图书][高性能JavaScript](http://product.dangdang.com/23762095.html)
	1. [图书][深入理解JavaScript](http://product.dangdang.com/23838213.html)
	1. [图书][JavaScript函数式编程](http://product.dangdang.com/23742619.html)
	1. [图书][JavaScript设计模式](http://product.dangdang.com/23753847.html)
	1. [图书][JavaScript模式](http://product.dangdang.com/22819430.html)
	1. [图书][JavaScript经典实例](http://product.dangdang.com/23823045.html)
	1. [图书][数据结构与算法JavaScript描述](http://product.dangdang.com/23543139.html)
	1. [图书][编写可测试的JavaScript代码](http://product.dangdang.com/23648815.html)
	1. [视频][李炎恢JavaScript教程 第一季](http://study.163.com/course/introduction/252008.htm)
	1. [视频][JavaScript（翁恺）](http://study.163.com/course/introduction/195001.htm)
	1. [视频][JavaScript面试题系列](http://study.163.com/course/introduction/742021.htm)
	1. [jQuery](https://jquery.com/) jQuery is a fast, small, and feature-rich JavaScript library.
		1. [图书][jQuery基础教程](http://product.dangdang.com/23352323.html)
		1. [图书][精通jQuery](http://product.dangdang.com/23553774.html)
	1. [AngularJS](https://angularjs.org/) AngularJS is a JavaScript framework.(AngularJS是一个JavaScript框架。) 
		1. [图书][AngularJS学习手册](http://product.dangdang.com/23815176.html)
	1. [Node.js](https://github.com/nodejs/node) Node.js JavaScript runtime.(Node.js JavaScript运行环境)
1. DashBoard
	1. [RDash](https://github.com/rdash/rdash-angular) AngularJS implementation of the RDash admin dashboard theme.(AngularJS实现的RDash管理仪表板主题。)
		
1. ### XML
	Extensible Markup Language(可扩展标记语言)
	1. [http://www.w3school.com.cn/xml](http://www.w3school.com.cn/xml)
   1. [图书][XML入门经典](http://product.dangdang.com/23388817.html)
   1. [图书]无废话XML
1. ### JavaEE
	1. Servlet
		A servlet is a Java technology based web component, managed by a container, that generates dynamic content. Like other Java-based components, servlets are platform independent Java classes that are compiled to platform neutral bytecode that can be loaded dynamically into and run by a Java enabled web server. Containers, some- times called servlet engines, are web server extensions that provide servlet function- ality. Servlets interact with web clients via a request/response paradigm implemented by the servlet container.
		
		Servlet是一种基于Java技术的Web组件，由容器管理，生成动态内容。 与其他基于Java的组件一样，Servlet是独立于平台的Java类，它们被编译为平台中性字节码，可以动态加载到支持Java的Web服务器并由其运行。 容器（有时称为Servlet引擎）是提供Servlet功能的Web服务器扩展。 Servlet通过Servlet容器实现的请求/响应范例与Web客户端进行交互。 
		
		The servlet container is a part of a web server or application server that provides the network services over which requests and responses are sent, decodes MIME based requests, and formats MIME based responses. A servlet container also contains and manages servlets through their lifecycle. 
		
		Servlet容器是Web服务器或应用程序服务器的一部分，它提供发送请求和响应的网络服务，解码基于MIME的请求，并格式化基于MIME的响应。 Servlet容器还包含并管理Servlet的生命周期。
		1. [图书][Head First Servlets & Jsp](http://product.dangdang.com/20926088.html)
		1. [图书]Java Servlet & JSP Cookbook
		1. [文章][Servlet 工作原理解析](http://www.ibm.com/developerworks/cn/java/j-lo-servlet)
		1. [视频][Servlet Java  Web 编程（郭宏志）](http://study.163.com/course/introduction/648001.htms)
	1. JSP
		JSP: JavaServer Pages is a technology for developing web pages that include dynamic content. Unlike a plain HTML page, which contains static content that always remains the same, a JSP page can change its content based on any number of variable items, including the identity of the user, the user's browser type, information provided by the user, and selections made by the user.
		
		JSP：JavaServer Pages是一种用于开发包含动态内容的网页的技术。 与包含始终保持相同的静态内容的纯HTML页面不同，JSP页面可以根据任意数量的变量项更改其内容，包括用户的身份，用户的浏览器类型，用户提供的信息以及 用户做出的选择。
		JSP is a specification, not a product. 
		JSP是规范，而不是产品。
		1. [视频][尚学堂Jsp快速入门（高淇）](http://study.163.com/course/courseMain.htm?courseId=1067001)
    1. WEB容器
		1. [Tomcat](https://tomcat.apache.org/) The Apache Tomcat® software is an open source implementation of the Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket technologies.(ApacheTomcat®软件是Java Servlet，JavaServer Pages，Java Expression Language和Java WebSocket技术的开源实现。)
			1. [图书][Tomcat权威指南](http://product.dangdang.com/20702017.html)
			1. [图书][深入剖析Tomcat](http://product.dangdang.com/22585226.html) How Tomcat Works.
		1. [Jetty](https://www.eclipse.org/jetty/) Eclipse Jetty provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations. These components are open source and available for commercial use and distribution.(Eclipse Jetty提供了一个Web服务器和javax.servlet容器，以及对HTTP / 2，WebSocket，OSGi，JMX，JNDI，JAAS和许多其他集成的支持。 这些组件是开源的，可用于商业用途和分发。)
	1. JavaEE
		1. [图书][疯狂软件教育标准教材·轻量级Java EE企业应用实战(第4版):Struts 2+Spring 4+Hibernate整合开发(附光盘)](http://product.dangdang.com/23572565.html)
		1. [视频][JavaEE视频教程（郭宏志）](http://study.163.com/course/courseMain.htm?courseId=320027)
		1. [视频][30天轻松掌握JavaWeb视频（方立勋）](http://study.163.com/course/courseMain.htm?courseId=214022)
		1. [图书]J2EE Development without EJB
		1. [图书]J2EE设计开发编程指南
		1. [图书]IBM WebSphere Studio J2EE应用开发可以看看。
		1. [图书]精通Spring

1. ### 开发工具(Tools)
	1. 版本管理
		1. [Git](https://git-scm.com) Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.(Git是一个免费的开源分布式版本控制系统，旨在快速，高效地处理从小型到大型项目的所有事务。)
			1. [图书][Git权威指南](http://product.dangdang.com/21108669.html)
			1. [图书][Git版本控制管理](http://product.dangdang.com/23657840.html)
			1. [图书][精通Git](http://product.dangdang.com/25166975.html) GitHub联合创始人倾心之作，没有版本控制概念的读者也可轻松入门，涵盖Git常见工作场景，有效帮助程序员提升软技能。
			1. [GitHub][A collection of .gitignore templates](https://github.com/github/gitignore)
		1. [Gitlab](https://about.gitlab.com/) GitLab is the leading integrated product for modern software development. Connecting issue management, version control, code review, CI, CD, and monitoring.(GitLab是现代软件开发的领先集成产品。 连接问题管理，版本控制，代码审查，CI，CD和监控。)
		1. [Bitbucket](https://bitbucket.org/product) 类似github的功能，不过是可以闭源。(Bitbucket is more than just Git code management. Bitbucket gives teams one place to plan projects, collaborate on code, test and deploy.)
		1. [Mercurial](https://www.mercurial-scm.org) 源码控制管理工具。(Mercurial is a free, distributed source control management tool.)
	1. IDE
		1. [Eclipse](https://www.eclipse.org) The Platform for Open Innovation and Collaboration. 我们主要使用其Java的开发工具。
		1. [IntelliJ](https://www.jetbrains.com/idea) 一款IDE工具，个人感觉比Eclipse要好，推荐使用。
		1. [Netbeans](https://netbeans.org) 不推荐使用。Quickly and easily develop desktop, mobile and web applications with Java, JavaScript, HTML5, PHP, C/C++ and more.(使用Java，JavaScript，HTML5，PHP，C / C ++等快速轻松地开发桌面，移动和Web应用程序。)
		1. Android Studio
			1. 编码规范
				1. [Google Java 格式化](https://github.com/google/google-java-format) 推荐使用，插件比较多，各IDE支持好，程序员喜欢。Reformats Java source code to comply with Google Java Style.
				1. [Alibaba Java 编码规范](https://github.com/alibaba/Alibaba-Java-Coding-Guidelines) 
	1. 构建工具
		1. [Maven](http://maven.apache.org) Apache Maven is a software project management and comprehension tool.(Apache Maven是一个软件项目管理和理解工具。)
			1. [图书][Maven实战](http://product.dangdang.com/20977961.html)
		1. [Ant](http://ant.apache.org) Apache Ant is a Java library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other.(Apache Ant是一个Java库和命令行工具，其任务是将构建文件中描述的进程作为目标和扩展点相互依赖。)
		1. [Gradle](https://gradle.org/) Build Tool.(构建工具)
	1. 私服
		1. [Nexus](https://www.sonatype.com/nexus-repository-sonatype) Maven私服。
	1. 持续集成
		1. [Jenkins](https://jenkins.io/) The leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project.(领先的开源自动化服务器，Jenkins提供数百个插件来支持构建，部署和自动化任何项目。)
			1. [图书][Jenkins权威指南](http://product.dangdang.com/24048566.html)
		1. [Teamcity](https://www.jetbrains.com/teamcity/) Powerful Continuous Integration out of the box.(强大的持续集成开箱即用。)
	1. IDE插件
		1. [Findbugs](http://findbugs.sourceforge.net) 一般用在IDE插件，帮助发现bug。(This is the web page for FindBugs, a program which uses static analysis to look for bugs in Java code. )
		1. [Checkstyle](https://checkstyle.org) Checkstyle is a development tool to help programmers write Java code that adheres to a coding standard. By default it supports the Google Java Style Guide and Sun Code Conventions, but is highly configurable. It can be invoked with an ANT task and a command line program.(Checkstyle是一种开发工具，可帮助程序员编写符合编码标准的Java代码。 默认情况下，它支持Google Java样式指南和Sun代码约定，但具有高度可配置性。 它可以使用ANT任务和命令行程序调用。)
			1. [Checkstyle](https://github.com/checkstyle/checkstyle)
	1. 需求管理
		1. [Redmine](http://www.redmine.org/) Redmine is a flexible project management web application.(Redmine是一个灵活的项目管理Web应用程序。)
	1. Bug管理
		1. [Bugzilla](https://www.bugzilla.org/) Bugzilla is server software designed to help you manage software development.(Bugzilla是旨在帮助您管理软件开发的服务器软件。)
		1. [Jira](https://www.atlassian.com/software/jira) 
	1. 其他
		1. [Postman](https://www.getpostman.com/) API访问工具。(Postman Makes API Development Simple.)
	1. Wiki
		1. [DokuWiki](https://www.dokuwiki.org) DokuWiki是一个基于PHP开发的开源wiki引擎。它具有小巧、功能强大、灵活的特点，适合于中小团队和个人网站搭建知识库系统。
	1. [Shadowsocks](https://github.com/shadowsocks/shadowsocks)
	1. Atlassian
		1. [Confluence](https://www.atlassian.com/software/confluence) Confluence is content collaboration software that changes how modern teams work.(Confluence是内容协作软件，可以改变现代团队的工作方式。)
	1. [Clojure](https://www.clojure.org) Clojure is a dynamic environment you can interact with. Almost all of the language constructs are reified, and thus can be examined and changed.(Clojure是一个可以与之交互的动态环境。 几乎所有的语言结构都是具体的，因此可以进行检查和更改。) 
	1. [SonarCube](https://www.sonarqube.org) The leading product for continuous code quality.(连续代码质量的领导产品。)

1. ### Java库和框架及其他介绍
	1. Java常用库
		1. [Spring](https://spring.io)
		1. [MyBatis](http://www.mybatis.org/mybatis-3)
		1. [Hibernate](http://hibernate.org) 
		1. [Struts](https://struts.apache.org)
		1. [Guava](https://github.com/google/guava)  Google core libraries for Java.(适用于Java的Google核心库。)
	1. 日志
		1. [Log4j](https://logging.apache.org/log4j/2.x/)
		2. [SLF4j](https://www.slf4j.org)
		3. [Logback](https://logback.qos.ch)
		4. [Common-Logging](http://commons.apache.org/proper/commons-logging)
	1. 缓存
		1. [EHCache](http://www.ehcache.org/)
	1. IOC
		1. [Guice](https://github.com/google/guice) Guice (pronounced 'juice') is a lightweight dependency injection framework for Java 6 and above, brought to you by Google.(Guice（发音为'juice'）是Google为您带来的Java 6及更高版本的轻量级依赖注入框架。)
	1. AOP
		1. [AspectJ](http://www.eclipse.org/aspectj) A seamless aspect-oriented extension to the Java programming language.(面向Java编程语言的面向方面的无缝扩展。)
	1. [RxJava](https://github.com/ReactiveX/RxJava) RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.(RxJava - JVM的Reactive Extensions - 一个使用Java VM的可观察序列组成异步和基于事件的程序的库。)
	1. 定时调度
		1. [Quartz](http://www.quartz-scheduler.org/)  Java任务调度库。(open source job scheduling library that can be integrated within virtually any Java application - from the smallest stand-alone application to the largest e-commerce system. Quartz can be used to create simple or complex schedules for executing tens, hundreds, or even tens-of-thousands of jobs; jobs whose tasks are defined as standard Java components that may execute virtually anything you may program them to do. The Quartz Scheduler includes many enterprise-class features, such as support for JTA transactions and clustering.)
		1. [Elastic-Job](https://github.com/xianglesong/learning-javas/blob/master/platform/Elastic-job.md) 当当网出品的这款产品也不错，可以进行分布式分片调度。开箱即用，很方便。(A distributed scheduled job framework, based on Quartz and Zookeeper.)
	1. 内存数据库
		1. [MapDB](http://www.mapdb.org/)  MapDB provides Java Maps, Sets, Lists, Queues and other collections backed by off-heap or on-disk storage. It is a hybrid between java collection framework and embedded database engine.(MapDB提供由堆外或磁盘存储支持的Java映射，集，列表，队列和其他集合。 它是java集合框架和嵌入式数据库引擎之间的混合体。)	
	1. 数据库连接池
		1. [Druid](https://github.com/alibaba/druid)  为监控而生的数据库连接池！
		1. [DBCP](https://commons.apache.org/proper/commons-dbcp/)
	1. Http工具
		1. [HttpClient](https://hc.apache.org/httpcomponents-client-ga/)
		1. [OkHttp](http://square.github.io/okhttp/) An HTTP+HTTP/2 client for Android and Java applications.
	1. 时间工具
		1. [Joda](http://www.joda.org/joda-time/)  Joda-Time provides a quality replacement for the Java date and time classes.(Joda-Time为Java日期和时间类提供了高质量的替代品。)
	1. IO高性能库
		1. [Netty](https://github.com/xianglesong/learning-javas/blob/master/lib/Netty.md)   Netty算是Java的高级库了，掌握他，IO高级没问题。
		(Netty is an asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.)
	1. 内存检测
		1. [Leakcanary](https://github.com/square/leakcanary) A memory leak detection library for Android and Java.(适用于Android和Java的内存泄漏检测库。)
	1. 分布式数据库
		1. [Sharding-jdbc](https://github.com/xianglesong/learning-javas/blob/master/lib/Sharding-jdbc.md)  分库分表的轻量级解决方法之一。(Distributed database middleware.)
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
		1. [Jsoup](https://jsoup.org/) Jsoup is a Java library for working with real-world HTML. It provides a very convenient API for extracting and manipulating data, using the best of DOM, CSS, and jquery-like methods.(Jsoup是一个用于处理真实HTML的Java库。 它提供了一个非常方便的API，用于提取和操作数据，使用最好的DOM，CSS和类似jquery的方法。)
	1. 搜索引擎
		1. [Lucene](http://lucene.apache.org/) 建立索引和查询库。(The goal of Apache Lucene and Solr is to provide world class search capabilities.)
			1. [图书][Lucene实战](http://product.dangdang.com/21094976.html)
			1. [图书][Lucene分析与应用](http://product.dangdang.com/20362257.html)
			1. [论坛][Lucene](http://lucene.472066.n3.nabble.com)
			1. [GitHub][Luke](https://github.com/DmitryKey/luke) This is mavenised Luke: Lucene Toolbox Project.
		1. [Solr](http://lucene.apache.org/solr) 企业级搜索平台基于Lucene的封装。(Solr is the popular, blazing-fast, open source enterprise search platform built on Apache Lucene™.)
			1. [图书][Solr实战](http://product.dangdang.com/25082460.html)
			1. [图书][Solr Cookbook](http://product.dangdang.com/1900482179.html)
			1. [图书][Solr 1.4 Enterprise Search Server](http://product.dangdang.com/1900489897.html)
			1. [图书][Apache Solr 3 Enterprise Search Server](http://product.dangdang.com/1900489427.html)
			1. [论坛][Solr](http://lucene.472066.n3.nabble.com)
		1. [ElasticSearch](https://github.com/xianglesong/learning-javas/blob/master/platform/ElasticSearch.md) 分布式搜索利器，广泛使用。
		(Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases. As the heart of the Elastic Stack, it centrally stores your data so you can discover the expected and uncover the unexpected.)
			1. [图书][深入理解Elasticsearch](http://product.dangdang.com/25084053.html)
			1. [图书][Elasticsearch服务器开发](http://product.dangdang.com/23659310.html)
			1. [图书][Elasticsearch ](http://product.dangdang.com/1900490173.html)
			1. [GitHub][elasticsearch-head](https://github.com/mobz/elasticsearch-head) A web front end for an elastic search cluster.
			1. [GitHub][The Definitive Guide to Elasticsearch](https://github.com/elastic/elasticsearch-definitive-guide)
		1. [elasticsearch-analysis-ik](https://github.com/medcl/elasticsearch-analysis-ik) The IK Analysis plugin integrates Lucene IK analyzer into elasticsearch, support customized dictionary.
		1. [JPinyin](https://github.com/stuxuhai/jpinyin) JPinyin是一个汉字转拼音的Java开源类库。不过好像被删除了，需要自己找了。
		1. [pinyin4j](https://github.com/belerweb/pinyin4j) A copy of http://sourceforge.net/projects/pinyin4j, then deploy it to maven central repository.
	1. 自然语言处理
		1. 分词
			1. [HanLP](http://hanlp.hankcs.com) 自然语言处理，中文分词，词性标注，命名实体识别，依存句法分析，关键词提取，新词发现，短语提取，自动摘要，文本分类等。 
		1. 相似性
			1. Word2VEC
				1. [Word2VEC Java版本的一个实现](https://github.com/NLPchina/Word2VEC_java)
	1. 分布式存储和计算
		1. [Hadoop](https://github.com/xianglesong/learning-javas/blob/master/platform/Hadoop.md) 分布式文件存储和技术框架，云计算的利器。(The
		Apache™ Hadoop® project develops open-source software for reliable, scalable, distributed computing.)
		1. [Hive](http://hive.apache.org) The Apache Hive ™ data warehouse software facilitates reading, writing, and managing large datasets residing in distributed storage using SQL.(Apache Hive™数据仓库软件有助于使用SQL读取，编写和管理驻留在分布式存储中的大型数据集。)
	1. 分布式协调器
		1. [Zookeeper](https://github.com/xianglesong/learning-javas/blob/master/platform/Zookeeper.md) Zookeeper提供分布式同步功能，在今天的分布式系统中有广泛使用。(A high-performance coordination service for distributed applications.)
			1. [Curator](http://curator.apache.org) Apache Curator is a Java/JVM client library for Apache ZooKeeper, a distributed coordination service. It includes a highlevel API framework and utilities to make using Apache ZooKeeper much easier and more reliable. It also includes recipes for common use cases and extensions such as service discovery and a Java 8 asynchronous DSL.(Apache Curator是Apache ZooKeeper的Java / JVM客户端库，Apache ZooKeeper是一种分布式协调服务。 它包括一个高级API框架和实用程序，使Apache ZooKeeper更容易，更可靠。 它还包括常见用例和扩展（如服务发现和Java 8异步DSL）的配方。)
	1. 分布式数据库
		1. [HBase](http://hbase.apache.org/) 建立在Hadoop上的分布式数据库。(Apache HBase™ is the Hadoop database, a distributed, scalable, big data store.)
		1. [Cassandra](http://cassandra.apache.org/) 分布式数据库(The Apache Cassandra database is the right choice when you need scalability and high availability without compromising performance.)
	1. 工作流调度
		1. [Oozie](http://oozie.apache.org/) Hadoop工作流调度工具。(Apache Oozie Workflow Scheduler for Hadoop.)
	1. 性能测试
		1. [JMeter](http://jmeter.apache.org/) The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance. It was originally designed for testing Web Applications but has since expanded to other test functions.(pache JMeter™应用程序是开源软件，是一种100％纯Java应用程序，旨在加载测试功能行为和测量性能。 它最初是为测试Web应用程序而设计的，但后来扩展到其他测试功能。)
			1. [图书][全栈性能测试修炼宝典 JMeter实战](http://product.dangdang.com/24048538.html)
   1. 二维码
	    1. [ZXing](https://github.com/zxing/zxing) ZXing ("Zebra Crossing") barcode scanning library for Java, Android.(ZXing（“Zebra Crossing”）用于Java，Android的条形码扫描库。)
	1. 图像处理
	    1. [ImageMagick](https://www.imagemagick.org/script/index.php) Use ImageMagick® to create, edit, compose, or convert bitmap images.(使用ImageMagick®创建，编辑，撰写或转换位图图像。)
	1. [Neo4j](https://neo4j.com/) The graph database platform.(图数据库平台。)
	1. 分布式跟踪
		1. [PinPoint](https://github.com/naver/pinpoint) Pinpoint is an open source APM (Application Performance Management) tool for large-scale distributed systems written in Java.(Pinpoint是一个开源的APM（应用程序性能管理）工具，适用于用Java编写的大型分布式系统。)
		1. [CAT](https://github.com/dianping/cat) Central Application Tracking.
	1. 分布式存储
	    1. [Ceph](https://ceph.com/)
	1. 数据挖掘
	    1. [Weka](https://www.cs.waikato.ac.nz/ml/weka) Weka is a collection of machine learning algorithms for data mining tasks.(Weka是用于数据挖掘任务的机器学习算法集合的工具。) 
	    	1. [图书][数据挖掘：实用机器学习工具与技术](http://product.dangdang.com/23469858.html)
	    	1. [文章][用 WEKA 进行数据挖掘:简介和回归](http://www.ibm.com/developerworks/cn/opensource/os-weka1/index.html)
	    	1. [文章][用 WEKA 进行数据挖掘:分类和群集](http://www.ibm.com/developerworks/cn/opensource/os-weka1/index.html)
	    	1. [文章][用 WEKA 进行数据挖掘:最近邻和服务器端库](http://www.ibm.com/developerworks/cn/opensource/os-weka1/index.html)
	    1. [Mahout](http://mahout.apache.org/) For Creating Scalable Performant Machine Learning Applications.(用于创建可扩展高性能的机器学习应用程序。)
	    	1. [图书][Mahout in Action]
	    1. [Spark](https://spark.apache.org/) A unified analytics engine for large-scale data processing.(用于大规模数据处理的统一分析引擎。)
	    	1. [图书][Spark快速大数据分析](http://product.dangdang.com/23790700.html)
	1. [Kylin](http://kylin.apache.org/cn) Apache Kylin™ is an open source Distributed Analytics Engine designed to provide SQL interface and multi-dimensional analysis (OLAP) on Hadoop/Spark supporting extremely large datasets, original contributed from eBay Inc.(Apache Kylin™是一个开源的分布式分析引擎，旨在为支持极大型数据集的Hadoop / Spark提供SQL接口和多维分析（OLAP），原创由eBay Inc.提供。)
	1. [SpringCloud](http://projects.spring.io/spring-cloud)
	    1. [SpringBoot](http://spring.io/projects/spring-boot) Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run".(Spring Boot可以轻松创建独立的，生产级的基于Spring的应用程序，您可以“即刻运行”。)
	    1. [Eureka](https://github.com/Netflix/eureka) AWS Service registry for resilient mid-tier load balancing and failover.(AWS服务注册，用于弹性中间层负载平衡和故障转移。)
	    1. [Zuul](https://github.com/Netflix/zuul) Zuul is a gateway service that provides dynamic routing, monitoring, resiliency, security, and more.(Zuul是一种网关服务，提供动态路由，监控，弹性，安全性等。)
	    1. [Zipkin](https://github.com/openzipkin/zipkin) Zipkin is a distributed tracing system.(Zipkin是一种分布式跟踪系统。)
	    1. [Hystrix](https://github.com/Netflix/Hystrix) Hystrix is a latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable.(Hystrix是一个延迟和容错库，旨在隔离对远程系统，服务和第三方库的访问点，停止级联故障，并在复杂的分布式系统中实现弹性，在这些系统中，故障是不可避免的。)
	1. 模版引擎
		1. [Velocity](http://velocity.apache.org) Velocity is a Java-based template engine.(Velocity是一个基于Java的模板引擎。) 
		1. [FreeMarker](https://freemarker.apache.org) FreeMarker is a template engine.(FreeMarker是一个模板引擎。)
	1. [Swagger](https://swagger.io) Swagger aides in development across the entire API lifecycle, from design and documentation, to test and deployment.(Swagger在整个API生命周期的开发过程中提供帮助，从设计和文档到测试和部署。) 
		1. [GitHub][swagger-ui-layer](https://github.com/caspar-chen/swagger-ui-layer)
	1. [ELK](https://www.elastic.co)
		1. [Logstash](https://github.com/elastic/logstash) Logstash - transport and process your logs, events, or other data.(Logstash - 传输和处理您的日志，事件或其他数据。)
		1. [Kibana](https://github.com/elastic/kibana) Kibana analytics and search dashboard for Elasticsearch.(Elasticsearch的Kibana分析和搜索仪表板。)
	1. [JUnit](https://junit.org/junit4) A programmer-oriented testing framework for Java.(面向程序员的Java测试框架。)
	1. [EasyMock](http://easymock.org) EasyMock, makes mocking easier since 2001.(自2001年以来，EasyMock使得模拟变得更容易。)
	1. [JFreeChart](http://www.jfree.org/jfreechart) JFreeChart is a free 100% Java chart library that makes it easy for developers to display professional quality charts in their applications.(JFreeChart是一个免费的100％Java图表库，使开发人员可以轻松地在其应用程序中显示专业质量的图表。) 
	1. 深度学习
	   1. [DeepLearning](https://github.com/yusugomori/DeepLearning) Deep Learning (Python, C, C++, Java, Scala, Go) http://yusugomori.com
		1. [Deep Learning 中文翻译](https://github.com/exacity/deeplearningbook-chinese) Deep Learning Book Chinese Translation.
	1. [WordPress](https://cn.wordpress.org) WordPress是使用PHP语言开发的博客平台，用户可以在支持PHP和MySQL数据库的服务器上架设属于自己的网站。也可以把 WordPress当作一个内容管理系统（CMS）来使用。
	1. 数据库
		1. [MySQL](https://www.mysql.com)
			1. [图书][MySQL DBA修炼之道](http://product.dangdang.com/24194120.html) 数据库技术专家撰写，多年数据库领域的经验结晶。实战性强，从架构、调优、运维、开发、测试等多个角度对MySQL管理和维护进行了全方位的归纳和总结，包含大量来自实际生产环境的经典案例。
		2. Teradata
	1. 缓存
		1. [Redis](https://redis.io) Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache and message broker.(Redis是一个开源（BSD许可），内存数据结构存储，用作数据库，缓存和消息代理。)
		1. [MemCache](http://memcached.org) A distributed memory object caching system.(分布式内存对象缓存系统。)
		1. [Varnish](http://varnish-cache.org) Varnish HTTP Cache.
		1. [Squid](http://www.squid-cache.org) Squid is a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more.(Squid是支持HTTP，HTTPS，FTP等的Web的缓存代理。)
	1. 消息
		1. [RabbitMQ](http://www.rabbitmq.com) RabbitMQ is the most widely deployed open source message broker.(RabbitMQ是部署最广泛的开源消息代理。)
			1. [图书][RabbitMQ实战：高效部署分布式消息队列](http://product.dangdang.com/23799313.html)
			1. [GitHub][Tutorials for using RabbitMQ in various ways ](https://github.com/rabbitmq/rabbitmq-tutorials) 以各种方式使用RabbitMQ的教程http://www.rabbitmq.com/getstarted.html
		1. [Kafka](http://kafka.apache.org) A distributed streaming platform.
			1. [GitHub][Kafka Manager](https://github.com/yahoo/kafka-manager) A tool for managing Apache Kafka.
			1. [图书][Kafka权威指南](http://product.dangdang.com/25211884.html)
			1. [文章][kafka入门：简介、使用场景、设计原理、主要配置及集群搭建（转）](https://www.cnblogs.com/likehua/p/3999538.html)
	1. 代理、反向代理
		1. [Nginx](http://nginx.org) Nginx [engine x] is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.(Nginx [engine x]是一个HTTP和反向代理服务器，一个邮件代理服务器和一个通用的TCP / UDP代理服务器，最初由Igor Sysoev编写。)
		1. [HAProxy](http://www.haproxy.org) 
	1. 虚拟机
		1. [VirtualBox](https://www.virtualbox.org)
		1. [VMware](https://www.vmware.com) 
	1. [Docker](https://www.docker.com) Build, Manage and Secure Your Apps Anywhere. Your Way.(随处构建，管理和保护您的应用程序。 你的方式。)
	1. [Kubernetes](https://kubernetes.io) 
Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.(Kubernetes是一个开源系统，用于自动化容器化应用程序的部署，扩展和管理。)
	1. [Mesos](http://mesos.apache.org) Apache Mesos abstracts CPU, memory, storage, and other compute resources away from machines (physical or virtual), enabling fault-tolerant and elastic distributed systems to easily be built and run effectively.(Apache Mesos将CPU，内存，存储和其他计算资源从机器（物理或虚拟）中抽象出来，使容错和弹性分布式系统能够轻松构建并有效运行。)
	1. 序列化、反序列化
		1. [Protobuf](https://github.com/google/protobuf) Protocol Buffers - Google's data interchange format https://developers.google.com/protocol-buffers.
	1. MQTT
		1. [Mosquito](https://mosquitto.org) Eclipse Mosquitto is an open source (EPL/EDL licensed) message broker that implements the MQTT protocol versions 3.1 and 3.1.1. Mosquitto is lightweight and is suitable for use on all devices from low power single board computers to full servers.(Eclipse Mosquitto是一个开源（EPL / EDL许可）消息代理，它实现了MQTT协议版本3.1和3.1.1。 Mosquitto重量轻，适用于从低功耗单板计算机到完整服务器的所有设备。)
	1. [Storm](http://storm.apache.org) Apache Storm is a free and open source distributed realtime computation system.(Apache Storm是一个免费的开源分布式实时计算系统。) 
		1. [图书][Storm分布式实时计算模式](http://product.dangdang.com/23616223.html) Apache Storm 项目核心贡献者亲笔撰写，涵盖多种分布式计算相关主题。
	1. ABTest
		1. [Sixpack](https://github.com/sixpack/sixpack-java) A Java client for the Sixpack A/B testing framework.
	1. [Tesseract](https://github.com/tesseract-ocr/tesseract) Tesseract Open Source OCR Engine.
	1. [ZeroMQ](http://zeromq.org) Distributed Messaging.
	1. [docx4j](https://github.com/plutext/docx4j)
	1. Trace
		1. [BTrace](https://github.com/btraceio/btrace) BTrace - a safe, dynamic tracing tool for the Java platform.(BTrace - Java平台的安全动态跟踪工具。)
			1. [文章][BTrace][Java在线问题排查利器之Btrace&Greys](http://tech.lede.com/2017/10/11/rd/server/javaToolsBTrace/)
			
## Linux
Linux是Java程序员必须掌握的核心工具。

1. ###  Linux基础
	1. [图书][鸟哥的Linux私房菜:基础学习篇](http://product.dangdang.com/20866026.html)
	1. [图书][Linux命令行大全](http://product.dangdang.com/23204024.html) 从命令行学起，也是学习Linux的一个不错路径。
	1. [图书][UNIX/Linux 系统管理技术手册](http://product.dangdang.com/22750915.html)
	1. [网站][http://linuxcommand.org](http://linuxcommand.org)

1. ### Shell
	1. [图书][Linux命令行与shell脚本编程大全](http://product.dangdang.com/24013685.html)
	1. [图书][Shell脚本学习指南](http://product.dangdang.com/20574166.html)
	1. [视频][Linux 入门基础（苏勇）](http://study.163.com/course/introduction/232007.htm)
	1. [视频][李明老师讲Linux（李明）](http://study.163.com/course/courseMain.htm)
	1. [视频][Linux视频教程（传智播客的韩顺平）](http://study.163.com/course/introduction/215011.htm)
	1. [视频][计算机专业导论](http://study.163.com/curricula/cs.htm)
	1. [认证][LPI Linux认证权威指南](http://product.dangdang.com/23217995.html)
	
1. ### Vim
	1. VI
		1. $输入$vimtutor en可以进入自带教程，好好学习，天天向上。
		1. [http://www.linfo.org/vi/index.html](http://www.linfo.org/vi/index.html)
		1. Emacs和VIM：神的编辑器和编辑器之神。
1. ### Linux编程
	1. Linux源码
		1. [图书]莱昂氏UNIX源代码分析
		1. [图书][Linux内核完全注释](http://product.dangdang.com/8914120.html)
	1. Linux编程
		1. [图书][Unix编程艺术](http://product.dangdang.com/22863178.html) 被极客程序员奉如圭臬的神人神作。
		1. [图书][UNIX环境高级编程](http://product.dangdang.com/23481078.html)
		1. [图书][Linux内核设计与实现](http://product.dangdang.com/21065276.html)
		1. [图书][深入理解LINUX内核](http://product.dangdang.com/20046247.html)
	
## 计算机基础知识
学习Java首先需要对计算机基础知识有比较好的理解。这个是未来能否走的更远、更好的关键。

1. ### 编程语言
	1. C
		1. [图书][C程序设计语言](http://product.dangdang.com/8766529.html)
		1. [图书][C程序设计语言(英文版)](http://product.dangdang.com/9196242.html)
		1. [图书][C 和指针](http://product.dangdang.com/20165942.html)
		1. [视频][C语言程序设计](http://study.163.com/curricula/cs.htm)
	1. C++
		1. [网站][http://www.cprogramming.com](https://www.cprogramming.com/)里有个c-tutorial
		1. [文章]高质量C++/C编程指南 林锐 博士
		1. [图书]GCC: The Complete Reference
		1. [源码][https://github.com/antirez/redis](https://github.com/antirez/redis) 
		1. [源码][https://github.com/nginx/nginx](https://github.com/nginx/nginx)
		
1. ### 数据结构和算法
	1. [图书][数据结构与算法分析：Java语言描述](http://product.dangdang.com/23918741.html)
	1. [图书][大话数据结构](http://product.dangdang.com/21088369.html)
	1. [图书][Java数据结构和算法](http://product.dangdang.com/9323527.html) 英文《Data Structures & Algorithms in Java》Robert Lafore著，特别推荐。
	1. [视频][数据结构和算法](http://study.163.com/course/introduction/468002.htm)
	1. [网站][数据学习的可视化网站http://zh.visualgo.net](http://zh.visualgo.net)
	1. [图书][算法导论](http://product.dangdang.com/22927209.html) 算法的最好的图书之一。
		1. [视频][麻省理工学院公开课：算法导论](http://open.163.com/special/opencourse/algorithms.html) 老头讲的非常好，年轻的一般。
	1. [图书][算法](http://product.dangdang.com/22880871.html) Knuth的学生写的，使用Java语言描述，值得一看。
	1. [网站][leetcode](https://leetcode.com) 算法题库。
	1. [网站][lintcode](https://www.lintcode.com/problem/?tag=lintcode-copyright) 中文版leetcode。
	1. [ACM-ICPC](https://icpc.baylor.edu)
	1. 大神的书[Donald E. Knuth:图灵奖得主]
		1. [图书][计算机程序设计艺术 卷1 基本算法](http://product.dangdang.com/23839682.html)
		1. [图书][计算机程序设计艺术 卷2 半数值算法](http://product.dangdang.com/24007299.html)
		1. [图书][计算机程序设计艺术 卷3 排序与查找](http://product.dangdang.com/24195308.html)
	1. [GitHub][算法学习笔记](https://github.com/nonstriater/Learn-Algorithms)
	
1. ### 操作系统
	1. [图书][操作系统设计与实现](http://product.dangdang.com/23727594.html) 此书告诉您如何实现一个操作系统，比学校里告诉您的更多，更好理解。当年Linus就是看这本书，编写的Linux。
		1. [网站][MINIX](http://www.minix3.org)
	1. [网站][GeekOS](http://geekos.sourceforge.net) The goal of GeekOS is to be a tool for learning about operating system kernels.  As of version 0.2.0, it comes with a set of projects suitable for use in an undergraduate operating systems course, or for self-directed learning.  GeekOS has been used in courses at a number of colleges and universities.
	1. [文章][操作系统学习笔记](https://blog.csdn.net/longronglin/article/category/536556)
	1. [图书][深入理解计算机系统](http://product.dangdang.com/24106647.html)
	1. [图书][30天自制操作系统](http://product.dangdang.com/22826468.html)
	1. [图书][Orange‘s一个操作系统的实现](http://product.dangdang.com/20597043.html)
	1. [图书][鸟哥的Linux私房菜](http://product.dangdang.com/20866026.html)
	
1. ### 编译原理
	1. [图书][编译原理](http://product.dangdang.com/20427584.html) 编译原理的水平与程序员水平正相关，光会写程序，不能理解编译原理，是很难写出高水平程序的。龙书非常出名，谁学谁知道。工作后您可能会使用各种各样的语言，他们是如何工作和执行的，编译原理是不可或缺的重要一环。
	1. [图书][自制编程语言](http://product.dangdang.com/23363722.html)
	1. [图书][编译原理及实现](http://product.dangdang.com/23781751.html) 这本书个人时强热推荐的，我读研期间重新做编译器，主要参考此书，非常好。
	1. [文章][编译原理学习基本步骤](http://blog.csdn.net/longronglin/article/details/5920957)
	1. [文章][编译原理解析](http://blog.csdn.net/longronglin/article/details/1109436) 如果把我上面的内容学好，可以说编译原理掌握的不错了。特别是我的内容是参考上面的清华大学孙悦红老师的课本做的，还得到了其支持。
	1. [图书][计算机程序的构造和解释](http://product.dangdang.com/8793968.html)
1. ### 数据库
	1. 关系数据库
		1. [图书]Transact-SQL权威指南 经典，没有图书卖了。
		1. [图书][Head First SQL](http://product.dangdang.com/21040398.html)
		1. [图书][Teach Yourself SQL in 21 Days](http://product.dangdang.com/1244621523.html)
		1. [图书][SQL必知必会(第3版)](http://product.dangdang.com/23246707.html)
		1. [图书][SQL教程（杨中科）](http://study.163.com/course/introduction/215012.htm#/courseDetail) 使用微软SQL Server讲解的。
		1. [图书][MySQL数据库（高洛峰）](http://study.163.com/course/introduction/247003.htm#/courseDetail)
		1. [视频][尚学堂马士兵Oracle视频教程](http://study.163.com/course/introduction/344012.htm#/courseDetail)
		1. Codd 12 Rules	
		1. CAP理论: 又称CAP定理，指的是在一个分布式系统中， Consistency（一致性）、 Availability（可用性）、Partition tolerance（分区容错性），三者不可得兼。
			1. 理论首先把分布式系统中的三个特性进行了如下归纳：
				1. 一致性（C）：在分布式系统中的所有数据备份，在同一时刻是否同样的值。（等同于所有节点访问同一份最新的数据副本）
				1. 可用性（A）：在集群中一部分节点故障后，集群整体是否还能响应客户端的读写请求。（对数据更新具备高可用性）
				1. 分区容错性（P）：以实际效果而言，分区相当于对通信的时限要求。系统如果不能在时限内达成数据一致性，就意味着发生了分区的情况，必须就当前操作在C和A之间做出选择。
	1. NOSQL
		1. MongoDB
			1. [图书][MongoDB权威指南](http://product.dangdang.com/23399173.html)
		2. HBase
			1. [图书][HBase权威指南](http://product.dangdang.com/23336430.html)
		3. Cassandra
			1. [图书][Cassandra权威指南](http://product.dangdang.com/25204594.html)
1. ### 计算机网络
	1. [图书][计算机网络自顶向下方法](http://product.dangdang.com/25299722.html)
	1. [图书][TCP/IP详解卷1:协议](http://product.dangdang.com/23989588.html)
	1. [图书][图解TCP/IP](http://product.dangdang.com/23265967.html)
	1. [图书][图解HTTP](http://product.dangdang.com/23462067.html)
	1. [视频][计算机网络技术与应用](http://study.163.com/course/courseMain.htm?courseId=1255007)
	2. [文章][从输入 URL 到页面加载完成的过程中都发生了什么事情？](http://fex.baidu.com/blog/2014/05/what-happen)
	3. [考证][CCNA学习指南](http://product.dangdang.com/22630120.html)
	4. [网站][鸿鹄论坛](http://bbs.hh010.com) 鸿鹄论坛，国内专业的思科华为微软网络工程师技术社区。
1. ### 软件工程
	1. [图书][软件工程](http://product.dangdang.com/25231549.html)
	1. [图书][代码大全](http://product.dangdang.com/22543344.html)
	1. [图书][人月神话](http://product.dangdang.com/23677487.html)
	1. [图书][敏捷软件开发(原则模式与实践)](http://product.dangdang.com/8771440.html)
	1. [图书][重构](http://product.dangdang.com/23734636.html)
	1. [图书][软件测试](http://product.dangdang.com/9159972.html)
1. ### CPU
	1. [文章][CISC模型微处理器设计（VHDL实现）](https://blog.csdn.net/longronglin/article/details/1055388) 
1. ### 汇编语言
	1. [图书][汇编语言](http://product.dangdang.com/25178843.html) 王爽的这版，我觉得入门是最好的。写的浅显易懂，更深入的需要看别的图书。
	1. [资料]Intel Architecture Software Developer's Manual Volume1: Basic Architecture
	1. [资料]Intel Architecture Software Developer's Manual Volume2:Instructions Set Reference 
	1. [资料]Intel Architecture Software Developer's Manual Volume3:System Programming Guide

1. ### 数据仓库及数据挖掘
	1. [图书][数据仓库](http://product.dangdang.com/9200409.html)
	1. ETL
		1. [Talend](https://www.talend.com/resources/what-is-etl/)
	1. [Teradata](https://www.teradata.com.cn)
	1. [DataStage](https://www.ibm.com/us-en/marketplace/datastage) Delivers advanced enterprise ETL.
	1. [图书][数据挖掘：概念与技术](http://product.dangdang.com/22846300.html)
	1. 数据挖掘领域的十大经典算法
		1. C4.5
		1. The k-means algorithm
		1. Support vector machines
		1. The Apriori algorithm
		1. 最大期望(EM)算法
		1. PageRank
		1. AdaBoost
		1. kNN: k-nearest neighbor classification
		1. Naive Bayes
		1. CART: 分类与回归树
1. ### 机器学习及人工智能
	1. [图书][推荐系统实践](http://product.dangdang.com/22775361.html)
	1. [图书][深度学习](http://product.dangdang.com/25111382.html)
	1. [GitHub][List of Recommender Systems](https://github.com/grahamjenson/list_of_recommender_systems)
1. ### 图灵奖
	1. 图灵：计算机之父。艾伦·麦席森·图灵（Alan Mathison Turing，1912年6月23日－1954年6月7日），英国数学家、逻辑学家，被称为计算机之父，人工智能之父。
	1. [历届图灵奖得主及贡献](https://amturing.acm.org)

## 科学研究
能否独立研究解决问题。

1. ### 期刊杂志
	1. [电脑报](http://www.icpcw.com) 
	1. [ACM](https://www.acm.org)
	1. [IEEE](https://www.ieee.org)

1. ### 论文(Paper)
	1. 搜索下载
		1. [万方数据](http://www.wanfangdata.com.cn/index.html) 整合数亿条全球优质学术资源，集成期刊、学位、会议、科技报告、专利、视频等十余种资源类型，覆盖各研究层次，感知用户学术背景，智慧你的搜索。万方智搜致力于帮助用户精准发现、获取与沉淀学术精华。万方数据愿与合作伙伴共同打造知识服务的基石、共建学术生态。
		1. [中国知网](http://cnki.net) 中国知网知识发现网络平台—面向海内外读者提供中国学术文献、外文文献、学位论文、报纸、会议、年鉴、工具书等。
		1. [维普](http://cqvip.com)
	1. 经典论文
		1. [The java.util.concurrent Synchronizer Framework](http://gee.cs.oswego.edu/dl/papers/aqs.pdf) Doug Lea.
		1. The Google File System
		1. MapReduce: Simplified Data Processing Large Clusters
		1. Bigtabel: A Distributed Storage System for Struchured Data 

1. ### 会议(Meeting)
	1. 自然语言处理

## 综合
1. ### 考试认证
	1. OCJP Oracle公司的Java工程师认证。通过该考试表明较好的掌握Java基础知识。
	1. Linux 有红帽认证等。
	1. Database 有Oracle和DB2等认证。
	1. [软考](http://www.ruankao.org.cn/)
		1. 考试介绍 [http://www.ruankao.org.cn/platform](http://www.ruankao.org.cn/platform)
			1. 软件设计师  个人觉得大三学生可以开始考这个，工作的就更容易了。
			1. 信息系统项目管理师  这个偏管理的，主要是论文会卡人，容易的考个中级的系统集成项目管理工程师就可以，这个不考论文。

1. ### 自动化测试及运维
	1. [图书][SRE：Google运维解密](http://product.dangdang.com/24032293.html)
	1. [Selium](https://www.seleniumhq.org)  A browser automation framework and ecosystem. 
		1. [图书][Selenium 2自动化测试实战——基于Python语言](http://product.dangdang.com/23851258.html)
	1. [Azkaban](https://azkaban.github.io/) Open-source Workflow Manager.
	1. Website Analystics
		1. [Piwik](https://piwik.org) 
		1. Baidu
		1. Google
	1. CDN
		1. 其实是域名劫持技术黑科技的好应用。 
		1. [网宿科技](http://www.wangsu.com)
	1. [JumpServer](http://www.jumpserver.org/) 是全球首款完全开源的堡垒机,使用GNU GPL v2.0开源协议,是符合 4A 的专业运维安全审计系统。
	1. [图书][海量运维、运营规划之道](http://product.dangdang.com/23380755.html)
	1. [图书][网站运维技术与实践]
	1. Zabbix
		1. [图书][Zabbix监控系统]
1. ### 网络安全
	1. [图书][白帽子讲Web安全](http://product.dangdang.com/23506094.html)
1. ### 云平台
	1. [阿里云](https://www.aliyun.com) 我个人也购买过，我以前的公司沪江购买过。
	1. [腾讯云](https://cloud.tencent.com)
	1. [青云](https://www.qingcloud.com) 我以前的公司微鲸印象中，使用的是这个。减去了自己搭建服务器和运维的很多麻烦，还是相当不错的。
	1. [AWS](https://aws.amazon.com)
	1. [搬瓦工](http://banwagong.cn)
	1. [七牛](https://www.qiniu.com)
1. ### 精华文档
	1. 缓存
		1. [缓存那些事](https://tech.meituan.com/cache_about.html)
1. ### 标准规范
	1. [HTML](https://www.w3.org/TR/html)
	1. [CSS](https://www.w3.org/TR/CSS/)
	1. [Hypertext Transfer Protocol -- HTTP/1.1](https://www.w3.org/Protocols/rfc2616/rfc2616.html)
1. ### API
	1. [Google API Design Guide](https://cloud.google.com/apis/design)
	2. [GitHub][HTTP API Design Guide](https://github.com/interagent/http-api-design)
	3. [GitHub][HTTP API 设计指南](https://github.com/ZhangBohan/http-api-design-ZH_CN)
1. ### RESTful API
	1. [RESTful API 论文](http://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)
1. ### Mac工具
   1. [Alfred](https://www.alfredapp.com) Alfred is a productivity application for Mac OS X.
   1. [iTerm2](https://www.iterm2.com) iTerm2 is a replacement for Terminal and the successor to iTerm.
   1. [Chrome](https://www.google.cn/chrome) 浏览器。
   1. [搜狗输入法](https://pinyin.sogou.com/mac) 输入法。
   1. [Foxmail](https://www.foxmail.com) 邮箱管理。 
   1. [EverNote](https://evernote.com/intl/zh-cn) 随时随地获取、整理、分享笔记，让灵感时刻与你同行。
   1. [XMind](https://www.xmind.net) 思维导图工具。
   1. [FileZilla](https://filezilla-project.org) The free FTP solution.
   1. [Jet Brains](http://www.jetbrains.com) JetBrains, creator of the leading Java IDE - IntelliJ IDEA - is a cutting-edge software vendor specializing in the creation of intelligent development tools.
   1. [Wireshark](https://www.wireshark.org) 网络封包分析软件。
   1. [CleanMyMac](https://cleanmymac.com) Your Mac. As good as new. Mac清理管理工具。
   1. [RescueTime](https://www.rescuetime.com) A personal analytics service that shows you how you spend your time and provides tools to help you be more productive. 时间花费跟踪工具。
   1. [StarUML](http://staruml.io) A sophisticated software modeler for agile and concise modeling.
   1. [Skype](https://web.skype.com) 是超清晰网络电话工具，电脑间通话永远免费，打国内国际固定/移动电话只需市话费。
   1. [Sequel Pro](http://www.sequelpro.com) Sequel Pro is a fast, easy-to-use Mac database management application for working with MySQL databases.
   1. [Parall Client](https://www.parallels.com/cn/products/ras/features/parallels-client) Parallels Client is an easy-to-install client software that provides access to your Parallels RAS installations.
	1. [Dash](https://kapeli.com/dash)  快速访问API。(Dash gives your Mac instant offline access to 200+ API documentation sets.)
	1. [Redis Desktop Manager](https://redisdesktop.com/)  访问Redis的工具。(Redis Desktop Manager (aka RDM) — is a fast open source Redis database management application for Windows, Linux and MacOS.)
		1. [图书][Redis实战](http://product.dangdang.com/23800641.html)
	1. [Robo 3T](https://robomongo.org/)  访问MongoDB的工具。(Robo 3T (formerly Robomongo) is the free lightweight GUI for MongoDB enthusiasts.)
	1. [MongoHub](https://github.com/jeromelebel/MongoHub-Mac)  访问MongoDB的工具。(Mac Native Mongodb Client.)
	1. [SourceTree](https://www.sourcetreeapp.com)  版本控制管理工具。(The friendly GUI for Mercurial and Git on your Mac.)
	1. [SnailSVN](https://langui.net/snailsvn) 访问svn工具。
	1. [MacDown](http://macdown.uranusjr.com) MarkDown编写工具。
	1. [Sublime Text](http://www.sublimetext.com)  免费的文本编辑工具。(A sophisticated text editor for code, markup and prose.)
	1. [Wunderlist: To-Do List & Tasks](https://www.wunderlist.com/zh) TODO工具。奇妙清单是完成工作的最简单方法。无论你是在安排度假、与伙伴分享购物清单，或是管理多个工作项目，奇妙清单会帮助你完成所有个人和职业待办事项。
   1. [Luyten](https://github.com/deathmarine/Luyten) An Open Source Java Decompiler Gui for Procyon.
   1. [GNS3](https://www.gns3.com) The software that empowers network professionals.
   1. [Office](https://products.office.com/zh-cn/mac/microsoft-office-for-mac) 确是 Office，专为 Mac 打造。
   1. [LaTeX](https://www.latex-project.org) LaTeX is a high-quality typesetting system.
   1. [Postman](https://www.getpostman.com) Postman is the only complete API development environment, for API developers.
1. ### 第三方工具
	1. [友盟](https://www.umeng.com) 第三方全域大数据服务提供商，为客户提供PC/APP/线下统计，广告效果监测，消息推送/微社区/分享/IM等运营工具，DIP，全域指数与行业报告等。
	2. [极光](https://www.jiguang.cn) 第三方消息推送服务。
1. ### 推荐GitHub
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
1. ### 微信公众号
	1. 神秘的程序员们
1. ### 其他语言
	1. Python
		1. [图书][Python基础教程](http://product.dangdang.com/25218035.html)
	1. Android
		1. [图书][疯狂Android讲义](http://product.dangdang.com/23699102.html)
		1. [图书][Android编程权威指南](http://product.dangdang.com/25102877.html)
	1. iOS
		1. [图书][精通iOS开发](http://product.dangdang.com/25113926.html)
	1. PHP
		1. [图书][PHP和MySQL Web开发](http://product.dangdang.com/20546846.html)
		1. [图书][深入PHP：面向对象、模式与实践](http://product.dangdang.com/22459608.html)
	1. 其他
		1. [图书]编码的奥秘
		1. [图书][松本行弘的程序世界](http://product.dangdang.com/22471151.html)
		1. [图书][编程珠玑](http://product.dangdang.com/23640352.html) 
1. ### 面试
	1. [GitHub][Interviews](https://github.com/kdn251/interviews) Everything you need to know to get the job.(找工作需要了解的一切。)
1. ### 项目管理
	1. [PMP](https://www.pmi.org/) 美国项目管理工程师协会认证，全球认可，做项目管理的一定要学习。和国内软考的信息系统项目管理师考试雷同，考个国内的也可以，国外贵，单易考。
		1. [图书][项目管理知识体系指南（PMBOK指南：第5版）](http://product.dangdang.com/23256884.html)
		1. [图书][西游记PMP备考奇书](http://product.dangdang.com/23639808.html)
		1. [图书][汪博士解读PMP考试](http://product.dangdang.com/25229379.html)
	1. 敏捷开发
		1. [图书][Scrum实战——敏捷软件项目管理与开发](http://product.dangdang.com/25294242.html)
	1. [ISO](https://www.iso.org)
1. ### 产品
	1. [Axure](https://www.axure.com)
	1. 	[人人都是产品经理](http://www.woshipm.com)
1. ### 其他
	1. 源码学习
		1. [Github](https://github.com) 全球最大的程序员交友网，也说全球最大的同性交友网站^-^。
		1. [Maven仓库](https://mvnrepository.com) 方便查找库应用。
		1. [Apache](http://apache.org) 很多著名的开源项目在里面，比如Tomcat Hadoop Maven等。
		1. [SourceForge](http://www.sourceforge.net) 很多开源库也放在这里，特别是没有github之前。
	1. 规范
		1. [W3C](https://www.w3.org)	
	1. 综合
		1. [CSDN](http://www.csdn.net) 中国最大的程序员网站。
		1. [InfoQ](http://www.infoq.com) 架构师网站。
		1. [ChinaUnix](http://www.chinaunix.net) 中国最大的Linux/Unix技术社区网站。
		1. [博客园](https://www.cnblogs.com) 博客园是一个面向开发者的知识分享社区。
		1. [http://www.iteye.com](http://www.iteye.com)
	1. 资料
		1. [Slideshare](https://www.slideshare.net) 技术ppt下载。
	1. 技术博客
		1. [阿里中间件团队博客](http://jm.taobao.org)
		1. [美团技术团队](https://tech.meituan.com)
		1. [网易乐得技术团队](http://tech.lede.com)
	1. 视频
		1. [极客学院](http://www.jikexueyuan.com)
		1. [网易云课堂](http://study.163.com)
		1. [YouTube](http://youtube.com)
		1. [吴恩达机器学习](http://study.163.com/course/introduction/1004570029.htm)
       1. [传智播客](http://www.itcast.cn)
		1. [网易公开课的可汗学院](https://open.163.com/khan) Khan讲的太好，牛人，佩服。
	1. QCon
		1. [QCon上海2016幻灯片](https://github.com/QConChina/QConShanghai2016)
	1. 翻译
		1. [Google翻译](https://translate.google.cn)
		1. [有道](http://youdao.com)
	1. 名人
		1. 李刚 我是买过[疯狂Android讲义](http://product.dangdang.com/23699102.html) 感觉挺适合新手入门的，推荐一下。
		1. 马士兵 我看过其Java视频，讲的不错，推荐一下。
	1. 图书
		1. [图书][决战618：探秘京东技术取胜之道（全彩）](http://product.dangdang.com/25173863.html)
		1. [图书][黑客与画家](http://product.dangdang.com/21049598.html)
		1. 	[图书][SEO实战密码——60天网站流量提高20倍](http://product.dangdang.com/23738363.html)
		1. [图书][点石成金](http://product.dangdang.com/23611791.html)
		1. [图书][用户体验要素：以用户为中心的产品设计](http://product.dangdang.com/21110580.html)
		1. [图书][设计之下——搜狐新闻客户端的用户体验设计（全彩）](http://product.dangdang.com/23409934.html)
		1. [图书][数学之美](http://product.dangdang.com/23594870.html)
	1. 其他
		1. [GNU](https://www.gnu.org/home.en.html)
		1. [Stack Overflow.com](https://stackoverflow.com) 问答网。
		1. [在线JSON校验格式化工具bejson](http://www.bejson.com)
		1. [GitHub][成为一名专业程序员](https://github.com/stanzhai/be-a-professional-programmer) 成为专业程序员路上用到的各种优秀资料、神器及框架。
	
## 关于我们

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
		1. [ActiveMQ](http://activemq.apache.org) 看过，后来也忘了。
		1. [Nutch](http://nutch.apache.org) 研究过代码，学习Hadoop和搜索引擎的可以看看。
		1. [Netty](https://netty.io) 看过DEMO，没仔细研究过。
		1. [Linux](https://www.linux.org) 我的终结结论就是一句话，就是一切都是逻辑。
	2. 论文
		1. [一种哈希表快速查找的改进方法](http://www.wanfangdata.com.cn/details/detail.do?_type=perio&id=jsjgcykx200809021)
		2. [基于贝叶斯方法和信息指纹的博客评论过滤](http://www.wanfangdata.com.cn/details/detail.do?_type=perio&id=jsjgcyyy200824048)
	3. 项目
		1. GitHub地址：[https://github.com/xianglesong](https://github.com/xianglesong) 
	4. 视频
		1. [享乐颂网易云课堂课程](http://study.163.com/provider/825396/course.htm)
		1. [Java宝典--实战及解析[推荐]](http://study.163.com/course/courseMain.htm?courseId=1005801006) 本文配套更新视频讲解及资料等。

1. ### 特别推荐
	1. #### `享乐颂官方网站 ` [http://www.xianglesong.com](http://www.xianglesong.com)
		1. 学习是一种习惯。
		1. 我们的口号是  省时 省心 省力 省钱。
		1. 官方网站提供部分内容讲解，帮助快速学习掌握技术。
		
	1. #### `QQ群:` 557373922(申请加入，请告诉我从哪里看到的，谢谢！)
	   1. 联系 rulinma#qq.com 替换#为@
1. ### 贡献
	1. 欢迎大家Fork、Star和贡献。 




