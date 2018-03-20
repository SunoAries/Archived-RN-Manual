<<<<<<< HEAD
# BONC移动开发平台文档
Ares是BONC移动开发框架，在此基础上，只需调用相关api，即可构建面向不同业务的移动应用

## 技术栈

前端技术栈为React、React-Redux、React--Native-Router-Flux、Native-Base

## 功能

* 安全登录登出
* 请求加密
* 版本检测
* 应用安装与卸载
* 聊天功能
* 下载模块
* 用户管理
* 数据持久化

##  项目搭建

1.  Java环境+安卓环境
2.  npm install
3.  react-native run-android/run-ios


## 项目目录

```
├─api
├─components    #自定义组件
│  ├─app
│  ├─checkbox
│  ├─expand
│  ├─friend
│  ├─group
│  ├─image
│  ├─infoItem
│  ├─input
│  ├─logo
│  ├─menu
│  ├─message
│  ├─modalBox
│  ├─org
│  ├─portalModal
│  ├─tab
│  ├─titleBar
│  └─toast
│      └─image
├─frame         #redux全局状态管理
│  ├─actions
│  ├─reducers
│  ├─state
│  ├─store
│  └─style
├─native        #原生模块
│  ├─aresNative
│  └─ui
├─resources
│  └─img
├─util         #rn工具函数
└─views        #rn业务代码
    ├─appDetail
    ├─appStore
    ├─assets
    │  └─contacts
    ├─contacts
    ├─contactsDetail
    ├─createGroupOne
    ├─createGroupTwo
    ├─groupDetail
    ├─login       #登录页面
    ├─main
    ├─note
    ├─platform    #native-base UI组件使用示例
    │  ├─boot
    │  ├─screens
    │  │  ├─actionsheet
    │  │  ├─anatomy
    │  │  ├─badge
    │  │  ├─button
    │  │  ├─card
    │  │  ├─checkbox
     ..................
     ..................
    ├─push
    ├─splash        
    ├─user
    ├─userSetting   #用户管理页面
    └─webview       #调用webview页面
```

##  

