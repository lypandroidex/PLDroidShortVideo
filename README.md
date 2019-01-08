# PLDroidShortVideo

PLDroidShortVideo 是七牛推出的一款适用于 Android 平台的短视频 SDK，提供了包括美颜、滤镜、水印、断点录制、分段回删、视频编辑、混音特效、本地/云端存储在内的多种功能，支持高度定制以及二次开发。

# 1. 功能列表

短视频 SDK 的功能，主要分为 3 大块：拍摄、编辑、上传。

## 1.1 拍摄功能

| 功能点                          | 版本       | 备注       |
| ---------------------------- | -------- | -------------- |
| 摄像头采集                        | 1.0.0(+) | 无 |
| 麦克风采集                        | 1.0.0(+) | 无 |
| 静音功能                         | 1.0.0(+) | 无 |
| 实时美颜                         | 1.0.0(+) | 无 |
| 贴纸特效                         | 1.0.0(+) | 无 |
| 大眼/瘦脸                        | 1.0.0(+) | 无 |
| 闪光灯开关                        | 1.0.0(+) | 无 |
| 第三方美颜接口                      | 1.0.0(+) | 无 |
| 第三方滤镜接口                      | 1.0.0(+) | 无 |
| 自定义拍摄时长                      | 1.0.0(+) | 无 |
| 自定义分辨率                       | 1.0.0(+) | 无 |
| 自定义视频帧率                      | 1.0.0(+) | 无 |
| 自定义视频码率                      | 1.0.0(+) | 无 |
| 支持 1:1 正方形录制                 | 1.0.0(+) | 无 |
| 断点拍摄（多段录制）                   | 1.0.0(+) | 无 |
| 回删视频                         | 1.0.0(+) | 无 |
| H.264 硬编                     | 1.0.0(+) | 无 |
| AAC 硬编                       | 1.0.0(+) | 无 |
| 输出 mp4 文件                    | 1.0.0(+) | 无 |
| 支持 armeabi，armv7, arm64, x86 | 1.0.0(+) | 无 |
| 实时滤镜                         | 1.0.1(+) | 无 |
| 实时水印                         | 1.0.1(+) | 无 |
| 手动对焦                         | 1.0.1(+) | 无 |
| 自动对焦                         | 1.0.1(+) | 无 |
| 曝光调节                         | 1.1.0(+) | 无 |
| 屏幕录制                         | 1.2.0(+) | 无 |
| 横屏拍摄                         | 1.3.0(+) | 无 |
| 倍数拍摄                         | 1.4.0(+) | 无 |
| 视频拼接                         | 1.5.0(+) | 无 |
| 摄像头变焦                        | 1.5.1(+) | 无 |
| AR 特效拍摄                        | 1.7.0(+) | 需要额外收费 |
| 纯音频拍摄                        | 1.7.0(+) | 无 |
| H.264 软编                      | 1.8.0(+) | 无 |
| AAC 软编                        | 1.8.0(+) | 无 |
| 草稿功能                         | 1.8.0(+) | 无 |
| View 录制                       | 1.11.0(+) | 无 |
| 分段变速录制                     | 1.12.0(+) | 无 |
| 实时获取录制时长                  | 1.14.0(+) | 无 |
| 录制时背景音乐不变速               | 1.14.0(+) | 无 |
| 外部音视频数据导入                 | 1.15.0(+) | 无 |

## 1.2 视频编辑功能

### 1.2.1 视频剪辑

| 功能点    | 版本       |
| ------ | -------- |
| 关键帧预览  | 1.1.0(+) |
| 非关键帧预览 | 1.2.1(+) |
| 剪辑指定区间 | 1.1.0(+) |
| 截取封面   | 1.1.0(+) |
| 快速剪辑模式 | 1.7.0(+) |

### 1.2.2 视频特效

| 功能点   | 版本       | 备注            |
| ----- | -------- | ------------- |
| 滤镜    | 1.0.0(+) | 无             |
| 水印    | 1.0.0(+) | 无             |
| 贴纸特效  | 1.0.0(+) | 基于面部识别，需要额外付费 |
| 大眼/瘦脸 | 1.0.0(+) | 基于面部识别，需要额外付费 |
| 文字特效  | 1.6.0(+) | 无             |
| MV 特效  | 1.6.0(+) | 无             |
| 变速     | 1.8.0(+) | 无             |
| 静态贴图  | 1.9.0(+) | 无             |
| 涂鸦     | 1.9.0(+) | 无             |
| 抖音特效  | 1.9.0(+) | 需要额外付费    |
| 分段特效  | 1.11.0(+) | 无           |
| 分段变速  | 1.16.0(+) | 无           |

### 1.2.3 音频特效

| 功能点        | 版本       |
| ---------- | -------- |
| 音频混合       | 1.1.0(+) |
| 截取音频片段     | 1.1.0(+) |
| 调节原声/背景声音量 | 1.1.0(+) |
| 配音         | 1.8.0(+) |
| 多重音频混合  | 1.16.1(+) |

### 1.2.4 视频合成

| 功能点       | 版本       |
| --------- | -------- |
| 片头片尾 MV   | 1.5.0(+) |
| 多个视频拼接    | 1.5.0(+) |
| 制作 GIF 封面 | 1.3.0(+) |
| 图片合成 MP4   | 1.6.0(+) |
| 制作过场字幕   | 1.10.0(+) |
| 从视频导出 GIF 动图 | 1.16.0(+) |
| 图片，视频，GIF 混合拼接 | 1.16.0(+) |

### 1.2.5 视频转码

| 功能点  | 版本       |
| ---- | -------- |
| 画面剪裁 | 1.1.0(+) |
| 码率变换 | 1.1.0(+) |
| 时光倒流 | 1.7.0(+) |
| 降帧率转码 | 1.13.0(+) |
| 区域裁剪转码 | 1.13.0(+) |

## 1.3 上传功能

| 功能点  | 版本       |
| ---- | -------- |
| 上传云端 | 1.0.1(+) |
| 断点续传 | 1.0.1(+) |

## 2. 设备以及系统要求

- 设备要求：搭载 Android 系统的设备
- 系统要求：Android 4.3(API 18) 及其以上

## 3. 使用方法

请参考开发者中心文档：[PLDroidShortVideo 文档](https://developer.qiniu.com/pili/sdk/3734/short-video-android-sdk)

## 4. 声明

本短视频 SDK 需授权方可使用，可通过 400-808-9176 转 2 号线联系七牛商务咨询，或者 [通过工单](https://support.qiniu.com/?ref=developer.qiniu.com) 联系七牛的技术支持。

## 5. 反馈及意见

当你遇到任何问题时，可以通过在 GitHub 的 repo 提交 issues 来反馈问题，请尽可能的描述清楚遇到的问题，如果有错误信息也一同附带，并且在 Labels 中指明类型为 bug 或者其他。

[通过这里查看已有的 issues 和提交 Bug](https://github.com/pili-engineering/PLDroidShortVideo/issues)
