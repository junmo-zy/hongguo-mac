# HongGuo for macOS v0.8.0（非官方）

**macOS 14+ · Apple Silicon（M 系列）· 155.0 MiB**

**[⬇ 下载 Mac 安装包](https://github.com/junmo-zy/hongguo-mac/releases/download/v0.8.0/HongGuo-Mac-0.8.0-arm64.dmg)** · [安装与完整说明](https://github.com/junmo-zy/hongguo-mac#三步安装) · [全部界面截图](https://github.com/junmo-zy/hongguo-mac#界面截图)

## 本次更新

- **映幕与青序主题**：保留经典，新增两套视觉风格。首页、剧集卡片、详情和播放器保持 SwiftUI 原生结构，兼顾深浅外观。
- **离线下载与 MP4 导出**：支持范围选集、清晰度、暂停/续传、重试、目录迁移和索引修复；可分别导出或按集数无损合并。
- **播放与恢复**：下一集预加载单独控制；竖屏小窗、临时 2 倍速、暂停并隐藏、画面模式、防休眠、兼容转码，以及失败切集回退。
- **找剧与追更**：官网链接/ID、演员搜索、其他季候选、本机追更、推荐换一批、只读本集评论和正式版更新提醒。
- **文档与截图**：更新全部功能说明，重新拍摄 12 张最新版截图，展示三套主题及详情、播放器、分类和离线选集。

## 界面预览

| 青序 · 浅色 | 映幕 · 深色 |
| --- | --- |
| ![青序浅色](https://raw.githubusercontent.com/junmo-zy/hongguo-mac/v0.8.0/home-jade-light.png) | ![映幕深色](https://raw.githubusercontent.com/junmo-zy/hongguo-mac/v0.8.0/home-cinema-dark.png) |

## 安装与更新

下载 `.dmg`，退出旧版，把 **HongGuo.app** 拖入 Applications 并替换。本机收藏、观看记录和播放偏好继续保留，重要数据可先在设置导出备份。已内置运行环境，不必另装 Python 或 Java。`Source code` 压缩包不是安装包。

当前只提供 Apple Silicon 版本。应用采用临时签名，尚未经过 Apple 公证；若系统阻止打开，请核对来源后使用“隐私与安全性”中的系统打开入口，无需关闭系统安全防护。

## 验证与限制

已通过自动化回归、六种主题/外观设置页渲染与滚动、签名、DMG 与 SHA-256 校验；测试环境为 Apple Silicon / macOS 26.6.2。覆盖真实在线/离线播放、下载续传、MP4 导出合并、切集恢复与偏好记忆。

AirPlay 配置、接口及调用链已验证，但系统选择器显示与实际投放尚未确认；未完成其他系统版本和长时间耐久测试。账号登录、手机云同步、评论发布和会员体系尚未接入。内容可用性依赖第三方服务。

## 文件校验

`HongGuo-Mac-0.8.0-arm64.dmg` · 162,496,651 字节

```text
68c977d57b4d8ab0d0c5bf5eb2701c0e00cccd46ca179b20b77aea475b9c6b67
```

可同时下载 `SHA256SUMS-0.8.0.txt` 核对文件。

本项目不是红果官方产品，与红果及其关联主体无隶属、合作或背书关系。第三方内容、封面、商标与组件归各自权利人所有。[免责声明与权利说明](https://github.com/junmo-zy/hongguo-mac/blob/main/DISCLAIMER.md)。
