# proj88-OpenHarmonyOS-Local-AIGC-APP
### 项目名称
基于OpenHarmony操作系统，构建离线多模态大模型APP。要求大模型能够输入、分析、理解文字、音频、视频、图片等多媒体数据，并生成、输出文字、音频、视频、图片等多媒体数据。



### 项目描述

OpenHarmony原生支持MindSpore AI框架，同时在OpenHarmony社区也有开发者成功移植了pytorch的C库libtorch。因此当前OpenHarmony操作系统已经具备了初步的本地AI模型开发和运行能力。

但是目前社区上并没有丰富的应用AI生态，且目前接入OpenHarmony操作系统的AI服务均为在线服务。即大模型部署在云端，Openharmony终端仅部署一个UI界面，使用调用接口的方式请求云端服务器接口数据。

本实验的目标是在OpenHarmony本地部署一个生成式大模型，围绕大模型构建多模态服务，开发一个大模型APP。



### 所属赛道

2024全国大学生操作系统比赛的“OS功能设计”赛道



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

* 用户能够通过UI界面输入文字、音频、视频、图片等多媒体数据。

* 大模型可以正确处理用户的输入，并生成对应的输出。

* 用户能够通过UI界面得到大模型生成的文字、音频、视频、图片等多媒体数据。

  

### 文档
* 硬件平台：Openharmony移动端设备（RISC-V硬件优先）
* 软件平台：OpenHarmony4及以上版本的操作系统、相关开发环境
* openharmony技术文档：https://gitee.com/openharmony
* openharmony快速开始文档：https://gitee.com/openharmony/docs/blob/master/zh-cn/device-dev/quick-start/Readme-CN.md

### License

* [Apache-2.0](https://opensource.org/licenses/Apache-2.0)



## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

### 第一题：高效性
使用推理加速框架、硬件加速技术，提高大模型的生成速度。

### 第二题：可扩展性
设计可扩展的框架，便于后续新增其它大模型、功能函数、插件等。

### 第三题：基于大模型的系统操作

将大模型的输出对接OpenHarmony的系统操作，为用户提供一种新的操作系统使用方法。
