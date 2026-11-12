# CODEYS 无限法则启动器

<div align="center">

<img src="CodeysIcon.png" width="110" alt="CODEYS" />

**Ring of Elysium · 玩家社区服务器启动器**

[官方网站](https://codeys.vip) · [下载最新版](../../releases/latest) · [加入 TG 群](https://t.me/codeys_vip)

免费 · 中英双语 · 精简版 / 完整版

</div>

---

CODEYS 是一个由玩家发起、玩家运营的**无限法则（Ring of Elysium）社区服务器项目**。我们重建了完整的对局服务链路——大厅、匹配、选点、进图、毒圈、撤离结算——让你用原版 2022 客户端就能回到熟悉的海岛与雪地。

本仓库是 CODEYS 的**启动器发布页**，只包含启动器安装包、使用指南和项目介绍；服务端与启动器源码暂不公开。启动器压缩包**不包含任何游戏文件**，也不会修改客户端程序与资源。

## 📦 下载

打开 [Releases 最新版](../../releases/latest) 或 [官网](https://codeys.vip/#launcher-download) 下载：

| 文件 | 说明 |
| --- | --- |
| `CodeysLauncher-1.1.8-win-x64-lite.zip` | 精简版，需 .NET 10 桌面运行环境（x64） |
| `CodeysLauncher-1.1.8-win-x64.zip` | 完整版，自带运行环境 |
| `*.zip.sha256` | 对应安装包的 SHA-256 校验值 |

当前正式版：**v1.1.8**（2026-11-12）。本次为**强制更新**，旧版须更新后才能继续启动游戏。解压后运行 `CodeysLauncher.exe`；两种压缩包均不含 docs 文件夹。

### 1.1.8 更新

- 兼容模式使用签名 ACE-BASE 驱动；每次兼容启动先自动停止并确认服务已停止，游戏退出后恢复原路径。默认关闭，需要管理员授权；请先退出其他 ACE 游戏。
- 新增 TP / ACE 安全组件检查，停止失败或超时会明确提示。
- 更新弹窗可选“默认 / 精简版 / 完整版”，默认识别当前版本类型。
- 附属文件统一放入 `CodeysLauncher.Data`，日志仅保留最近 10 次启动及对应错误、崩溃记录。
- 管理员公告评论显示金色“管理员”，身份由服务器确认。
- 保留渲染器选择、地图开关、CET 兼容、10 秒网络检测、公告互动及反馈提醒。

## 🚀 快速开始

1. 准备**无限法则 2022 客户端**（`0.2.989.0`，需自行安装；本仓库不分发游戏文件）
2. 在 [codeys.vip](https://codeys.vip) 注册账号
3. 下载并解压启动器，运行 `CodeysLauncher.exe`
4. 用账号名或邮箱登录；启动器会自动识别游戏目录，未找到时可手动选择
5. 点击**开始游戏**——游戏运行期间请保持启动器开启

完整说明见 [PLAYER-GUIDE.zh-CN.txt](PLAYER-GUIDE.zh-CN.txt) ｜ [English Guide](PLAYER-GUIDE.en-US.txt)。

## ✨ 服务器玩法

- 🗺️ **经典地图**：海岛（Europa）与雪地大世界，另有团队竞技（TDM）
- 🤖 **战术 AI**：会进圈、找掩体、投烟救人、绕路包抄的智能对手，独狼也能打满全场
- 👥 **完整对局链路**：注册 → 大厅 → 匹配 → 选点 → 进图 → 撤离登机结算，异常断线可重连
- 🎫 **全外观开放**：1692 项永久通用外观对所有账号开放，20 种游戏货币一次性大额发放
- 🚗 **载具与战术装备**：载具皮肤、抓钩、滑翔与滑雪背包等原版装备
- 🛡️ **小队系统**：好友、组队、公开招募，和队友整队进图

## ❓ 常见问题

**收费吗？**
免费，社区运营，无任何内购。

**和官方服务器是什么关系？**
没有关系。这是玩家社区项目，启动器连接的是 CODEYS 自行运营的社区服务器。

**必须要有原版客户端吗？**
必须。启动器只校验并启动本机已安装的无限法则 2022（`0.2.989.0`）客户端；仓库和启动器压缩包都不包含游戏文件。

**账号安全吗？**
启动器不保存密码，登录凭证由 Windows 当前用户加密存储，最长 7 天有效；游戏服务器通过一次性票据核验身份，仅凭 UID 无法登录他人账号。目前暂不支持邮箱找回密码，请保管好密码。

**连不上 / 进不去游戏？**
用启动器内的「检测网络」；发现可修复的拦截时可一键放行服务器 IP，检测到丢包时按提示启动游戏加速器后重测。出现错误时启动器会自动上传脱敏诊断信息；你也可以使用「提交反馈」说明问题，并附上同一次启动生成的两份 `.log` 文件（位于 `CodeysLauncher.Data/logs`，设置内「使用帮助」可查看实际路径），方便维护者排查。

## 🌍 English

CODEYS is a player-run community server for **Ring of Elysium**. Grab the launcher from [Releases](../../releases/latest), register at [codeys.vip](https://codeys.vip), and point the launcher at your own **ROE 2022 client (`0.2.989.0`)** — then jump back into the island and the snow with tactical AI, squads, vehicles and free cosmetics. The launcher is bilingual (Chinese/English), updates itself, and contains **no game files**. Full guide: [PLAYER-GUIDE.en-US.txt](PLAYER-GUIDE.en-US.txt).

**Current stable: v1.1.8 (2026-11-12). This update is required.** Choose Lite (.NET 10 Desktop Runtime x64 required) or Full (runtime included). Compatibility mode uses a signed ACE-BASE driver, automatically stops and checks the service before each compatible launch, and restores its path on exit. This mode defaults off and requires administrator approval. Updates offer Default/Lite/Full; logs and related crash records retain the latest ten launches. Includes security diagnostics and trusted administrator comment labels. Packages omit the docs folder.

## ⚠️ 声明

本项目为非官方玩家社区项目，与 Tencent、Aurora Studio 无关。「无限法则 / Ring of Elysium」名称及相关资产版权归原权利人所有。本仓库仅分发社区启动器程序与使用文档，不分发、不修改任何游戏客户端文件。

## 📜 许可与致谢

启动器基于 [tom-weiland/csharp-game-launcher](https://github.com/tom-weiland/csharp-game-launcher)（MIT）改造，详见 [Licence.txt](Licence.txt) 与 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)。
