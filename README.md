# WarmCore 影院 · APK 下载

WarmCore 多端影院应用的安装包下载页。本项目仅公开发布 APK，源码仓库私有。

## 下载

| 应用 | 适用设备 | 直链下载 | 应用内版本 |
|---|---|---|---|
| 手机端 Phone | Android 手机 / 平板 | [WarmCoreCinemaPhone.apk](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.9/WarmCoreCinemaPhone.apk) | **1.0.9** |
| 电视端 TV | Android TV / 电视盒子 | [WarmCoreCinemaTV.apk](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.4/WarmCoreCinemaTV.apk) | 1.1.6 |
| 车机端 Car | 车载安卓（兼容 Android 4.1+ 老车机） | [WarmCoreCinemaCar-debug.apk](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.4/WarmCoreCinemaCar-debug.apk) | 1.0.36 |

手机端 APK 只有上面这一个（v0.1.9）。旧版本中的手机端安装包均已下架。安装后在「设置 → 应用 → WarmCore」核对版本号，必须是 **1.0.9**。

文件完整性校验：[SHA256.txt](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/download/v0.1.9/SHA256.txt)（TV / 车机端哈希见 [v0.1.4 SHA256](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases/tag/v0.1.4)）

全部版本请见 [Releases 页面](https://github.com/zhouyevip/WarmCoreCinema-Releases/releases)。

## 安装说明

1. 下载对应设备的 APK 文件。
2. 在设备上允许「安装未知来源应用」。
3. 点击 APK 安装。TV / 车机设备可先下载到手机或电脑，再通过 U 盘、局域网共享等方式传到设备上安装。

## 版本说明

- **v0.1.9**（2026-09-28）：手机端 1.0.9。音乐页改版——搜歌、📻 FM 电台（radio-browser 中国电台：中国之声、经济之声、音乐台、相声等）、📺 音乐频道（IPTV）三块常驻同屏，横排卡片点击即播；去掉搜歌/频道模式切换。
- **v0.1.8**（2026-09-28）：手机端 1.0.8。音乐频道模式保留搜索框，可按频道名/分组/来源关键词筛选；搜索框提示词随模式切换（搜歌曲 / 筛频道 / 搜影视）。
- **v0.1.7**（2026-09-28）：手机端 1.0.7。音乐搜歌结果改为汽水音乐风格竖排列表（圆角封面、歌名/歌手·专辑、时长、播放圆钮），不再是方形海报网格；封面位暂用渐变音符占位。
- **v0.1.6**（2026-09-28）：手机端 1.0.6。音乐 Tab 支持搜歌点播——输入歌名/歌手搜索（酷我音源），点击歌曲直接解析直链播放，支持缓存下载；音乐频道（IPTV）保留为第二模式。
- **v0.1.5**（2026-09-28）：手机端 1.0.5。「点播 / 直播 / 历史 / 缓存」选项卡移至底部固定并新增**音乐** Tab（聚合 IPTV 音乐频道，点击即播）；去掉顶部「影视」标题整排；修复剧集长名字显示不全（网格按名字长度自适应列数）。签名与 v0.1.4 相同，可直接覆盖升级。
- **v0.1.4**（2026-09-05）：三端去云端化——本机直连资源站，源配置支持 GitHub 远程更新（24h 自动刷新），OTA 改走 GitHub。TV 瘦身至 3.2MB（1.1.6）、手机端瘦身至 13.7MB（1.0.4）、车机端 1.0.36。
- **v0.1.3**（2026-09-05）：修复点播页「加载失败: HTTP 404」（构建参数缺陷导致请求路径异常）。已在模拟器实测点播加载与历史页正常。应用内版本 1.0.2。
- **v0.1.2**（2026-09-05）：应用内版本 1.0.1；播放记录本地存储。该版点播页存在 404 问题，安装包已下架，请使用更新版本。
- **v0.1.1**（2026-09-05）：修复「历史」Tab 播放记录加载失败。安装包已下架。
- **v0.1.0**（2026-09-05）：首个公开版本，三端 debug 构建。
