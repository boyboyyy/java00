# c&c++

- 1972年c的诞生
- 优点：贴近硬件，运行极快，效率极高
- 当时操作系统，编译器，数据库，网络系统主要的编译语言
- 缺点：指针和内存管理容易出错

- 1982年c++诞生
- 面向对象，兼容c,

# JAVA

java开发许多的平台，系统，工具

- 构造工具L:Ant,Maven,jekins
- 应用服务器：Tomcat ,jetty,jboss,**websphere,weblogic**。Eckspase
- Web开发：Struts,spring.Hibernate，mybatis
- 开发工具;Eclipse,Netbean,**intellij idea**,Jbuilder
- 。。。
- 2006:Hadoop（大数据邻域）
- Android(手机端)

## java特点

- 简单性：易于学习

- 面向对象：对象与对象的接口上，模拟人的思维贴切人

- 可移植性：可跨平台进行编写写一次到处运行

- 高性能：效率不断的提高

- 分布式，动态性，安全性，健壮性，多线程性

  ## javad的三大版本

  - javaSE:标准用于（桌面程序，控制台开发）/ /工作需要可以先学

  - javaME:嵌入式开发（手机，小家电）
  - jacaEE:E企业级开发（web端，服务器开发）
  - JDK包含JRE和JVM,
  - JRE是开发的环境，其中就包括了java虚拟机
  - JDK又包含了JRE；

  ## java开发环境

  JDK的下载地址[点击跳转]([Java 归档下载 - Java SE 8 (oracle.com)](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html))
  
  ![image-20230304022511684](../../AppData/Roaming/Typora/typora-user-images/image-20230304022511684.png)
  
  建议下载8U192，新的版本只是不断的更新一些内容，了解即可。
  
  我的电脑window10 x64为例，故我下载。
  
  ![image-20230304022559402](../../AppData/Roaming/Typora/typora-user-images/image-20230304022559402.png)
  
  下载需要签订流氓条约和注册账号即可下载。
  
  ## 卸载JDK
  
  - 将jdk软件删除
  - 进入我的电脑空白处右键–>点击属性–>高级系统设置—>环境变量–>java_home删除
  
  ![image-20230303230421449](../../AppData/Roaming/Typora/typora-user-images/image-20230303230421449.png)
  
  双击path环境中所有含java的都删除即可

## 配置环境变量

进入我的电脑空白处右键–>点击属性–>高级系统设置—>环境变量—>![image-20230303235342623](../../AppData/Roaming/Typora/typora-user-images/image-20230303235342623.png)

选择新建

![image-20230304022931371](../../AppData/Roaming/Typora/typora-user-images/image-20230304022931371.png)

变量名为路径日后将进行访问的名字

变量值是下载JDK的地址

确定后，双击**系统变量**中path的环境变量，新建两个环境变量如下图

![image-20230304024127153](../../AppData/Roaming/Typora/typora-user-images/image-20230304024127153.png)

按确认后，环境变量即可配置完成。window+R    cmd    进入命令窗口后输入：java空格键减号健version回车即可。如下图即完成

![image-20230304024203376](../../AppData/Roaming/Typora/typora-user-images/image-20230304024203376.png)
