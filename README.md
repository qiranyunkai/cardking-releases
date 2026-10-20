# 抽卡的王（Card King）

抽卡的王 macOS 应用的安装包与在线更新发布仓库。

## 发布状态

正在准备首个支持在线更新的公开版本。完成 Apple Developer ID 签名、公证及更新验证后，将在 Releases 中提供下载。

## 系统要求

- macOS 14 或更高版本
- Apple Silicon 或 Intel Mac

## 安装和更新

首次使用时，从 Releases 下载所需通道的安装包，解压后将应用移入“应用程序”。

安装已配置在线更新的版本后，可在应用菜单中选择“检查更新…”获取后续版本。电脑需要能够联网访问 GitHub 及其下载服务。

## 更新通道

- [正式版](https://github.com/qiranyunkai/cardking-releases/releases/tag/cardking-stable)：`cardking-stable`
- [预览版](https://github.com/qiranyunkai/cardking-releases/releases/tag/cardking-preview)：`cardking-preview`

两个通道分别提供更新清单和安装包。应用会检查自身通道的更新。

本仓库用于发布安装包、更新清单和版本说明。
