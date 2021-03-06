# JavaThings - Java安全漫谈笔记相关

《Java安全漫谈》是我在写的一点Java学习相关的随笔，不是很严谨，也不是啥高科技。这个Repository主要是记录并整理一下，附加一些代码。

## Java安全漫谈目录

- [Java安全漫谈 - 01.Java的动态特性——反射](https://t.zsxq.com/iyJiAMJ)
- [Java安全漫谈 - 02.反射的简单利用](https://t.zsxq.com/iIa2B2j)
- [Java安全漫谈 - 03.反射的几个进阶技巧](https://t.zsxq.com/MNRbayr)
- [Java安全漫谈 - 04.RMI的通信过程分析](https://t.zsxq.com/FMJiUrV)
- [Java安全漫谈 - 05.利用codebase攻击RMI Registry](https://t.zsxq.com/BuFy3zF)
- [Java安全漫谈 - 06.深入理解RMI协议与序列化对象](https://t.zsxq.com/vZjaiuR)
- [Java安全漫谈 - 07.不同语言中的反序列化漏洞](https://t.zsxq.com/NF2NfQf)
- [Java安全漫谈 - 08.认识最简单的Gadget——URLDNS](https://t.zsxq.com/ieMZBQj)
- [Java安全漫谈 - 09.初识CommonsCollections](https://t.zsxq.com/BmIIAy3)
- [Java安全漫谈 - 10.用TransformedMap编写真正的POC](https://t.zsxq.com/ZNZrJMZ)
- [Java安全漫谈 - 11.LazyMap详解](https://t.zsxq.com/FufUf2B)
- [Java安全漫谈 - 12.简化版CommonsCollections6](https://t.zsxq.com/A2j2beE)
- [Java安全漫谈 - 番外篇1. BCEL ClassLoader去哪了？](https://www.leavesongs.com/PENETRATION/where-is-bcel-classloader.html)
- [Java安全漫谈 - 13.Java中动态加载字节码的那些方法](https://t.zsxq.com/E2VfUVB)

## Demo代码

- 我简化的[CommonCollections6](deserialization/src/main/java/com/govuln/CommonsCollections6.java)，更方便大家理解
- 远程字节码加载Demo：[HelloClassLoader](general/src/main/java/com/govuln/HelloClassLoader.java)
- 系统默认defineClass加载字节码Demo：[HelloDefineClass](general/src/main/java/com/govuln/HelloDefineClass.java)
- 使用TemplatesImpl加载字节码Demo：[HelloTemplatesImpl](general/src/main/java/com/govuln/HelloTemplatesImpl.java)
- 使用BCEL加载字节码Demo：[HelloBCEL](general/src/main/java/com/govuln/HelloBCEL.java)
