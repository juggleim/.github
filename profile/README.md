<div align="center">
  <a href="https://www.juggle.im/">
    <img src="https://raw.githubusercontent.com/juggleim/im-server/master/docs/logo.png" alt="JuggleIM" height="112">
  </a>

  <h1>Open-source infrastructure for real-time messaging</h1>

  <p>
    Build private chat, group messaging, live chatrooms, customer support,<br>
    social communities, and AI conversations—on infrastructure you control.
  </p>

  <p>
    <strong>English</strong> · <a href="./README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://github.com/juggleim/im-server/stargazers"><img src="https://img.shields.io/github/stars/juggleim/im-server?style=flat-square&color=ffb000&label=Stars" alt="GitHub stars"></a>
    <a href="https://github.com/juggleim/im-server/network/members"><img src="https://img.shields.io/github/forks/juggleim/im-server?style=flat-square&color=3b82f6" alt="GitHub forks"></a>
    <a href="https://github.com/juggleim/im-server/blob/master/LICENSE"><img src="https://img.shields.io/github/license/juggleim/im-server?style=flat-square&color=22c55e" alt="Apache 2.0 license"></a>
    <a href="https://github.com/juggleim/im-server/commits/master"><img src="https://img.shields.io/github/last-commit/juggleim/im-server?style=flat-square" alt="Last commit"></a>
  </p>

  <p>
    <a href="https://www.juggle.im/"><strong>Website</strong></a> ·
    <a href="https://www.juggle.im/docs/guide/intro/"><strong>Documentation</strong></a> ·
    <a href="https://www.juggle.im/docs/guide/deploy/quickdeploy/"><strong>Quick Deploy</strong></a> ·
    <a href="https://github.com/juggleim/im-server/discussions"><strong>Discussions</strong></a> ·
    <a href="https://t.me/juggleim_zh"><strong>Community</strong></a>
  </p>
</div>

---

## Own your messaging stack

JuggleIM is a **high-performance, scalable instant messaging platform** with an open-source Go server, multi-platform client SDKs, REST APIs, WebHooks, admin tooling and related developer components.

For developers who want to evaluate JuggleIM or build their own messaging product, we also provide an open-source JuggleChat Server and open-source UI demo/reference applications for Web, iOS, and Android.

These open-source projects are intended for evaluation, integration reference, learning, and custom development.

JuggleChat is a separate production-ready commercial messaging product built by the JuggleIM team. It provides complete application source code for teams that want to launch a full messaging product without building every product-level feature from scratch.

> **Important**
>
> The open-source JuggleChat Server and UI demos are developer reference projects.
> They are not the complete commercial JuggleChat product source code.

Choose a self-hosted private deployment for full control over data and infrastructure, or use the managed cloud to start quickly. The same platform supports everything from a two-person conversation to a 100,000-member group and large live chatrooms.

| | What you get |
| :--- | :--- |
| **Self-hosted by design** | Deploy on your own servers or cloud; keep control of data storage and operations. |
| **Every major client** | Android, iOS, Web, React Native, Flutter, HarmonyOS, and desktop building blocks. |
| **Complete messaging** | Private chat, groups, chatrooms, system notifications, read state, multi-device sync, media, and custom messages. |
| **Built for production** | Protobuf + WebSocket, horizontal scaling, REST APIs, WebHooks, moderation, push, and an admin console. |
| **Ready to customize** | Start from JuggleChat's cross-platform source code instead of rebuilding common chat flows. |

JuggleIM is a practical foundation for **self-hosted chat**, **in-app messaging**, social networks, marketplace messaging, customer service, community products, live-stream interaction, IoT messaging, and AI assistants.

<a href="https://www.juggle.im/#/jugglechat">
  <img src="https://github.com/user-attachments/assets/0432e193-9ee0-45e1-9997-080f68c0be00" alt="JuggleChat cross-platform messaging interface" width="100%">
</a>

<p align="center"><em>JuggleChat is JuggleIM's production-ready cross-platform messaging application, available as commercial source code for Android, iOS, Web and Desktop.

Public GitHub repositories provide SDKs, infrastructure components and selected reference/demo projects. <a href="https://www.juggle.im/#/jugglechat">Explore the product →</a></em></p>

## Start with the right project

| Project | Use it for | Stack |
| :--- | :--- | :---: |
| ⭐ **[im-server](https://github.com/juggleim/im-server)** | The open-source core: message delivery, storage, connections, groups, chatrooms, and server APIs | Go |
| **[jugglechat-server](https://github.com/juggleim/jugglechat-server)** | A production-ready business server with accounts, friends, groups, auth, bots, and storage. Used in open source UI demos and commercial JuggleChat applications. | Go |
| **[Client SDKs and UI demos](https://github.com/orgs/juggleim/repositories?q=imsdk)** | Add messaging to Android, iOS, Web, React Native, Flutter, and HarmonyOS apps | Multi-platform |
| **[Server SDKs](https://github.com/orgs/juggleim/repositories?q=imserver-sdk)** | Call JuggleIM server APIs from Go, Java, or Python services | Go / Java / Python |
| **[Bot SDKs](https://github.com/orgs/juggleim/repositories?q=imbot-sdk)** | Connect bots, automations, and AI assistants | Go / Python / Node.js / Rust |

<details>
<summary><strong>Direct links to client SDKs and apps</strong></summary>

<br>

| Platform | SDK | Open-source UI Demo | Commercial JuggleChat  |
| :--- | :--- | :--- | :--- |
| Android | [imsdk-android](https://github.com/juggleim/imsdk-android) | [android-demo](https://github.com/juggleim/imsdk-android/tree/master/demo) | Available |
| iOS | [imsdk-ios](https://github.com/juggleim/imsdk-ios) | [iOS-demo](https://github.com/juggleim/imsdk-ios/tree/master/QuickStart) | Available |
| Web | [imsdk-web](https://github.com/juggleim/imsdk-web) | [jugglechat-web](https://github.com/juggleim/jugglechat-web) | Available |
| React Native | [imsdk-rn](https://github.com/juggleim/imsdk-rn) | — | - |
| Flutter | [imsdk-flutter](https://github.com/juggleim/imsdk-flutter) | — | Available |
| HarmonyOS | [imsdk-harmony](https://github.com/juggleim/imsdk-harmony) | — | -|

</details>

## Get running

Pick the shortest path for your goal:

1. **Host your own IM service** — follow the [one-click deployment guide](https://www.juggle.im/docs/guide/deploy/quickdeploy/) or explore [im-server](https://github.com/juggleim/im-server).
2. **Add chat to an existing product** — choose a [client SDK](https://www.juggle.im/docs/client/quickstart/android/) and connect it through the documented server APIs.
3. **Ship a complete messenger** — use [JuggleChat](https://github.com/juggleim/jugglechat-server) as a full-stack starting point and customize the clients for your product.

Explore the [product overview](https://www.juggle.im/docs/guide/intro/), [SDK documentation](https://www.juggle.im/docs/client/quickstart/android/), and [server API reference](https://www.juggle.im/docs/server/api/) for integration details.

## Built for real products

- **Social & communities:** direct messages, friend relationships, large groups, mentions, reactions, and read receipts.
- **Marketplaces & support:** buyer–seller conversations, service notifications, message history, and moderation hooks.
- **Live experiences:** high-concurrency chatrooms for comments, likes, gifts, room state, and interactive events.
- **AI & automation:** bot SDKs and connectors for assistants, workflows, and LLM-powered conversations.
- **Private enterprise apps:** deploy inside your own environment and choose where conversation data is stored.

## Join the community

Great open-source messaging infrastructure is built in the open. You can help by:

- ⭐ Starring [im-server](https://github.com/juggleim/im-server) so more developers can discover JuggleIM.
- 💬 Asking questions and sharing ideas in [GitHub Discussions](https://github.com/juggleim/im-server/discussions).
- 🐛 Reporting a bug or proposing a feature in [GitHub Issues](https://github.com/juggleim/im-server/issues).
- 🛠️ Improving code or documentation with a pull request.
- 💬 Joining the [Telegram Chinese community](https://t.me/juggleim_zh) for integration help and discussion.
- 🚀 Sharing what you built with JuggleIM—we would love to feature it.

<div align="center">
  <br>
  <h3>If JuggleIM saves you time, give <a href="https://github.com/juggleim/im-server">im-server</a> a ⭐</h3>
  <p>Every Star helps other developers find an open, self-hosted alternative for real-time messaging.</p>
  <a href="https://github.com/juggleim/im-server/stargazers">
    <img src="https://img.shields.io/github/stars/juggleim/im-server?style=for-the-badge&logo=github&color=ffb000&label=Star%20JuggleIM" alt="Star JuggleIM on GitHub">
  </a>
</div>
