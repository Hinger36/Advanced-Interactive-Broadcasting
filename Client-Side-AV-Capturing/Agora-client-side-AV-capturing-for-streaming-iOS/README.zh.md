# Agora client side AV capturing for streaming iOS


*Read this in other languages: [English](README.md)*

这个开源示例项目演示了如何从 Agora 视频 SDK 获取音视频裸数据，以便用来进行其他操作。

在这个示例项目中包含了以下功能：

- 加入通话和离开通话；
- 从 Agora 视频 SDK 获取音视频裸数据；
- 处理音视频裸数据并且把数据回传到 Objective-C 代码层；

你可以在这里查看Agora视频SDK的入门示例项目：[Agora-iOS-Tutorial-Swift-1to1](https://github.com/AgoraIO/Basic-Video-Call/tree/master/One-to-One-Video/Agora-iOS-Tutorial-Swift-1to1)

你也可以查看 Android 平台的示例项目：

- [Agora-client-side-AV-capturing-for-streaming-Android](https://github.com/AgoraIO/Advanced-Interactive-Broadcasting/tree/master/Client-Side-AV-Capturing/Agora-client-side-AV-capturing-for-streaming-Android)

## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。将 AppID 填写进 KeyCenter.swift

```
static let AppId: String = "Your App ID"
```

然后在 [Agora.io SDK](https://www.agora.io/cn/blog/download/) 下载 **视频通话 + 直播 SDK**，解压后将其中的 **libs/AgoraRtcEngineKit.framework** 复制到本项目的 “Agora-client-side-AV-capturing-for-streaming-iOS” 文件夹下。

最后使用 XCode 打开 Agora-client-side-AV-capturing-for-streaming-iOS.xcodeproj，连接 iPhone／iPad 测试设备，设置有效的开发者签名后即可运行。

## 运行环境
* XCode 10.0+
* iOS 真机设备
* 不支持模拟器

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题，你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题，可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持，你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的bug，欢迎提交 [issue](https://github.com/AgoraIO/Advanced-Interactive-Broadcasting/issues)

## 代码许可

The MIT License (MIT).
