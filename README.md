# 龙门骰

龙门骰的独立版本发布与更新仓库。

## 下载 M5.7.4

- [Android 安装包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.7.4/longmen-dice-M5.7.4-android.apk)：下载后按系统提示覆盖安装。
- [Windows 便携包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.7.4/longmen-dice-M5.7.4-windows.zip)：完整解压后双击 `START_GAME.cmd`，无需另外安装 Godot。
- Android 备用下载：[线路一](https://ghfast.top/https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.7.4/longmen-dice-M5.7.4-android.apk) / [线路二](https://gh-proxy.com/https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.7.4/longmen-dice-M5.7.4-android.apk)。
- Windows 备用下载：[线路一](https://ghfast.top/https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.7.4/longmen-dice-M5.7.4-windows.zip) / [线路二](https://gh-proxy.com/https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.7.4/longmen-dice-M5.7.4-windows.zip)。
- [全部版本](https://github.com/Sun-rise-2024/longmen-dice-releases/releases)；[M5.7.3 历史版本](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/tag/M5.7.3)。

联机双方请使用同一版本。Windows 与 Android 可在网络地址彼此可达时联机。

## 本版更新

先手第一个回合改为投2枚骰子，之后每回合仍投3枚；独立对话框与投骰浮层支持拖动，保留列表与正文滚动。

切屏时保留原对局、暂停双方操作，回到游戏后先核对进度再继续；连接已丢失时自动尝试恢复原座位。房主和加入者之间仍需保持网络地址可达。安卓强制结束进程或更换网络后可能需要手动重连。手机可在设置选择三档界面大小；列表可从按钮、卡图和文字上开始滑动，棋盘可单指平移、双指缩放。

## 自动检查与一键更新

M5.4 起可在主菜单、设置中“检查更新”，启动时也会自动检查。Windows 下载并校验更新包后安装、重启；M5.6 起 Android 也会在游戏内下载并校验新版 APK，然后直接进入系统安装授权与确认；第一次需允许龙门骰安装应用。对局期间不会自动替换游戏文件。

M5.6 起可直接在游戏内更新到本版；M5.4、M5.5 升级到本版仍使用原有的浏览器下载流程。旧版没有备用线路，无法访问 GitHub 时需手动覆盖安装本版一次。M5.3.1 及更早版本也需先手动安装新版。M5.7 起使用 [签名清单](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/latest/download/latest.signed.json)，自动切换固定的备用传输线路；公共服务的可用性由所在网络与服务状态决定。原 [latest.json](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/latest/download/latest.json) 保留给旧更新器。

## 源码与素材说明

Windows 包包含本版 Godot 项目源码。公开副本会排除含本机临时图片路径、且不参与游戏运行的开发裁切脚本；游戏运行文件与本版构建一致。

第三方引擎、界面素材、卡图保留原有权利；本仓库不对第三方素材授予额外许可。YGOMobile 来源与 GPL-2.0 许可证见包内 `dungeon-dice-monsters/assets/ygomobile/SOURCES.md`、`LICENSE-GPL-2.0.txt`；Godot 许可证见 `tools/godot/GODOT_LICENSE.txt`。
