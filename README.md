**为什么要搞“中台”**
--
  “中台”是对传统“软件平台”的升级和加强，通过在企业层面引入新的专业化职能分工、数据唯一性建模等规则；在解决软件行业“重复造轮子”问题的基础上，进一步解决了传统“软件平台”未能解决的“软件平台间职能边界划分问题”及“数据孤岛问题”。根据业务发展情况，由业务中台、技术中台以及数据中台组成，目标是要做到功能多、接入快、体验好、省钱省成本。<br>
![中台形象图](./中台形象图.webp)


<details>
  <summary>目录列表</summary>
<!-- TOC -->
- [技术中台：](#技术中台)
  - [客户端SDK](#客户端sdk)
        - [浏览器 SDK](#浏览器-sdk)
        - [自研IM SDK](#自研im-sdk)
        - [归因 SDK](#归因-sdk)
        - [日志 SDK](#日志-sdk)
        - [包校验 SDK](#包校验-sdk)
        - [实时上报 SDK](#实时上报-sdk)
        - [App 合规工具](#app-合规工具)
        - [用研 SDK](#用研-sdk)
        - [录屏 SDK](#录屏-sdk)
        - [用研 SDK](#用研-sdk-1)
        - [公共网络库](#公共网络库)
        - [Kibana指南](#kibana指南)
        - [ipa权限对比](#ipa权限对比)
  - [平台服务](#平台服务)
        - [低代码平台](#低代码平台)
        - [短信管理平台](#短信管理平台)
        - [可视化活动平台](#可视化活动平台)
        - [推送管理平台](#推送管理平台)
        - [设计中台](#设计中台)
<!-- TOC -->
  </details>

## 技术中台：

集中解决大部分业务重复造轮子的问题并整合提供最优的技术解决方案。

### 客户端SDK

###### 浏览器 SDK

> 基于业务需求和Jsbridge桥接的定制官方浏览器，兼容低版本laya游戏、控制台日志输出等
> 
> SDK名称：cli-webview_flutter<br>
> 仓库地址：https://github.com/olaola-chat/cli-webview_flutter.git<br>
> 负责同事：刘锡清、唐斌<br>



###### 自研IM SDK

> 一款自主技术研发的即时通讯开发工具集，涵盖WebSocket长连接、消息首发、本地信息存储等特
> 
> SDK名称：cli-bbim<br>
> 仓库地址：https://github.com/olaola-chat/cli-bbim.git <br>
> 负责同事：巫金生<br>



###### 归因 SDK

> 收集用户终端基础信息以及统计用户行为的关键流程
> 
> SDK名称：cli-bb_attr_report<br>
> 仓库地址：https://github.com/olaola-chat/cli-bb_attr_report.git<br>
> 负责同事：巫金生<br>



###### 日志 SDK

> 自研的日志采集工具，压缩优化生成日志体积，提供日志搜索平台
> 
> SDK名称：cli-bblog<br>
> 仓库地址： https://github.com/olaola-chat/cli-bblog.git <br>
> 负责同事：肖纳<br>



###### 包校验 SDK

> 通过验证码校验和签名校验可以防止App测试包对外泄漏
> 
> SDK名称：cli-debug_limit<br>
> 仓库地址： https://github.com/olaola-chat/cli-debug_limit.git<br>
> 负责同事：巫金生、唐斌<br>



###### 实时上报 SDK

> 一款自主技术研发的即时通讯开发工具集，涵盖WebSocket长连接、消息首发、本地信息存储等特
> 
> SDK名称：cli-statistics-flutter<br>
> 仓库地址：https://github.com/olaola-chat/cli-statistics-flutter.git <br>
> 负责同事：罗维樵、肖纳、刘锡清<br>



###### App 合规工具

> 用于App发版本前进行合规检测，包括敏感词检测、隐私分析、lint规则
> 
> SDK名称：cli-code-check<br>
> 仓库地址：https://github.com/olaola-chat/cli-code-check.git<br>
> 负责同事：罗维樵<br>



###### 用研 SDK

> 通过问卷、访谈等形式进行用户调研分析
> 
> SDK名称：cli-user_survey<br>
> 仓库地址：https://github.com/olaola-chat/cli-user_survey.git<br>
> 负责同事：唐斌<br>



###### 录屏 SDK

>基于腾讯lvb录屏推流的sdk，搭配用研SDK使用
>
> SDK名称：cli-lvb<br>
> 仓库地址：https://github.com/olaola-chat/cli-lvb.git<br>
> 负责同事：唐斌<br>



###### 用研 SDK

>一款自主技术研发的即时通讯开发工具集，涵盖WebSocket长连接、消息首发、本地信息存储等特
>
> SDK名称：cli-user_survey<br>
> 仓库地址：https://github.com/olaola-chat/cli-user_survey.git<br>
> 负责同事：唐斌<br>



###### 公共网络库

>基础的网络库，包括http、http2、rpcx、websocke等网络协议的封装
>
> SDK名称：cli-net-client<br>
> 仓库地址：https://github.com/olaola-chat/cli-net-client.git<br>
> 负责同事：肖纳、罗维樵<br>

###### Kibana指南

>教你如何使用Kibana配置业务方的表格
>
> SDK名称：cli-quickly-start-Kibana<br>
> 仓库地址：https://github.com/olaola-chat/cli-quickly-start-Kibana.git<br>
> 负责同事：唐斌<br>



###### ipa权限对比 

>教你如何使用Kibana配置业务方的表格
>
> SDK名称：cli-app_permission_statistics<br>
> 仓库地址：https://github.com/olaola-chat/cli-app_permission_statistics.git<br>
> 负责同事：唐斌<br>


### 平台服务

###### 低代码平台 

>通过低代码的方式快速配置运营活动、榜单等web页面<br>
>
> 仓库地址：https://bc-admin.iambanban.com/lesscode/guidlist/main<br>
> 负责同事：林宋梓、唐国鹏<br>



###### 短信管理平台 

>短信管理平台支持多个运营商灵活调配、保障有效触到率的同时降低使用成本<br>
>
> 仓库地址：https://bc-admin.iambanban.com/operate/sms/smsRecordLogs<br>
> 负责同事：熊宇<br>



###### 可视化活动平台 

>通过简单的配置可以即时预览当前活动效果，一键配置发到线上，提升运营效率<br>
>
> 仓库地址：https://bc-admin.iambanban.com/operate/activity/list<br>
> 负责同事：蔡文辟<br>



###### 推送管理平台 

>管理App的推送任务，包括推送策略，推送目标管理等等<br>
>
> 仓库地址：https://bc-admin.iambanban.com/operate/push/index<br>
> 负责同事：严文聪<br>



###### 设计中台 

>帮助设计师完成更多设计资源的管理工作<br>
>
> 仓库地址：https://bc-admin.iambanban.com/operate/push/index<br>
> 负责同事：林跃<br>
