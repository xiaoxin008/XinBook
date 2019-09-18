# Java & JVM 简介

## 技术体系

### 按功能划分

* JDK（Java Development Kit）：是Java程序设计语言，Java虚拟机，Java API类库三者的统称，是用于支持Java程序开发的最小环境

* JRE（Java Runtime Environ）：可以把Java API类库中的JavaSE API子集和Java虚拟机这两部分统称为JRE，JRE是支持Java程序运行的标准环境

  ![Java技术体系所包含的内容](img/introduction.png)

### 按技术所服务的领域划分

* Java Card：支持一些小程序运行在小内存设备上的平台
* Java ME（Micro Edition）：移动终端应用，又称J2ME
* Java SE （Standard Edition）：PC端应用，又称J2SE
* Java EE（Enterprise Edition）：企业级应用，又称J2EE

## Java发展史

* 1991年4月，Java语言前身Oak(橡树)诞生
* 1995年5月23日，Oak语言改名为Java 版本1.0
* 1996年1月23日，JDK1.0发布，包括：Java虚拟机、Applet、AWT等
* 1997年2月19日，JDK1.1发布，包括：JAR文件格式、JDBC、JavaBeans、RMI、反射、内部类
* 1998年12月4日，JDK1.2发布（Palyground）竞技场，包括：J2SE、J2EE、J2ME、EJB、Swing
* 2000年5月8日，JDK1.3发布（Kestrel）美洲红凖，包括：JNDI，Java2D
* 2002年2月13日，JDK1.4发布（Merlin）灰背凖，包括：正则表达式、异常链、NIO、日志类、XML解析器
* 2004年9月30日，JDK1.5发布（Tiger）老虎，包括：自动装箱、泛型、动态注解、枚举、可变长参数、foreach、java.util.concurrent包
* 2006年12月11日，JDK1.6发布（Mustang）野马，包括：动态语言支持、编译API、微型HTTP服务器API
* 2009年2月19日，JDK1.7发布（Dolphin）海豚，包括：新GI收集器、加强对非Java语言的调用支持、升级类加载架构
* 2014年3月18日，JDK1.8发布（Spider）蜘蛛，包括：Lambda表达式
* 2017年9月21日，JDK1.9发布，包括：Java平台模块化、jShell
* 2018年3月21日，JDK10.0发布
* 2018年9月25日，JDK11.0发布

## 虚拟机发展史

* sun classic/exact vm：世界上第一款商用Java虚拟机
* sun hotspot vm：Sun JDK和Open JDK中所带的虚拟机，使用范围最广
* sun mobile-embedded vm/meta-circular vm：移动端类虚拟机
* bea jrockit/ibm j9 vm
* azul vm/bea liquid vm
* apache harmony/google android dalvik vm
* microsoft jvm及其他
