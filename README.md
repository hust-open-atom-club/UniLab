# UniLab
Unified Lab Framework， 一个统一实验框架。

## 一、项目背景

没啥背景，就是给各种奇奇怪怪的实验适配不同的输出格式不同的CI要求搞麻了，所以，遵照“大一统”之原则，设计一个统一的实验评测框架，**以求输出同文，运行同轨，天下之实验皆可由同一套评测系统实现评测。**自此之后实验设计者可全身心设计习题，而不必考虑评测方式的实现，可以通过本框架快速产出计算机教育所需的各类配套实验。

## 二、项目目标（暂定）

**目标一：规定统一的数据输出接口 （模块），确保所有输出数据按照统一的，可明确区分内容的格式输出。**

**目标二：设计一完善的输出处理与分析模块，针对输出信息进行分析，从中提取分数，报错等信息，生成完善的实验报告信息，反馈给使用者。**

**目标三：考虑不同实验所需的不同编译与运行环境，设计一集成编译模块以兼容各类编译环境（支持在本模块内配置编译配置文件与编译信息）**

**目标四：设计一习题储存模块与展示模块，支持按照规定格式添加/删除习题，支持对习题进行显示（rustlings可为本模块设计的一个参考）**

**目标五：应当支持GitHub，Gitee等平台的流水线评测与Linux/windows的本地评测。**



