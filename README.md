
## 2019年最新总结，阿里，腾讯，百度，美团，头条等技术面试题目，以及答案，专家出题人分析汇总。持续更新中。

* [阿里篇](#1)
* [mysql篇](#2)
* [redis篇](#3)
* [MongDB篇](#4)
* [Zookeeper篇](#5)
* [nginx篇](#6)
* [算法篇](#7)
* [内存篇](#8)
* [cpu篇](#9)
* [磁盘篇](#10)
* [网络通信篇](#11)
* [安全篇](#12)
* [并发篇](#13)
* [华为篇](#14)
* [百度篇](#15)
* [腾讯篇](#16)
* [美团篇](#17)
* [头条篇](#18)
* [滴滴篇](#19)
* [京东篇](#20)

<h3 id="1">阿里篇</h3> 

---

##### 1.1.1 如何实现一个高效的单向链表逆序输出？

##### 1.1.2 已知sqrt(2)约等于1.414，要求不用数学库，求sqrt(2)精确到小数点后10位

##### 1.1.3 给定一个二叉搜索树(BST)，找到树中第 K 小的节点

##### 1.1.4 LRU缓存机制

##### 1.1.5 关于epoll和select的区别，以下哪些说法是正确的

##### 1.1.6 从innodb的索引结构分析，为什么索引的 key 长度不能太长

##### 1.1.7 MySQL的数据如何恢复到任意时间点？

##### 1.1.8 NFS 和 SMB 是最常见的两种 NAS（Network Attached Storage）协议，当把一个文件系统同时通过 NFS 和 SMB 协议共享给多个主机访问时，以下哪些说法是错误的

##### 1.1.9 输入 ping IP 后敲回车，发包前会发生什么？

##### 1.2.0 请解释下为什么鹿晗发布恋情的时候，微博系统会崩溃，如何解决？

##### 1.2.1 现有一批邮件需要发送给订阅顾客，且有一个集群（集群的节点数不定，会动态扩容缩容）来负责具体的邮件发送任务，如何让系统尽快地完成发送？

##### 1.2.2 有一批气象观测站，现需要获取这些站点的观测数据，并存储到 Hive 中。但是气象局只提供了 api 查询，每次只能查询单个观测点。那么如果能够方便快速地获取到所有的观测点的数据？

##### 1.2.3 如何实现两金额数据相加（最多小数点两位）

##### 1.2.4 关于并行计算的一些基础开放问题

##### 1.2.5 请计算XILINX公司VU9P芯片的算力相当于多少TOPS，给出计算过程与公式

##### 1.2.6 一颗现代处理器，每秒大概可以执行多少条简单的MOV指令，有哪些主要的影响因素

##### 1.2.7 请分析 MaxCompute 产品与分布式技术的关系、当前大数据计算平台类产品的市场现状和发展趋势

##### 1.2.8 对大数据平台中的元数据管理是怎么理解的，元数据收集管理体系是怎么样的，会对大数据应用有什么样的影响

##### 1.2.9 你理解常见如阿里，和友商大数据平台的技术体系差异以及发展趋势和技术瓶颈，在存储和计算两个方面进行概述

##### 1.3.0 在云计算大数据处理场景中，每天运行着成千上万的任务，每个任务都要进行 IO 读写。存储系统为了更好的服务，经常会保证高优先级的任务优先执行。当多个作业或用户访问存储系统时,如何保证优先级和公平性

##### 1.3.1 最大频率栈

##### 1.3.2 给定一个链表，删除链表的倒数第N个节点，并且返回链表的头结点

##### 1.3.3 如果让你设计一个通用的、支持各种数据库秒级备份和恢复的系统，你会如何设计

##### 1.3.4 如果让你来设计一个支持数据库、NOSQL 和大数据之间数据实时流动的数据流及处理的系统，你会考虑哪些问题？如何设计？

##### 1.3.5 给定一个整数数组和一个整数，返回两个数组的索引，这两个索引指向的数字的加和等于指定的整数。需要最优的算法，分析算法的空间和时间复杂度

##### 1.3.6 假如给你一个新产品，你将从哪些方面来保障它的质量？

##### 1.3.7 请评估一下程序的执行结果？

<br>

<h3 id="2">mysql篇</h3> 

---

##### 2.1.0 主键 超键 候选键 外键

##### 2.1.1 数据库事务的四个特性及含义

##### 2.1.2 视图的作用，视图可以更改么？

##### 2.1.3 drop,delete与truncate的区别

##### 2.1.4 索引的工作原理及其种类

##### 2.1.5 连接的种类

##### 2.1.6 数据库范式

##### 2.1.7 数据库优化的思路

##### 2.1.8 存储过程与触发器的区别


<br>


<h3 id="3">redis篇</h3> 

---
##### 3.1.0 使用Redis有哪些好处？

##### 3.1.1 redis相比memcached有哪些优势？

##### 3.1.2 redis常见性能问题和解决方案

##### 3.1.3 MySQL里有2000w数据，redis中只存20w的数据，如何保证redis中的数据都是热点数据

##### 3.1.4 Memcache与Redis的区别都有哪些？

##### 3.1.5 Redis 常见的性能问题都有哪些？如何解决？

##### 3.1.6 redis 最适合的场景

##### [3.1.7 Redis的同步机制了解么？](https://github.com/0voice/interview_internal_reference/blob/master/3.1.7%20Redis%E7%9A%84%E5%90%8C%E6%AD%A5%E6%9C%BA%E5%88%B6%E4%BA%86%E8%A7%A3%E4%B9%88%EF%BC%9F.md)

##### 3.1.8 是否使用过Redis集群，集群的原理是什么？

##### 3.1.9 redis集群如何保证一致性？


<br>

<h3 id="4">MongDB篇</h3> 

---
##### 4.1.0 什么是MongoDB？

##### 4.1.1 MongoDB是由哪种语言写的？

##### 4.1.2 MongoDB的优势有哪些？

##### 4.1.3 什么是数据库？

##### 4.1.4 什么是集合？

##### 4.1.5 什么是文档？

##### 4.1.6 MongoDB和关系型数据库术语对比图

##### 4.1.7 什么是“mongod”？

##### 4.1.8 “mongod”参数有什么？

##### 4.1.9 什么是"mongo"？

##### 4.2.0 MongoDB哪个命令可以切换数据库？

##### 4.2.1 什么是非关系型数据库？

##### 4.2.2 非关系型数据库有哪些类型？

##### 4.2.3 为什么用MOngoDB？

##### 4.2.4 在哪些场景使用MongoDB？

##### 4.2.5 MongoDB中的命名空间是什么意思?

##### 4.2.6 哪些语言支持MongoDB?

##### 4.2.7 在MongoDB中如何创建一个新的数据库？

##### 4.2.8 在MongoDB中如何查看数据库列表？

##### 4.2.9 MongoDB中的分片是什么意思？

##### 4.3.0 如何查看使用MongoDB的连接？

##### 4.3.1 什么是复制？

##### 4.3.2 在MongoDB中如何在集合中插入一个文档？

##### 4.3.3 在MongoDB中如何除去一个数据库？

##### 4.3.4 在MongoDB中如何创建一个集合？

##### 4.3.5 在MongoDB中如何查看一个已经创建的集合？

##### 4.3.6 在MongoDB中如何删除一个集合？

##### 4.3.7 为什么要在MongoDB中使用分析器？

##### 4.3.8 MongoDB支持主键外键关系吗？

##### 4.3.9 MongoDB支持哪些数据类型？

##### 4.4.0 为什么要在MongoDB中用"Code"数据类型？

##### 4.4.1 为什么要在MongoDB中用"Regular Expression"数据类型？

##### 4.4.2 为什么在MongoDB中使用"Object ID"数据类型？

##### 4.4.3 如何在集合中插入一个文档？

##### 4.4.4 “ObjectID”有哪些部分组成？

##### 4.4.5 在MongoDb中什么是索引？

##### 4.4.6 如何添加索引？

##### 4.4.7 MongoDB有哪些可替代产品？

##### 4.4.8 如何查询集合中的文档？

##### 4.4.9 用什么方法可以格式化输出结果？

##### 4.5.0 如何使用"AND"或"OR"条件循环查询集合中的文档？

##### 4.5.1 在MongoDB中如何更新数据？

##### 4.5.2 如何删除文档？

##### 4.5.3 在MongoDB中如何排序？

##### 4.5.4 什么是聚合？

##### 4.5.5 在MongoDB中什么是副本集？

##### 4.5.6 Mongodb存储特性与内部原理?


<br>

<h3 id="5">Zookeeper篇</h3> 

---
##### 5.1.0 zookeeper是什么？

##### 5.1.1 zookeeper提供了什么？

##### 5.1.2 zookeeper文件系统

##### 5.1.3 zookeeper的四种类型的znode

##### 5.1.4 zookeeper通知机制

##### 5.1.5 zookeeper有哪些应用场景？

##### 5.1.6 zk的命名服务

##### 5.1.7 zk的配置管理服务

##### 5.1.8 zk的集群管理

##### 5.1.9 zk的分布式锁

##### 5.2.0 zk队列管理

##### 5.2.1 zk数据复制

##### 5.2.2 zk的工作原理

##### 5.2.3 zk是如何保证事物的顺序一致性

##### 5.2.4 zk集群下server工作状态

##### 5.2.5 zk是如何选举Leader的？

##### 5.2.6 zk同步流程

##### 5.2.7 分布式通知和协调


<br>

<h3 id="6">nginx篇</h3> 

---
##### 6.1.0 请解释一下什么是Nginx?

##### 6.1.1 请列举Nginx的一些特性?

##### 6.1.2 请列举Nginx和Apache 之间的不同点?

##### 6.1.3 请解释Nginx如何处理HTTP请求。

##### 6.1.4 在Nginx中，如何使用未定义的服务器名称来阻止处理请求?

##### 6.1.5 使用“反向代理服务器”的优点是什么?

##### 6.1.6 请列举Nginx服务器的最佳用途。

##### 6.1.7 请解释Nginx服务器上的Master和Worker进程分别是什么?

##### 6.1.8 请解释你如何通过不同于80的端口开启Nginx?

##### 6.1.9  请解释是否有可能将Nginx的错误替换为502错误、503?

##### 6.2.0 在Nginx中，解释如何在URL中保留双斜线?

##### 6.2.1 请解释ngx_http_upstream_module的作用是什么?

##### 6.2.2 请解释什么是C10K问题，后来是怎么解决的？

##### 6.2.3 请陈述stub_status和sub_filter指令的作用是什么?

##### 6.2.4 解释Nginx是否支持将请求压缩到上游?

##### 6.2.5 解释如何在Nginx中获得当前的时间?

##### 6.2.6 用Nginx服务器解释-s的目的是什么?

##### 6.2.7 解释如何在Nginx服务器上添加模块?

##### 6.2.8 nginx中多个work进程是如何监听同一个端口的？如何处理客户连接的惊群问题？

##### 6.2.9 nginx程序的热更新是如何做的？


<br/>
<br/>

**获取大牛视频资料，专家架构交流3群：783153655**

**若群已满，添加QQ：469254771 , 备注github**

**关注公众号，更多权威架构设计方案。 另附企业内推，架构设计资料，相关视频资料**

<img src = "arch.jpg" />




