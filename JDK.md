## 安装JDK

- 下载各个版本的jdk，安装

  jdk17下载：https://www.oracle.com/java/technologies/downloads/#jdk17-windows
  jdk1.8下载：https://www.oracle.com/java/technologies/downloads/#java8-windows

  
## 配置环境变量

- 删Path变量

  在安装JDK的时候，JDK会给我们的Path变量添加 变量，安装一次，就会生成一条这样的变量，那就把他们都删掉

   C:\Program Files\Common Files\Oracle\Java\javapath
   C:\Program Files (x86)\Common Files\Oracle\Java\javapath

- 给Path添加变量

  %JAVA_HOME%\bin
  %JAVA_HOME%\jre\bin

- 创建系统变量

  CLASSPATH=.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar

  JAVA_HOME=%JAVA_HOME17% 或者 %JAVA_HOME8%

  JAVA_HOME17=C:\Program Files\Java\jdk-17.0.5  或者自己安装的jdk17路径

  JAVA_HOME8=C:\Program Files\Java\jdk1.8.0_291 或者自己安装的jdk1.8路径

- 切换版本

  修改JAVA_HOME为对应的版本即可

- 