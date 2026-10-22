# 龙门骰

龙门骰的独立版本发布与更新仓库。

## 下载 M5.4

- [Android 安装包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.4/longmen-dice-M5.4-android.apk)：下载后按系统提示覆盖安装。
- [Windows 便携包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.4/longmen-dice-M5.4-windows.zip)：完整解压后双击 `START_GAME.cmd`，无需另外安装 Godot。
- [全部版本](https://github.com/Sun-rise-2024/longmen-dice-releases/releases)；[M5.3.1 历史版本](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/tag/M5.3.1)。

联机双方请使用同一版本。Windows 与 Android 可在网络地址彼此可达时联机。

## 自动检查与一键更新

M5.4 起可在主菜单、设置中“检查更新”，启动时也会自动检查。Windows 下载并校验更新包后安装、重启；Android 会打开浏览器下载新版 APK，再按系统流程覆盖安装。对局期间不会自动替换游戏文件。

M5.3.1 及更早版本尚无内置更新器，需先手动安装一次 M5.4。固定更新清单为 [latest.json](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/latest/download/latest.json)。

## 本版更新

新增主菜单／设置检查更新、启动自动检查；Windows 下载校验后安装重启，Android 通过浏览器下载覆盖安装，并保留对局保护。

## 源码与素材说明

Windows 包包含本版 Godot 项目源码。公开副本会排除含本机临时图片路径、且不参与游戏运行的开发裁切脚本；游戏运行文件与本版构建一致。

第三方引擎、界面素材、卡图保留原有权利；本仓库不对第三方素材授予额外许可。YGOMobile 来源与 GPL-2.0 许可证见包内 `dungeon-dice-monsters/assets/ygomobile/SOURCES.md`、`LICENSE-GPL-2.0.txt`；Godot 许可证见 `tools/godot/GODOT_LICENSE.txt`。
