# HongGuo 红果短剧 Mac 客户端 v0.8.1

**播放源修复 · macOS 14+ · Apple Silicon（M 系列）· 155.0 MiB**

**[⬇ 下载 Mac 安装包](https://github.com/junmo-zy/hongguo-mac/releases/download/v0.8.1/HongGuo-Mac-0.8.1-arm64.dmg)** · [安装与完整说明](https://github.com/junmo-zy/hongguo-mac#三步安装) · [界面截图](https://github.com/junmo-zy/hongguo-mac#界面截图)

## 本次更新

- **恢复播放与下载**：修复旧播放接口返回空响应、无法获取视频的问题，更新在线播放和离线下载共用的取流请求。
- **保持最高可用画质**：实测恢复 1080p 播放，保留手动清晰度切换、切集、预加载、续播和下载续传。每集提供的画质以实际片源为准。
- **保留现有体验**：经典、映幕、青序三套深浅主题与 SwiftUI 原生结构保持不变，继续支持独立播放器、离线剧库和 MP4 导出合并。

## 安装与更新

下载 `.dmg`，完全退出旧版，将 **HongGuo.app** 拖入 **Applications / 应用程序**并替换，再从应用程序启动。本机收藏、观看记录、下载及设置继续保留。

已内置 Python、Java 及所需组件。当前安装包仅支持 Apple Silicon Mac；GitHub 自动生成的 `Source code` 压缩包不是 Mac 安装包。应用采用临时签名，尚未经过 Apple 公证，详见[安装说明](https://github.com/junmo-zy/hongguo-mac#安装说明)。

## 验证与使用说明

2026-10-17 在 Apple Silicon / macOS 26.6.2 上通过四组自动化回归，覆盖真实 1080p 出画、清晰度切换、切集与续播、边播放边下载、离线播放、MP4 导出与无损合并、失败切集回退、兼容转码和防休眠。安装包签名、镜像完整性和安装启动检查通过。

完整搜索接口不可用时仍回退到官网结果；单集评论目前可能只返回数量而没有正文。AirPlay 本次仅验证接口，未验证接收端投放。片源可用性取决于上游服务。

取流请求字段参考 [hongguoTV 的近期播放修复](https://github.com/bimoshuxinghe/hongguoTV/commit/0815d5ec47ddab1353f85c85167b0ac47ef92ae9)，本项目独立实现适配。组件来源与许可证继续保留在应用包内。

[免责声明与权利说明](https://github.com/junmo-zy/hongguo-mac/blob/main/DISCLAIMER.md)
