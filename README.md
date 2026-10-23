# 龙门骰

龙门骰的独立版本发布与更新仓库。

## 下载 M5.6

- [Android 安装包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.6/longmen-dice-M5.6-android.apk)：下载后按系统提示覆盖安装。
- [Windows 便携包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.6/longmen-dice-M5.6-windows.zip)：完整解压后双击 `START_GAME.cmd`，无需另外安装 Godot。
- [全部版本](https://github.com/Sun-rise-2024/longmen-dice-releases/releases)；[M5.5 历史版本](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/tag/M5.5)。

联机双方请使用同一版本。Windows 与 Android 可在网络地址彼此可达时联机。

## 安卓游戏内更新

安卓版支持在游戏内下载并校验新版 APK，直接唤起安卓系统的安装授权与确认，不再跳转浏览器；保留手机版屏幕适配和 Windows 更新。

手机可在系统设置选择“界面大小”。棋盘用双指缩放和平移，单指选格、召唤拖放及长按查看资料继续保留；“全图”按钮恢复整张棋盘。

## 自动检查与一键更新

M5.4 起可在主菜单、设置中“检查更新”，启动时也会自动检查。Windows 下载并校验更新包后安装、重启；M5.6 起 Android 也会在游戏内下载并校验新版 APK，然后直接进入系统安装授权与确认；第一次需允许龙门骰安装应用。对局期间不会自动替换游戏文件。

M5.4、M5.5 升级到 M5.6 这一次仍使用原有的浏览器下载流程；升级后后续版本可在游戏内下载。M5.3.1 及更早版本尚无内置更新器，需先手动安装新版。固定更新清单为 [latest.json](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/latest/download/latest.json)。

## 源码与素材说明

Windows 包包含本版 Godot 项目源码。公开副本会排除含本机临时图片路径、且不参与游戏运行的开发裁切脚本；游戏运行文件与本版构建一致。

第三方引擎、界面素材、卡图保留原有权利；本仓库不对第三方素材授予额外许可。YGOMobile 来源与 GPL-2.0 许可证见包内 `dungeon-dice-monsters/assets/ygomobile/SOURCES.md`、`LICENSE-GPL-2.0.txt`；Godot 许可证见 `tools/godot/GODOT_LICENSE.txt`。
