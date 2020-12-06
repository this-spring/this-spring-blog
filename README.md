<!--
 * @Author: xiuquanxu
 * @Company: kaochong
 * @Date: 2020-11-04 23:49:12
 * @LastEditors: xiuquanxu
 * @LastEditTime: 2020-12-06 10:52:17
-->
# xuxiuquan个人简历

## 个人简介  

- 姓名：徐秀全
- 性别：男
- 毕业院校：东北石油大学
- 专业：软件工程
- 学历：本科  
- 毕业时间：2018-07
- 现居北京
- 1995年生人
- 手机号：17801171929
- 邮箱：1312543912@qq.com
- vx: txty01150815

## 目前状态  

在职  

## 专业技能  

- 精通使用 Html5、CSS3、ES6 和原生 JS。
- 精通使用 H5+。
- 熟练使用 Webassembly
- 熟练使用 Electron
- 熟练使用 Ts
- 熟练使用 WebGl
- 熟练使用 Flutter
- 熟练使用 vue、vue-router、vuex
- 熟练使用 Node
- 熟悉 Flv、HLS，Fmp4 视频格式
- 熟悉 MSE，流媒体开发。
- 熟练运用各种自动化构建工具（Webpack, Gulp）
- 熟练使用 git 分布式管理控制器 
- 具有一定c开发能力
- 了解微前端、webcomponents
- 开发过微信小程序
- 具有一定后台开发能力  

## 个人学习记录  

- <a href="https://github.com/this-spring">github</a>  
- <a href="https://www.zhihu.com/people/txspring">知乎</a>

### 工作经历

- 2018-09 - 至今: 考虫  研发工程师
- 2017-12 - 2018-9: 迅雷网心科技  前端开发工程师

## 项目

### 考虫web端播放器研发  

- 项目意义：web端播放器研发为了满足考虫学生在web端观看直播和回放的需求而研发。  

- 项目描述：基于自研协议，采用ProtoBuf作为数据传输格式，音频采用opus，视频采用h264。工作流程为：web端收到opus后利用Webassmebly把opus->pcm->aac->fmp4，生成fmp4后发送给业务层播放。在视频方案上采用指令模式，指令都是通过自研协议解析出来的。根据音频播放进度展示对应指令。  
目前web端支持：老师出镜，屏幕分享，语音连麦以及划线写字等功能。所有功能全部是本人自己编写（包括c模块的视频编解码，生成Webassmebly，webworker、webgl性能优化等）。   

- 技术栈：Webassmebly + C + Vue-Cli + Ts + WebGl  

- 主要职责：  
 1)整体项目架构设计。  
 2)项目从0-1的开发。  
 3)优化项目。   

### 考虫window和mac教室客户端研发  

- 项目描述：KCTeacher研发目的是为了满足老师教学需求。 

- 项目描述：架构设计由于历史原因上采用Electron负责UI层的展示以及交互，Java层负责数据发送和中转，C++层负责音视频等数据采集。发送和接受数据同样采用自研协议。 
- 技术栈：Electron + Vue + Ts + WebGl + Java + C++ 

- 主要职责：  
 1)整体项目架构设计。  
 2)项目UI层研发。  
 3)pdf部分的c++拓展研发。   

### 迅雷p2p下载H5SDK  
- 项目意义：实现web端p2p下载视频数据功能，充分开发利用玩客云资源  
- 项目描述：通过迅雷网心的玩客云实现数据存储，通过调度接口请求可用的节点建立wss链接进行并发下载，通过还原算法（具体名字有点记不清了）还原出源文件实现p2p下载，利用 nodejs 、ES6和asm.js
实现视频流解析，转成 FMP4，利用 MSE 技术碎片化喂给 video 标签，实现直播业务。  
项目架构：Nodejs +ES6 +Gulp 。项目整体使用使用 nodejs 和原生 JS 中的 Buffer模块进行实时视频流解析，
使用 WS 进行数据传递，利用 MSE 实现视频播放。   
- 技术栈：asm.js + ES6 + gulp
- 主要职责：  
 1)整体项目架构设计。  
 2)传输层代码编写。  
 3)优化代码。   
 4)hls方案的实现

## 最近学习  

- vue源码  
- 汇编语言基于x86处理器
- 刷LeetCode  
- 斯坦福CS143编译器课程  

## 自我评价  
1．喜欢接触新鲜事物，为人诚恳勤奋好学，喜欢脚踏实地，积极进取，勇于挑战。  
2．悟性高，团队意识强，善于与人沟通。  
2．具有一定的大型项目开发经验。    

## 个人爱好

- 热爱编程，对前端，编译器，Ai特别感兴趣  
- 喜欢深入研究底层
- 平时娱乐爬山，LOL，打球
