<div align="center">

<img src="assets/ghost-agent-icon.png" alt="Ghost Agent" width="180" />

# Ghost Agent

**一个面向长期协作的本地优先 AI 工作台。**

Ghost Agent 把会话、人格、技能与数据源组织在同一个桌面应用里，
让 AI 不只回答眼前的问题，也能逐渐接住你的工具、资料和工作方式。

[**下载最新版本**](https://github.com/trivium-sys/ghost-agent-releases/releases/latest)

</div>

---

## 人格有自己的房间，不只是一张工牌

很多 AI 工具里的“人格”，主要是一段角色设定：名字和语气变了，背后的记忆与工作空间仍然混在一起。

Ghost Agent 把人格当作一个可以长期生长的协作主体。每个人格在本地拥有自己的身份、对你的理解、记忆索引和工作空间；开始会话时，这些内容会进入上下文，新的记忆也会回到它自己的目录。

模型负责提供能力，人格负责带着谁的身份、记忆和工作方式使用这些能力。你可以更换模型，而不必把搭档重新认识一遍；切换人格时，系统也会从下一轮正式交接，而不是在原对话里悄悄换一种口吻。

这些内容都落在你能查看、编辑和带走的本地文件里，不锁在某个远端账号中。不同模型通道提供的自动记忆能力可能不同，在线模型和外部服务仍遵循对应服务的隐私政策。

## 下载安装

Ghost Agent 目前支持 **Apple Silicon Mac（M 系列芯片）**。

1. 打开 [最新版本页面](https://github.com/trivium-sys/ghost-agent-releases/releases/latest)。
2. 下载名称类似 `Ghost-Agent-0.10.3-ghost.11-arm64.dmg` 的文件。
3. 打开 DMG，把 **Ghost Agent** 拖进「应用程序」文件夹，然后启动。

安装包带 Developer ID 签名并通过 Apple 公证；macOS 会在安装和更新时验证它没有被篡改。

## 更新会自己来

安装一次以后，不需要反复回来下载 DMG。

Ghost Agent 启动时会在后台检查新版本。有更新时，App 会显示下载进度；准备完成后确认重启，
它会自动退出、替换为新版本并重新打开。也可以在 App 菜单中手动检查更新。

你的会话、人格、技能和配置不住在安装包里，正常版本更新不会覆盖这些数据。

## 下载哪个文件？

普通用户只需要下载带版本号的 **`arm64.dmg`**。

Release 里其余 ZIP、blockmap 和 YAML 文件是自动更新系统使用的组件，不需要手动下载或打开。

## 遇到问题

如果安装失败、更新卡住，或者启动后发现异常，请到
[Issues](https://github.com/trivium-sys/ghost-agent-releases/issues) 留言，并附上：

- 当前 Ghost Agent 版本
- macOS 版本
- 出现问题前做了什么
- 能看到的错误文字或截图

---

<div align="center">
<sub>旧时王谢堂前燕，飞入寻常百姓家。</sub>
</div>
