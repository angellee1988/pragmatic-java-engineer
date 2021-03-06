# Java工程师修炼之道

目前互联网行业如火如荼，进入这个行业的技术人员也越来越多。对于研发来说，从工程角度主要分为：前端工程师、客户端工程师（又分为iOS和Android工程师）、后端工程师、算法工程师等职位。本书所说的Java工程师指的是以Java做为主要开发语言的后端工程师。

从2008年还未毕业时做一些小的项目至今做后端开发已经有差不多十年时间。经历过刚学Java时的迷茫，第一次写出Java程序时的激动，第一次写出一个Web系统的醍醐灌顶，一直到接触到Java更底层的东西，对Java有了一个系统的认识，对后端技术体系有了一个宏观的感受。这期间，用过各式各样的编程语言，尝试过各种开源软件，挖过各种坑，也填过各种坑。就单单针对后端的技术来说，自己的这些知识体系，还是觉得是有一定价值的。

此外，还记得笔者毕业后进入第一家公司时，入职培训的课程对于自己来说虽然不难，但确实让自己有种恍然大悟的感觉。业界的最佳实践和自己在学校里学到的、使用到的差别还是非常大的。直到后来加入当前的这家公司，做过一系列后端技术的培训课程，并且在校招的笔试和面试过程中，深刻体会到了学校中的知识与业界脱节之严重，在平时的社招中也遇到很多对后端技术缺乏系统性认识、技能点不足的工程师们，也经常被人问起如何学习Java后端技术。于是就打算写一下目前后端工程师一些比较主流前沿的技术以及实际工作中会用到的一些技能并串联起来，给刚上大学以后打算以Java后端为职业的学生、刚毕业入职的应届生以及初学者们一些入门的指引，避免走一些弯路，也给一些有经验的工程师们提供一个参考手册将零散的知识点串起来，减少在解决某些实际问题时无头绪搜索带来的时间成本，同时也是对自己的一个阶段性总结和查漏补缺。需要注意的一点是，像数据结构、计算机网络等计算机科学基础知识以及JavaSE基本用法，笔者认为是从事程序开发工作的Java工程师应该必备的知识点，因此并不包括在内。

本书会针对Java后端开发工作中经常用到的关键技能点去做阐述，会尽量覆盖在实际工作中需要的所有技能点。但由于很多技能点并非一两篇文章就能讲述完成的，本书仅仅是做一些实践性的经验总结和阐述，更加详细和深入地学习则需要参考专门的书籍或者官方文档。因此，如果是对内容深度有要求的读者，那么本书并不适合。

本书的大部分内容都来自笔者的博客以及平时工作、学习中的一些自我总结和笔记，记录了笔者进入这个行业以来的一些经验教训和思考，也是自己平时工作时会经常查阅的参考手册。

## 读者对象

- 未入门或者刚入门的Java工程师

    包括未来以Java后端开发为职业方向的在校学生、刚毕业入职的Java工程师以及未形成知识体系的Java工程师。通过阅读本书能够对Java工程师的必备技能有一个全局的认识，逐步形成自己的Java技术体系。
    
- 有经验的Java工程师

    有经验的Java工程师可以通过此书查漏补缺，巩固自己的开发技能，进一步加强自身的Java技术体系。
    
- 对Java后端开发感兴趣的非Java工程师

    非Java工程师可以通过此书了解Java工程师的技能体系，尤其对于其他语言的后端工程师来说，本书的很多内容也是通用的，并不局限于Java开发。

## 内容概览

- 第一章 后端技术导言

    本章主要从总体上描述后端技术的概念、组成、作用、需要的知识点，并给出了学习后端技术的建议。

- 第二章 Java项目工程化

    本章主要讲述Java项目工程化需要掌握的软件、技能等。

- 第三章 开发框架

    本章主要讲述Java后端开发中的一些主流框架的使用。
    
- 第四章 Spring

    本章主要讲述Spring核心、数据操作以及一些常用组件的使用。

- 第五章 数据存储

    本章主要讲述Java应用中数据存储上使用的一些软件、服务等。

- 第六章 数据通信

    本章主要讲述Java应用中数据传输、通信上使用的一些软件、服务等。

- 第七章 Java编程进阶

    本章主要介绍一些Java开发中的高级特性以及在Java开发中非常流行的类库。

- 第八章 性能调优

    本章主要讲述如何对Java应用的性能进行分析和调优，并给出了开发建议。
    
- 第九章 安全技术

    本章主要对Java开发中常用的加密技术、HTTP以及防范各种攻击的方案做了阐述。

## 参考资料

在写作本书以及平时的工作中，笔者阅读、参考过很多书籍，以下是其中具有代表性的。对于本书讲述不够深入的地方，可以参考这些书籍进一步的学习。

- 《Effective Java（第2版）》：此书讲解了Java的一些高级特性和技巧。

- 《Java并发编程实战》：此书是并发编程经典书籍，涵盖了并发编程的各种知识点以及相关理论知识。
    
- 《七周七并发模式》：此书讲述了主流的几种并发编程模式。
    
- 《深入理解Java虚拟机：JVM高级特性与最佳实践（第2版）》：此书讲解了JVM的内存、GC、字节码、编译器等高级特性和优化实践。 
	
- 《高性能MySQL（第3版）》：此书讲述了MySQL各种优化技巧，并结合原理给予讲解。

- 《Redis开发与运维》：此书在原理层面对于Redis的使用优化做了详尽的描述。

- 《深入分布式缓存》：此书涵盖了分布式原理、各种缓存软件/框架的使用以及缓存在各大公司的典型实践。

- 《深入理解Elasticsearch（原书第2版）》：此书讲述了对ES的使用、原理和优化技巧。

- 《Java性能权威指南》：此书是Java性能调优的权威书籍，几乎涵盖了Java调优的方方面面。
	
- 《构建高性能Web站点》：此书从各种案例触发，讲解了高性能Web站点需要的各种优化技巧、实践经验等。
	
- 《白帽子讲Web安全》：本书基本涵盖了方方面面的Web安全技术，包括客户端安全、服务端安全等。
    
- 《分布式系统：概念与设计（原书第5版）》：分布式系统理论的经典书籍，全面介绍了分布式系统的原理、体系结构、算法和设计。

- 《Clean Architecture》: Uncle Bob的架构经典书籍，梳理了架构的定义、目的、架构设计原则等，是架构入门的好书。

虽然以上书籍都是非常实用的参考资料，但就笔者自己来看，更为推崇的则是直接通过相关技术的官方文档来学习，既能够段炼自己的英文阅读能力，也能够直面相关技术的第一手文档，避免了在看相关书籍时被一些偶然的纰漏所误导。

需要注意的是这里面的《Effective Java》（第三版英文版已经面世）和《Java并发编程实战》两本书都是基于Java的旧版本来写的，但是其讲述的很多东西并不过时，尤其是JDK底层源码、设计理论、优化思想等仍然适用于现在的Java开发。

此外，笔者的学习、工作笔记是平时工作中查阅网上资料并经过辨伪后记录下来的零散知识点，难免会有一些对网上零散资料的引用，特别对这些资料的原创者表示感谢，如果有侵权请联系我。

## 勘误和支持

在这本书的写作过程中，自己一直是战战兢兢的，一直害怕写成那种侃侃而谈却没有实质内容的东西或者给予读者一些误导信息，因此对于每一个写出来的知识点，自己都是在查阅官方文档以及其他权威资料并在自己思考之后才敢于落笔。但由于笔者知识能力有限，难免有错误。

如果在阅读过程中发现错误的地方，请提交到此网址：<https://github.com/superhj1987/pragmatic-java-engineer/issues>。

![](images/issues.jpg)

同时，请随时注意勘误信息的发布：<https://github.com/superhj1987/pragmatic-java-engineer/wiki/Mistakes>。

![](images/mistakes.jpg)

## 致谢

由于工作以及个人身体等方面的原因，中间数次延期，历时一年多才完成本书。因此首先要特别感谢我的父母和妻子，在我写作此书的过程中给予了非常大的后勤支持和鼓励，让我能够专心地完成写作。

同时要感谢中华万年历的同事们在平时的工作中给了我很多启发和思路，感谢公司的设计总监张喜亮抽出时间帮我修饰了一些图片；尤其要感谢CEO孙建在写作此书的过程中给予了我充分的信任和支持。

还要感谢我的前同事，也是我刚毕业时的工作导师尧飘海，在百忙之中审阅并给此书写序；也要感谢前同事张小川、阙杭宁和好友秦绪震、饶洵抽出宝贵时间校对了此书并给出了宝贵的建议。

最后，感谢电子工业出版社永恒的侠少找到我出版此书，并允许我一次次延期。也感谢付睿编辑的辛苦校对和修改，让本书得以顺利出版。

也把此书献给我刚出生的女儿 - 依依。

## 联系方式

邮箱：superhj1987@126.com

博客：http://rowkey.me

微博：http://weibo.com/superhj1987
