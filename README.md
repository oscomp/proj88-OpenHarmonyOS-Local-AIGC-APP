# proj88-openHarmonyOS-Cross-Device-Control
### 项目名称
基于openHarmony操作系统，为操作系统添加一个跨设备互联接口，并使用openharmony的跨设备互联能力与自己构建的接口实现一个跨设备应用。



### 项目描述

openHarmony中提供了远程调用接口和数据库互联功能，但是二者在直接的使用上并不能完美应对所有的功能需求。

目前提供的功能如下：跨设备传递调用Ability信息，跨设备数据库互通。但是没有实现跨设备的功能信息传递（A设备上直接通过某个API向B设备发送某种Ability内的控制信号）。

本实验的目标是在openHarmony上面实现新的远端调用接口，实现外部功能的传递api，从而完成跨设备互联接口，该接口的实现方式不限（包括但不限于系统能力、开发库）。



### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

中科院软件所 郑森文

* gitee [isrc_ohos](https://gitee.com/iscas-ohos)

* email senwen@iscas.ac.cn

  

### 难度

中等



### 特征 

* 添加功能后的openharmonyOS可以提供如下API：供多设备功能信息流的传递，使其提供外在接口，使得多设备之间可以直接传递功能信息。

* 使用设计好后的api设计一个完整的跨设备调用案例。

* 跨设备调用案例例如：大屏与手机的交互体验（优酷）；居家设备与手机的相互控制（九阳）。

  

### 文档
* 硬件平台：[Hi3861开发](https://gitee.com/openharmony/docs/blob/master/zh-cn/device-dev/quick-start/Hi3861开发板.md)、[Hi3516开发板](https://gitee.com/openharmony/docs/blob/master/zh-cn/device-dev/quick-start/Hi3516开发板.md)、[Hi3518开发板](https://gitee.com/openharmony/docs/blob/master/zh-cn/device-dev/quick-start/Hi3518开发板.md)、openharmony移动端设备
* 软件平台：openHarmony分布式操作系统、相关开发环境
* openharmony技术文档：https://gitee.com/openharmony
* openharmony快速开始文档：https://gitee.com/openharmony/docs/blob/master/zh-cn/device-dev/quick-start/Readme-CN.md
* openharmony开发、学习资源：https://gitee.com/isrc_ohos/ultimate-harmony-reference

### License

* [Apache-2.0](https://opensource.org/licenses/Apache-2.0)



## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题：多端调用
在多端使用openharmony的前提下确保应用可以多端调用功能

### 第二题：功能信息传递
设计合适的算法逻辑，借用数据库互通和远端调用Ability来实现功能信号的传递

### 第三题

实现时可适当考虑调用性能、可维护性
设计合适的算法，以保障功能信息传递的时效性和延迟。

### 第四题

制作一个简单的demo应用程序来演示相关功能。