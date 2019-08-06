JAVA Study
==

# Table of contents

* [day01](./day01/README.md "day01")
* [day02](./day02/README.md "day02")
* [day03](./day03/README.md "day03")
* [day04](./day04/README.md "day04")
* [day05](./day05/README.md "day05")
* [day06](./day06/README.md "day06")
* [day07](./day07/README.md "day07")
* [day08](./day08/README.md "day08")
* [day09_高级类特性1](./day09/README.md "day09")
* [day10_高级类特性2](./day10/README.md "day10")
* [day11_异常处理](./day11/README.md "day11")
* [day12_异常处理](./day12/README.md "day12")
* [day13_java 集合](./day13/README.md "day13")
* [day14_泛型](./day14/README.md "泛型")
* [day15_IO流](./day15/README.md "IO流")
* [day16](./day16/README.md "")


<details>
<summary>day17_多线程</summary>

* [day17_多线程](./day17/README.md "多线程")
    * [程序、进程、线程概念](./day17/README.md#程序、进程、线程概念)
    * 多线程使用场景(./day17/README.md)
        * 多线程的创建和启动
    * Thread类(./day17/README.md)
        * [创建线程(类)的两种方法](./day17/README.md#创建线程类的两种方法)
            * [继承Thread类](./day17/README.md#继承Thread类)
            * [实现Runnable接口](./day17/README.md#实现Runnable接口)
         * [继承Thread方式和实现Runnable方法的联系与区别](./day17/README.md#继承Thread方式和实现Runnable方法的联系与区别)
         * [Thread构造器](./day17/README.md#Thread构造器)
         * [Thread常用方法](./day17/README.md#Thread常用方法)
    * [线程的调度](./day17/README.md#线程的调度)
    * [线程的优先级](./day17/README.md#线程的优先级)
    * [使用多线程的优点](./day17/README.md#使用多线程的优点)
    * [线程的分类](./day17/README.md#线程的分类)
        * 守护线程
        * 用户线程
    * [线程的生命周期](./day17/README.md#线程的生命周期)
    * [线程的同步](./day17/README.md#线程的同步)
    * [synchronized线程同步使用方法](./day17/README.md#synchronized线程同步使用方法)
    * [synchronized线程同步机制的两种实现方式](./day17/README.md#synchronized线程同步机制的两种实现方式)
        * 同步代码块
        * 同步方法
    * [互斥锁](./day17/README.md#互斥锁)
    * [懒汉式单例模式线程安全问题修复](./day17/README.md#懒汉式单例模式线程安全问题修复)
    * [释放锁的操作](./day17/README.md#释放锁的操作)
    * [不会释放锁的操作](./day17/README.md#不会释放锁的操作)
    * [线程的死锁问题](./day17/README.md#线程的死锁问题)
    * [线程通信](./day17/README.md#线程通信)
        * 线程通信示例
        * 线程通信应用示例(生产者/消费者问题)
</details>


<details>
<summary>day18_java常用类</summary>

* [day18_java常用类](./day18/README.md "java常用类")
    * [String类](./day18/README.md#String类)
        * 字符串的特性
        * String类的构造器
        * String方法
        * 字符串与基本数据类型、包装类之间转换
        * 字符串与字节数组的相互转换
        * 字符串与字符数组的相互转换
    * [StringBuffer类](./day18/README.md#StringBuffer类)
        * 特点
        * 构造器
        * StringBuffer方法
    * [StringBuilder类](./day18/README.md#StringBuilder类)
        * String、StringBuffer、StringBuilder特点比较
    * 与时间相关的类
        * System.currentTimeMillis();
        * Date：java.util.Date、java.sql.Date
        * SimpleDateFormat
        * Calendar
    * [主要时间标准](./day18/README.md#主要时间标准)
    * [System类的System.currentTimeMillis()方法](./day18/README.md#system类的systemcurrenttimemillis方法)
    * [Date类](./day18/README.md#Date类)
    * [SimpleDateFormat类](./day18/README.md#SimpleDateFormat类)
    * [Calendar类](./day18/README.md#Calendar类)
    * [Math类](./day18/README.md#Math类)
    * [BigInteger类](./day18/README.md#BigInteger类)
    * [BigDecimal类](./day18/README.md#BigDecimal类)
</details>


<details>
<summary>day19_java反射机制</summary>

* [day19_java反射机制](./day19/README.md "java反射机制")
    * [java reflection](./day19/README.md#java-reflection)
        * 反射机制提供的功能
        * 反射相关的主要API
        * Class类主要方法
        * 反射示例
        * 获取类的Class实例的4种方法
        * 示例
    * [JAVA类加载过程](./day19/README.md#JAVA类加载过程)
        * ClassLoader
        *  类加载器一个主要方法
    * [通过反射调用类的完整结构](./day19/README.md#通过反射调用类的完整结构)
        * 获取实现的接口
        * 获取所继承的父类
        * 获取全部的构造器
        * 获取全部的方法
        * 获取全部的属性(Field)
        * 获取注解(Annotation)
        * 泛型相关
        * 获取类所在的包
        * 获取内部类
        * 数字形式修饰符转String修饰符
        * 示例
    * [通过反射调用类中指定的方法、属性、构造器](./day19/README.md#通过反射调用类中指定的方法、属性、构造器)
        * 调用指定的方法
        * 调用指定的属性
        * 调用指定的构造器
    * [JAVA动态代理](./day19/README.md#JAVA动态代理)
        * 静态代理示例
        * 动态代理示例
    * [动态代理与AOP(Aspect Orient Programming面向切面编程)](./day19/README.md#动态代理与aopaspect-orient-programming面向切面编程)
        * AOP代理示例
    
        
</details>


<details>
<summary>day20_网络编程</summary>

* [day20_网络编程](./day20/README.md "网络编程")
    * [网络编程概述](./day20/README.md#网络编程概述)
    * [通讯要素](./day20/README.md#网络基础)
        * IP和端口
            * InetAddress类(IP地址)、InetSocketAddress(IP、端口)
        * 网络通信协议
    * [TCP socket网络编程](./day20/README.md#基于Socket的TCP编程)
        * ServerSocket类
        * Socket类
        * [TCP socket示例](./day20/README.md#TCP-socket示例)
    * [UDP socket网络编程](./day20/README.md#基于socket的UDP编程)
        * DatagramSocket类
        * DatagramPacket类
    * [URL socket网络编程](./day20/README.md#URL编程)
        * URL类
        * URLConnection类
        * HttpURLConnection类

</details>

* [enmu枚举类](./README/枚举类.md "enmu枚举类")
* [注解](./README/注解.md "注解")


* other
    * [安装JDK](./README/install_JDK.md "安装JDK")  
    * [clone或一个新的Interlij IDE项目到本地如何正常运行](./README/Interlij_IDE_open_new_clone_project.md "clone或一个新的Interlij IDE项目到本地如何正常运行")
    * [IntelliJ IDEA的安装、配置与使用](README/images/other/IntelliJ_IDEA的安装、配置与使用.pdf)
    * [JUnit单元测试--IntelliJ IDEA](./README/JUnit_IntelliJ_IDEA.md)
    * [如何编译和运行包含package的java源文件](./README/Compile_and_run_a_contain_package.md)
    * [jdk 1.8 api document](./README/java_resources.md)
    * [java方法区以及static的内存分配图](./README/java方法区以及static的内存分配图.md)
    * [URI、URL、URN联系与区别](./README/URI_URL_URN.md)
