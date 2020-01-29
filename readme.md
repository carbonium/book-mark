
# 1.注释导入的问题
注释导入导出问题：
因为注释中有重叠部分，则导入时不能正常处理，比如重叠的两个红色、绿色的勾；
或者注释文字的修改。
###解决
在foxit 6.0.4版左边点击注释按钮；
之后，点开其中的第一页的第一个注释，选中；
之后隔几百页，再点开某一页的注释，按住shift同时选中这个注释，从而可以选中这几百页的所有注释（不要点展开所有注释，这样删除注释会异常缓慢！）；
之后按delete键，删除所有注释，再在这个版本中导入注释即可。
PS:foxit 6.0.4在我的百度云(book目录)里有。
# 2.修改pdf页面大小
工具：117Infix.exe  
菜单：文档，调整页面尺寸，选择自定义，单位为百分比（根据视觉大小，自定义缩放），
在修改时，为了不至于内存使用过大而卡死，
可以先修改第1~200页，点击保存，之后再修改201~406页，保存。

# 3.pdf收集
csdn、网盘搜索的网站

# 4.好书筛选
豆瓣读书、jd

# book list
```    
$ tree book/
book/
├── AI
│   ├── Deep_Learning.pdf
│   ├── Machine_Learning.pdf
│   ├── Machine_Learning_text.pdf
│   ├── pytorch-doc.pdf
│   ├── TensorFlow官方文档中文版v1.2.pdf
│   ├── TensorFlow技术解析与实战.pdf
│   ├── 白话深度学习与TensorFlow.pdf
│   ├── 大话数据挖掘.pdf
│   ├── 机器学习_周志华.pdf
│   ├── 机器学习导论_2.pdf
│   ├── 机器学习实战.pdf
│   ├── 机器学习实战_Code.rar
│   ├── 人工智能-一种现代的方法_3.pdf
│   ├── 深度学习入门之Pytorch.pdf
│   ├── 神经网络与机器学习_3.pdf
│   ├── 数据挖掘导论.pdf
│   ├── 斯坦福大学机器学习吴恩达讲义中文版.rar
│   ├── 统计学习方法_李航.pdf
│   ├── 图解机器学习.pdf
│   └── 写给程序员的数据挖掘实践指南.pdf
├── Algorithm
│   ├── AC_算法：C++语言实现(第1-4部分)基础知识、数据结构、排序及搜索_3.pdf
│   ├── AC_算法：C语言实现(第1-4部分)基础知识、数据结构、排序及搜索_3.pdf
│   ├── AD_算法导论_3.pdf
│   ├── AG_算法概论_1.pdf
│   ├── ALG_算法_4.pdf
│   ├── AY_算法引论：一种创造性方法_1.pdf
│   ├── CAFPL_C-C++常用算法手册_1.pdf
│   ├── C语言基本算法程序百例.pdf
│   ├── DSAA_数据结构与算法分析：C++描述_3.pdf
│   ├── DSAA_数据结构与算法分析：C语言描述_2.pdf
│   ├── DSAA_数据结构与算法分析：C语言描述_2_习题答案
│   │   ├── ch00.pdf
│   │   ├── ch01.pdf
│   │   ├── ch02.pdf
│   │   ├── ch03.pdf
│   │   ├── ch04.pdf
│   │   ├── ch05.pdf
│   │   ├── ch06.pdf
│   │   ├── ch07.pdf
│   │   ├── ch08.pdf
│   │   ├── ch09.pdf
│   │   ├── ch10.pdf
│   │   ├── ch11.pdf
│   │   └── ch12.pdf
│   ├── FDS_数据结构基础(C语言版)_2.PDF
│   ├── PWDS_大话数据结构_1.pdf
│   ├── 啊哈！算法_1.pdf
│   ├── 妙趣横生的算法(C语言实现)_1.pdf
│   ├── 数据结构(C语言版)_1.pdf
│   ├── 数据结构(C语言版)_1_习题解答.doc
│   ├── 数据结构(C语言版)_题集_1.pdf
│   └── 数据结构(C语言描述).DOC
├── BlockChain
│   ├── IBM系列课程_区块链和HyperLedger
│   │   ├── 简介.txt
│   │   ├── 区块链第八讲.pdf
│   │   ├── 区块链第二讲.pdf
│   │   ├── 区块链第六讲.pdf
│   │   ├── 区块链第七讲.pdf
│   │   ├── 区块链第三讲.pdf
│   │   ├── 区块链第四讲.pdf
│   │   ├── 区块链第五讲.pdf
│   │   └── 区块链第一讲.pdf
│   ├── 精通比特币_2.pdf
│   ├── 区块链原理、设计与应用.pdf
│   └── 深度探索区块链：Hyperledger技术与应用.pdf
├── C++
│   ├── AC++_Accelerated+C++中文_1.pdf
│   ├── ASTL_STL源码剖析_1.pdf
│   ├── BLDG_Boost程序库完全开发指南.pdf
│   ├── Boost程序库完全开发指南.pdf
│   ├── C++CIA_c++ concurrency in action.pdf
│   ├── C++P_C++Primer_4.pdf
│   ├── C++Primer_4_习题解答.pdf
│   ├── C++标准程序库_1.pdf
│   ├── C++标准库函数参考手册【c++官网】.chm
│   ├── CP_C语言程序设计_现代方法_2.pdf
│   ├── EC++_Effective C++_3.pdf
│   ├── ESTL_Effective STL：50条有效使用STL的经验_1.pdf
│   ├── ICOM_深度探索C++对象模型_1.pdf
│   ├── MEC++_More Effective C++_1.pdf
│   ├── others
│   │   ├── C++_____C++11_____《C++11新标准——学习笔记》.doc
│   │   └── C++string常用函数.docx
│   └── PP_编程珠玑_2.pdf
├── CV
│   ├── MATLAB R2014a完全自学一本通(上).pdf
│   ├── MATLAB R2014a完全自学一本通(下).pdf
│   ├── OpenCV3编程入门.pdf
│   ├── OpenCV3编程入门_Code.rar
│   ├── OpenCV3计算机视觉-Python语言实现_2.pdf
│   ├── Python计算机视觉编程.pdf
│   ├── 计算机视觉-一种现代方法_1.pdf
│   ├── 数字图像处理_2.pdf
│   ├── 数字图像处理的MATLAB实现_2.pdf
│   ├── 数字图像处理的MATLAB实现_2_Code.rar
│   ├── 数字图像处理的MATLAB实现_3.pdf
│   └── 学习OpenCV.pdf
├── DataBase
│   ├── DSC_数据库系统概念_6.pdf
│   ├── HPM_高性能MySQL_3.pdf
│   ├── MySQL_crashcourse_2012.pdf
│   ├── MySQL必知必会.pdf
│   ├── refman-5.7-en.a4.pdf
│   ├── RIA_Redis实战.pdf
│   ├── RSS_Redis设计与实现_2.pdf
│   └── 深入浅出MySQL++数据库开发、优化与管理维护_2.pdf
├── DesignPatterns
│   ├── ASD_敏捷软件开发：原则,模式与实践.pdf
│   ├── BTDP_大话设计模式_1.pdf
│   ├── DPE_设计模式解析_2.pdf
│   ├── GoF_en_设计模式-可复用面向对象软件的基础_1.pdf
│   ├── GoF_设计模式-可复用面向对象软件的基础_1.pdf
│   ├── HFDP_Head First设计模式_1.pdf
│   ├── MC++D_C++设计新思维泛型编程与设计模式之应用.pdf
│   ├── POSA_面向模式的软件体系结构-卷2-用于并发和网络化对象的模式_1.pdf
│   ├── TUML_大象：Thinking in UML_2.pdf
│   ├── UMLD_UML精粹：标准对象建模语言简明指南_3.pdf
│   └── ZDP_设计模式之禅_2.pdf
├── desktop.ini
├── Develop
│   ├── gdb手册(debuging_with_gdb).pdf
│   ├── LibeventBook.pdf
│   ├── libevent参考手册(中文版).pdf
│   ├── 跟我一起写Makefile_陈皓.pdf
│   └── 内存与常见内存错误.pdf
├── Go
│   ├── AGP_Go语言高级编程.pdf
│   ├── GCP_Go语言核心编程.pdf
│   ├── GIA_Go语言实战 .pdf
│   ├── GPL_Go程序设计语言.pdf
│   ├── GSN_Go语言学习笔记.pdf
│   └── 说明.md
├── Infix PDF Editor Pro v6.29.exe
├── Linux
│   ├── ILDD_深入Linux设备驱动程序内核机制_1.pdf
│   ├── LDD_Linux设备驱动程序_3.pdf
│   ├── TLPIv1_Linux-Unix系统编程手册（上)_1.pdf
│   ├── TLPIv2_Linux-Unix系统编程手册（下)_1.pdf
│   └── UULP_Unix-Linux编程实践教程_1.pdf
├── MongoDB
│   ├── MongoDB权威指南_2.pdf
│   └── MongoDB实战_2.pdf
├── Network
│   ├── Linux内核协议栈源码解析_1.pdf
│   ├── others
│   │   ├── linux协议栈.ppt
│   │   ├── Linux协议栈实现.doc
│   │   └── Linux协议栈实现分析.vsd
│   ├── TIIv1_TCP-IP详解卷1：协议_1.pdf
│   ├── TIIv2_TCP-IP详解卷2：实现_1.pdf
│   ├── TIIv3_TCP-IP详解卷3：TCP事务协议_1.pdf
│   ├── ULNI_深入理解Linux网络技术内幕_1.pdf
│   ├── UNPv1_Unix网络编程卷1：套接字联网API_3.pdf
│   ├── UNPv2_Unix网络编程卷2：进程间通信_2.pdf
│   ├── 图解HTTP_1.pdf
│   ├── 图解TCP-IP_5.pdf
│   ├── 图解网络硬件完整版_1.pdf
│   └── 追踪Linux TCP-IP代码运行--基于2.6内核_1.pdf
├── NLP
│   ├── ABNF语法开发指南.chm
│   ├── NLP汉语自然语言处理原理与实践.pdf
│   ├── python自然语言处理.pdf
│   ├── 科大讯飞ABNF文法规范.pdf
│   ├── 中文信息处理丛书_统计自然语言处理2.pdf
│   └── 自然语言处理综论_中文版.pdf
├── OS
│   ├── AL_汇编语言_2.pdf
│   ├── APUE_Unix环境高级编程_3.pdf
│   ├── CS_深入理解计算机系统_2.pdf
│   ├── CXYXY_程序员的自我修养--链接、装载与库.pdf
│   ├── JSJZC_计算机组成原理_唐朔飞_2.pdf
│   ├── LKD_Linux内核设计与实现_3.pdf
│   ├── LL_Linkers & Loaders.pdf
│   ├── LLch_链接器和加载器.pdf
│   ├── MOS_现代操作系统_3.pdf
│   ├── PLKA_深入Linux内核架构_1.pdf
│   ├── ULK_深入理解Linux内核_3.pdf
│   ├── 深入理解Linux内核_3_English.pdf
│   └── 现代体系结构上的UNIX系统.内核程序员的对称多处理和缓存技术.pdf
├── Script
│   ├── Linux命令行与Shell脚本编程大全_2.pdf
│   ├── Python编程_从入门到实践.pdf
│   ├── Python核心编程_2.pdf
│   ├── Python核心编程_3.pdf
│   ├── Python数据分析基础.pdf
│   └── Shell脚本学习指南_1.pdf
├── Server
│   ├── Kafka权威指南.pdf
│   ├── 从Paxos到Zookeeper  分布式一致性原理与实践.pdf
│   ├── 大规模分布式存储系统_原理解析与架构实战.pdf
│   ├── 大数据-互联网大规模数据挖掘与分布式处理_1.pdf
│   ├── 大型网站技术架构-核心原理与案例分析_1.pdf
│   ├── 分布式系统-概念与设计_5.pdf
│   ├── 分布式消息中间件实践 .pdf
│   ├── 深入分布式缓存_从原理到实践.pdf
│   ├── 深入理解：Nginx模块开发与架构解析.pdf
│   ├── 淘宝技术这十年_1.pdf
│   └── 微服务设计.pdf
├── tools
│   ├── FoxitReader_6.0.4.619.exe
│   ├── FSCapture_v8.4_截图.rar
│   └── Infix PDF Editor Pro v6.29.exe
└── Work
    ├── CIG_程序员代码面试指南_左程云.pdf
    ├── CPP_MS宝典.pdf
    ├── Google+C+++风格指南.chm
    ├── Google的C++编码规范.PDF
    ├── leetcode-cpp.pdf
    ├── 程序员MS金典_5.pdf
    ├── 剑指Or.pdf
    ├── 手写代码必备手册(C++版).pdf
    └── 腾讯C++编码规范.pdf

22 directories, 193 files

```
