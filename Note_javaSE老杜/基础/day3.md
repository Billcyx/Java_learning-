![[SE,EE and ME.png]]

JVM： （java虚拟机）
所有java程序都是在JVM运行的； 
JVM执行过程中再去操作内存； 
JVM是C++写的一个虚拟的电脑；
安装了JDK以后，JVM就安装好了

内存是什么：
程序运行当中的数据 *临时* 储存空间； 关机之后内存中的数据就消失了！（硬盘内的数据不会丢失）

java中的GC机制： 垃圾自动回收机制， 不容易导致内存泄漏。 （由JVM负责调动，程序员不需要干涉）； java吃完饭可以不洗碗，cpp要洗碗。。 缺点： 内存无法得到清理。

java的可移植性： 不需要任何改动，可以在很多系统上， 例如windows，macos or linuxI(原因就是虚拟机，不同系统的JVM是不一样的，是JVM和操作系统打交道，但java程序只需要和JVM打交道，所有java程序可以 无改动 移植)

JRE：java 运行环境（体积小，便捷安装）

java代码(.java)是普通文本，被称为“源代码“，编译就是 将 java代码 转化成 **字节码**（.class） ， JVM可以识别的是字节码; 也因此，编译和运行可以在不同的系统完成（在windows上编译形成字节码，然后字节码在linux上被jvm识别）； 需要注意的是，一个java源文件可以生成几个不同的字节码文件（.class）

字节码文件不是二进制文件（因为操作系统可以直接执行二进制，但字节码需要java虚拟机进一步解释； JVM翻译出来的才是二进制，然后经由operating system识别）

























