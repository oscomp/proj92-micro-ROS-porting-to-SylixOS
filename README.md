# projx-micro-ROS-porting-to-SylixOS

### 项目描述

SylixOS 是中国人完全自主设计开发，内核开源的实时操作系统，支持ARM、X86、MIPS、RSIC-V等主流CPU架构和板卡。在国防、航空航天、电力、轨道交通、 工业自动化 等领域有着广泛的应用。

ROS（Robot Operating System）作为开源的机器人操作系统，在上层算法实现和生态方面具有优势，如果想将ROS用于工业机器人，实时性难以满足要求。

在基于 ROS 的机器人应用中，micro-ROS 用于连接资源受限的微控制器设备和拥有强大处理器设备。 micro-ROS 在各种嵌入式硬件上运行，使 ROS 更接近机器人硬件。

如果将micro-ROS移植到SylixOS运行，那么，将为工业机器人提供一种高实时性、低成本的解决方案，完全可以满足工业工业机器人实时性要求和工业领域快速开发产品的需求。

我们的目标是移植  micro-ROS到 SylixOS，能与其他设备上的ROS节点进行通信，模拟机器人操作指令或操控真实机器人。

- 移植  micro-ROS 到 SylixOS 
- 模拟机器人操作或操控机器人

### 源码

 [libcextern.git](http://git.sylixos.com/cgit/cgit.cgi/libcextern.git/) 

 [libsylixos.git](http://git.sylixos.com/cgit/cgit.cgi/libsylixos.git/) 

 [micro-ROS](https://micro.ros.org/)



### 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）、研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

陈洪邦

* github [edward518](https://github.com/edward518)

* email chenhongbang@acoinfo.com

  

### 难度

中等

### 特征

- 支持 micro-ROS 


### 文档

[micro-ROS 参考文档](https://micro.ros.org/docs/tutorials/core/overview/)

[SylixOS 参考文件](https://github.com/acoinfo/sylixos_oscomp_2021)

### License

- Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标



### 第一题：移植 micro-ROS 到 SylixOS 

* 移植 micro-ROS 到 SylixOS 操作系统，能与其他设备上的ROS节点进行通信

* 移植 micro-ROS 相关组件

  

### 第二题：模拟机器人操作或操控机器人

* 完成与其他设备上ROS 节点之间的数据传输
* micro-ROS 节点设备接收数据并执行或模拟执行机器人操作

  
