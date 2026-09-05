# WarmCore 影院 · APK 下载

WarmCore 多端影院应用的安装包下载页。本项目仅公开发布 APK，源码仓库私有。

## 下载

| 应用 | 适用设备 | 直链下载 | 应用内版本 |
|---|---|---|---|
| 手机端 Phone | Android 手机 / 平板 | [WarmCoreCinemaPhone-debug.apk（v0.1.2）](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.2/WarmCoreCinemaPhone-debug.apk) | **1.0.1** |
| 电视端 TV | Android TV / 电视盒子 | [WarmCoreCinemaTV-debug.apk（v0.1.0）](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.0/WarmCoreCinemaTV-debug.apk) | — |
| 车机端 Car | 车载安卓（兼容 Android 4.1+ 老车机） | [WarmCoreCinemaCar-debug.apk（v0.1.0）](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.0/WarmCoreCinemaCar-debug.apk) | — |

安装后在「设置 → 应用 → WarmCore」核对版本号，手机端必须是 **1.0.1**（旧包都是 1.0.0，无法通过界面区分）。

文件完整性校验：[v0.1.2 SHA256.txt](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.2/SHA256.txt)（TV / 车机端哈希见 [v0.1.0 SHA256.txt](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.0/SHA256.txt)）

全部版本请见 [Releases 页面](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases)。

## 安装说明

1. 下载对应设备的 APK 文件。
2. 在设备上允许「安装未知来源应用」。
3. 点击 APK 安装。TV / 车机设备可先下载到手机或电脑，再通过 U 盘、局域网共享等方式传到设备上安装。

## 手机端显示「加载失败」？

1. 先确认装的是新包：设置 → 应用 → WarmCore，版本号应为 **1.0.1**。
2. 用手机浏览器打开 <http://67.216.218.76:8200/health>：显示 `{"status":"ok",...}` 说明当前网络可访问影视服务器；打不开说明当前网络（部分运营商蜂窝网络）无法访问该服务器，请切换 WiFi 后再试。

## 版本说明

- **v0.1.2**（2026-09-05）：手机端应用内版本升至 1.0.1；播放记录本地存储；内置影视服务地址与令牌。
- **v0.1.1**（2026-09-05）：修复手机端「历史」Tab 播放记录加载失败（播放记录改为本地存储）。应用内版本仍为 1.0.0，与旧包无法区分，请改用 v0.1.2。
- **v0.1.0**（2026-09-05）：首个公开版本，三端 debug 构建。
