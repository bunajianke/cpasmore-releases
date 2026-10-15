# CapsMore 下载

原生 macOS 键盘增强工具：按住 Caps Lock 使用快捷键，支持自定义映射、状态栏监听开关和软件内在线更新。

**[下载最新版本](https://github.com/bunajianke/cpasmore-releases/releases/latest)**

## 安装

1. 在 Releases 下载 `CapsMore-<版本>.dmg`，将 CapsMore 拖到“应用程序”。
2. 从“应用程序”打开 CapsMore，为这份应用开启“辅助功能”和“输入监控”，退出重开。
3. 右键状态栏图标，选择“开关监听”。

支持 Apple Silicon 和 Intel，最低 macOS 12。当前版本使用本地临时签名，未做 Apple 公证；首次打开可能需要在系统设置中确认，升级后权限也可能需要重新授权。

## 更新与配置

通过“CapsMore → 检查更新…”或状态栏右键菜单安装后续版本。可开启“自动检查更新”。更新源和 ZIP 更新包均使用 EdDSA 签名校验。

快捷键配置保存在 `~/Library/Application Support/CapsMore/shortcuts.json`，升级后保留。

本仓库只发布安装包、更新源和版本说明，源码独立维护。
