# 龙门骰

龙门骰的独立版本发布仓库，用于下载安装包、查看更新说明，以及为后续客户端更新提供固定渠道。

## 下载 M5.3.1

- [安卓安装包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.3.1/longmen-dice-M5.3.1-android.apk)：下载后安装，可使用原签名覆盖旧版。
- [Windows 便携包](https://github.com/Sun-rise-2024/longmen-dice-releases/releases/download/M5.3.1/longmen-dice-M5.3.1-windows.zip)：完整解压后双击 `START_GAME.cmd`，无需另外安装 Godot。
- [全部版本](https://github.com/Sun-rise-2024/longmen-dice-releases/releases)

联机双方请使用同一版本。Windows 与安卓可在彼此网络地址可达时联机。

## 本版更新

修复 M 炽拳之龙自身攻击、触发加攻并移动后，因离开原攻击范围而错误取消已宣言攻击的问题。现在移动后仍会对原目标继续结算，防御正常处理，费用不会重复扣除。

## 后续更新

当前 M5.3.1 尚未内置自动更新器。本仓库先建立固定下载渠道；客户端更新功能接入后，才能在游戏里检查及下载新版。`latest.json` 保存版本与下载信息，`SHA256SUMS.txt` 可用于核对安装包完整性。

## 源码及素材说明

Windows 便携包内包含本版 Godot 项目源码。第三方引擎、界面素材和卡图保留各自原有权利；本仓库不对第三方素材授予额外许可。

此 Windows 下载是 M5.3.1 的公开发布副本，仅移除了不参与游戏运行、含本机临时图片路径的开发裁切脚本；游戏程序、源码、素材、许可证和启动器与已验证的同版本包一致。

YGOMobile 界面资源的来源及 GPL-2.0 许可证见包内 `dungeon-dice-monsters/assets/ygomobile/SOURCES.md` 和 `LICENSE-GPL-2.0.txt`；Godot 许可证见 `tools/godot/GODOT_LICENSE.txt`。项目内编写的怪兽特效及参考说明见 `dungeon-dice-monsters/VFX_SOURCES.md`。
