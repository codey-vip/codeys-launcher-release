# CODEYS 无限法则启动器

<div align="center">

<img src="CodeysIcon.png" width="110" alt="CODEYS" />

**Ring of Elysium · 玩家社区服务器启动器**

[官方网站](https://codeys.vip) · [下载最新版](../../releases/latest) · [加入 TG 群](https://t.me/codeys_vip)

免费 · 中英双语 · 自带运行环境，解压即用

</div>

---

CODEYS 是一个由玩家发起、玩家运营的**无限法则（Ring of Elysium）社区服务器项目**。我们重建了完整的对局服务链路——大厅、匹配、选点、进图、毒圈、撤离结算——让你用原版 2022 客户端就能回到熟悉的海岛与雪地。

本仓库是 CODEYS 的**启动器发布页**，只包含启动器安装包、使用指南和项目介绍；服务端与启动器源码暂不公开。启动器压缩包**不包含任何游戏文件**，也不会修改客户端程序与资源。

## 📦 下载

打开 [Releases 最新版](../../releases/latest) 下载（约 40.9 MiB）：

| 文件 | 说明 |
| --- | --- |
| `CodeysLauncher-x.y.z-win-x64.zip` | 启动器主包，解压后运行 `CodeysLauncher.exe` |
| `CodeysLauncher-x.y.z-win-x64.zip.sha256` | 安装包校验值（SHA-256） |

当前正式版：**v1.1.6**（2026-11-09 发布）。

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
用启动器内的「检测网络」；发现可修复的拦截时可一键放行服务器 IP。仍未解决时，把同一次启动生成的两份 `.log` 文件（路径见设置内「使用帮助」）带到 TG 群，维护者会跟进。

## 🌍 English

CODEYS is a player-run community server for **Ring of Elysium**. Grab the launcher from [Releases](../../releases/latest), register at [codeys.vip](https://codeys.vip), and point the launcher at your own **ROE 2022 client (`0.2.989.0`)** — then jump back into the island and the snow with tactical AI, squads, vehicles and free cosmetics. The launcher is bilingual (Chinese/English), updates itself, and contains **no game files**. Full guide: [PLAYER-GUIDE.en-US.txt](PLAYER-GUIDE.en-US.txt).

## ⚠️ 声明

本项目为非官方玩家社区项目，与 Tencent、Aurora Studio 无关。「无限法则 / Ring of Elysium」名称及相关资产版权归原权利人所有。本仓库仅分发社区启动器程序与使用文档，不分发、不修改任何游戏客户端文件。

## 📜 许可与致谢

启动器基于 [tom-weiland/csharp-game-launcher](https://github.com/tom-weiland/csharp-game-launcher)（MIT）改造，详见 [Licence.txt](Licence.txt) 与 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)。
