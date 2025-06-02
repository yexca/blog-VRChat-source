---
title: Linux安装Unity2019.4.31f1
permalink: /archives/286.html
date: 2022-08-17 20:21:56
categories:
    - 其他教程
tags:
---

~~相信使用Linux了应该不会有网络问题了吧，中国版想必也差不多~~

## 下载Unity Hub

官网下载：[Download - Unity](https://unity3d.com/get-unity/download)

## 安装

假定下载后的文件`UnityHub.AppImage`在`~/downloads`

打开终端，依次输入以下命令

```bash
cd ~/downloads
chmod +x UnityHub.AppImage 
./UnityHub.AppImage unityhub://2019.4.31f1/bd5abf232a62
```

等待即可

## 运行Unity Hub

到`UnityHub.AppImage`所在目录，输入命令`./UnityHub.AppImage`即可

## 关于命令后缀来源

进入Unity发布页面[What's new in Unity 2022.1.0 - Unity](https://unity3d.com/unity/whats-new/2022.1.0)

右侧选择要安装的版本，以2019.4.31为例

左侧版本号下方有Install this version with [Unity Hub](unityhub://2019.4.31f1/bd5abf232a62).

复制蓝字`Unity Hub`指向的链接
