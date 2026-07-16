<div align="center">
  <a href="https://www.juggle.im/">
    <img src="https://raw.githubusercontent.com/juggleim/im-server/master/docs/logo.png" alt="JuggleIM" height="112">
  </a>

  <h1>为实时通讯而生的开源基础设施</h1>

  <p>
    在完全自主可控的基础设施上，快速构建私聊、群聊、直播聊天室、客服系统、<br>
    社区产品和 AI 对话应用。
  </p>

  <p>
    <a href="./README.md">English</a> · <strong>简体中文</strong>
  </p>

  <p>
    <a href="https://github.com/juggleim/im-server/stargazers"><img src="https://img.shields.io/github/stars/juggleim/im-server?style=flat-square&color=ffb000&label=Stars" alt="GitHub Stars"></a>
    <a href="https://github.com/juggleim/im-server/network/members"><img src="https://img.shields.io/github/forks/juggleim/im-server?style=flat-square&color=3b82f6" alt="GitHub Forks"></a>
    <a href="https://github.com/juggleim/im-server/blob/master/LICENSE"><img src="https://img.shields.io/github/license/juggleim/im-server?style=flat-square&color=22c55e" alt="Apache 2.0 开源协议"></a>
    <a href="https://github.com/juggleim/im-server/commits/master"><img src="https://img.shields.io/github/last-commit/juggleim/im-server?style=flat-square" alt="最近提交"></a>
  </p>

  <p>
    <a href="https://www.juggle.im/"><strong>官网</strong></a> ·
    <a href="https://www.juggle.im/docs/guide/intro/"><strong>开发文档</strong></a> ·
    <a href="https://www.juggle.im/docs/guide/deploy/quickdeploy/"><strong>快速部署</strong></a> ·
    <a href="https://github.com/juggleim/im-server/discussions"><strong>开发者讨论</strong></a> ·
    <a href="https://t.me/juggleim_zh"><strong>开发者社区</strong></a>
  </p>
</div>

---

## 掌控自己的即时通讯技术栈

JuggleIM 是一套**高性能、可扩展的即时通讯平台**，包含开源 Go 服务端、多平台客户端 SDK、服务端 API、WebHook、管理工具以及生产可用的聊天应用源码。

你可以通过私有化部署完整掌控数据和基础设施，也可以使用公有云快速开始。同一套平台既能承载两个人的私聊，也能支持十万成员大群和大型直播聊天室。

| | 你将获得 |
| :--- | :--- |
| **私有化优先** | 部署在自有服务器或云环境，自主掌控数据存储与运维方式。 |
| **覆盖主流平台** | 提供 Android、iOS、Web、React Native、Flutter、HarmonyOS 和桌面端能力。 |
| **完整通讯场景** | 私聊、群聊、聊天室、系统通知、已读状态、多端同步、媒体消息和自定义消息。 |
| **面向生产环境** | Protobuf + WebSocket、水平扩展、REST API、WebHook、内容审核、推送和管理后台。 |
| **开箱即可二开** | 从 JuggleChat 多端源码开始，无需重复开发常见聊天流程。 |

JuggleIM 适用于**自托管聊天系统**、**App 内即时通讯**、社交网络、电商私信、在线客服、社区产品、直播互动、IoT 消息和 AI 助手等场景。

<a href="https://www.juggle.im/#/jugglechat">
  <img src="https://github.com/user-attachments/assets/0432e193-9ee0-45e1-9997-080f68c0be00" alt="JuggleChat 跨平台即时通讯界面" width="100%">
</a>

<p align="center"><em>JuggleChat 是基于 JuggleIM 构建的开源跨平台应用。<a href="https://www.juggle.im/#/jugglechat">查看产品 →</a></em></p>

## 选择合适的项目开始

| 项目 | 适用场景 | 技术栈 |
| :--- | :--- | :---: |
| ⭐ **[im-server](https://github.com/juggleim/im-server)** | 开源 IM 核心：消息投递、存储、长连接、群组、聊天室和服务端 API | Go |
| **[jugglechat-server](https://github.com/juggleim/jugglechat-server)** | 生产可用的业务服务端：账号、好友、群组、鉴权、机器人和存储 | Go |
| **[JuggleChat 客户端](https://github.com/orgs/juggleim/repositories?q=jugglechat)** | 可自由二开的 Android、iOS、Web 和桌面端聊天应用 | 多平台 |
| **[客户端 SDK](https://github.com/orgs/juggleim/repositories?q=imsdk)** | 为 Android、iOS、Web、React Native、Flutter 和 HarmonyOS 应用集成 IM | 多平台 |
| **[服务端 SDK](https://github.com/orgs/juggleim/repositories?q=imserver-sdk)** | 在 Go、Java 或 Python 服务中调用 JuggleIM 服务端 API | Go / Java / Python |
| **[机器人 SDK](https://github.com/orgs/juggleim/repositories?q=imbot-sdk)** | 接入机器人、自动化流程和 AI 助手 | Go / Python / Node.js / Rust |

<details>
<summary><strong>客户端 SDK 与应用源码直达链接</strong></summary>

<br>

| 平台 | SDK | 可二开的应用 |
| :--- | :--- | :--- |
| Android | [imsdk-android](https://github.com/juggleim/imsdk-android) | [jugglechat-android](https://github.com/juggleim/jugglechat-android) |
| iOS | [imsdk-ios](https://github.com/juggleim/imsdk-ios) | [jugglechat-ios](https://github.com/juggleim/jugglechat-ios) |
| Web | [imsdk-web](https://github.com/juggleim/imsdk-web) | [jugglechat-web](https://github.com/juggleim/jugglechat-web) |
| React Native | [imsdk-rn](https://github.com/juggleim/imsdk-rn) | — |
| Flutter | [imsdk-flutter](https://github.com/juggleim/imsdk-flutter) | — |
| HarmonyOS | [imsdk-harmony](https://github.com/juggleim/imsdk-harmony) | — |
| 桌面端 | — | [jugglechat-desktop](https://github.com/juggleim/jugglechat-desktop) |

</details>

## 快速开始

根据你的目标选择最短路径：

1. **自建 IM 服务** — 查看[一键部署文档](https://www.juggle.im/docs/guide/deploy/quickdeploy/)，或直接访问 [im-server](https://github.com/juggleim/im-server)。
2. **为现有产品集成聊天** — 选择对应的[客户端 SDK](https://www.juggle.im/docs/client/quickstart/android/)，并通过服务端 API 接入现有业务系统。
3. **快速上线完整聊天应用** — 使用 [JuggleChat](https://github.com/juggleim/jugglechat-server) 作为全栈起点，再按产品需求定制各端客户端。

集成细节请查看[产品概述](https://www.juggle.im/docs/guide/intro/)、[客户端 SDK 文档](https://www.juggle.im/docs/client/quickstart/android/)和[服务端 API 文档](https://www.juggle.im/docs/server/api/)。

## 服务真实业务场景

- **社交与社区：** 私信、好友关系、大群、@、消息回应和已读回执。
- **电商与客服：** 买卖双方沟通、服务通知、历史消息和内容审核回调。
- **直播互动：** 支持弹幕、点赞、礼物、房间状态和互动事件的高并发聊天室。
- **AI 与自动化：** 通过机器人 SDK 和连接器构建助手、工作流及大模型对话。
- **企业私有应用：** 部署在自有环境中，并自主选择会话数据的存储位置。

## 加入社区

优秀的开源即时通讯基础设施需要大家共同建设。你可以：

- ⭐ 为 [im-server](https://github.com/juggleim/im-server) 点亮 Star，让更多开发者发现 JuggleIM。
- 💬 在 [GitHub Discussions](https://github.com/juggleim/im-server/discussions) 提问、交流想法或展示项目。
- 🐛 通过 [GitHub Issues](https://github.com/juggleim/im-server/issues) 报告问题或提出新功能建议。
- 🛠️ 提交 Pull Request，改进代码或文档。
- 💬 加入 [Telegram 中文社区](https://t.me/juggleim_zh)，讨论集成问题和 IM 技术。
- 🚀 分享你基于 JuggleIM 构建的产品，我们很乐意展示优秀案例。

<div align="center">
  <br>
  <h3>如果 JuggleIM 为你节省了时间，请为 <a href="https://github.com/juggleim/im-server">im-server</a> 点亮 ⭐</h3>
  <p>每一个 Star 都能帮助更多开发者发现开放、自托管的实时通讯方案。</p>
  <a href="https://github.com/juggleim/im-server/stargazers">
    <img src="https://img.shields.io/github/stars/juggleim/im-server?style=for-the-badge&logo=github&color=ffb000&label=Star%20JuggleIM" alt="在 GitHub 为 JuggleIM 点亮 Star">
  </a>
</div>
