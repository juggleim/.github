### 关于 JuggleIM

IM 即时通讯是日常工作生活必备的工具之一，我们每天都被文本消息、语音消息、图片消息等各种信息包围着，IM 通信能力自主化和数据存储安全化关注度日益增高，JuggleIM 在此背景下推出全新一代 IM 即时通讯系统，并且将 IM 核心源码 **全部开源**，支持开发者自主选择部署方式和数据存储位置，提供公有云和私有云两种模式，公私有部署模式 IM 功能完全一致，开发者可以根据业务发展阶段和特性灵活选择高自主化和数据自有存储的私有云，也可选择简单可靠开箱即用的公有云服务。

### 社群讨论

如果对 IM 感兴趣、有集成问题讨论的朋友，非常欢迎加入社群讨论～

[Telegram 中文群](https://t.me/juggleim_zh)、[Telegram English](https://t.me/juggleim_en)、[添加好友加入微信群](https://downloads.juggleim.com/xiaoshan.jpg)

_备注：由于微信群二维码有时间限制，加入微信讨论可优先加 **小山** 微信好友，由 Ta 邀请进群组_

### 下载 Demo

> JuggleChat iOS: [https://testflight.apple.com/join/XucKbQ54](https://testflight.apple.com/join/XucKbQ54)

> JuggleChat Android: 敬请期待

> JuggleChat Web: [https://im.jugglechat.com/](https://im.jugglechat.com/)

> JuggleLive Web: [https://live.jugglechat.com/](https://live.jugglechat.com/)


### SDK 在线安装

#### Android SDK

1. 导入 Juggle 的 maven 代码库。打开根目录下的 settings.gradle（Project 视图）。

```gradle（Project
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        //Juggle 的 maven 仓库
        maven {
            url "https://maven.jugglechat.com/repository/maven-releases/"
        }
    }
}
```

2. 在应用的 build.gradle 中，添加 Juggle 依赖。

```gradle（Project
dependencies {
    ...
    api 'com.juggle.im:juggle:1.7.0'
}
```

#### iOS SDK

1. 在 podfile 里添加如下内容

```shell
pod 'JuggleIM', '1.7.0'
```

2. 在终端中运行以下命令

```shell
pod install
```

#### Web SDK

```js
npm install jugglechat-websdk --save

import JuggleIM from 'jugglechat-websdk';

```


