# Ghost Agent — Releases

Ghost Agent 的安装包与自动更新分发仓。**代码不在这里**（私有），这里只放产物。

## 下载安装

到 [Releases](https://github.com/trivium-sys/ghost-agent-releases/releases) 取最新版的
`Ghost-Agent-<版本>-arm64.dmg`（Apple Silicon），打开拖进「应用程序」即可。

包带 Developer ID 签名与 Apple 公证，不会报「已损坏」。

## 自动更新

装好之后不用再来这里——App 启动时会自动检查更新，有新版会下载并在下次启动时装上。
也可以从菜单栏手动「检查更新」。

## 每个版本包含

| 文件 | 用途 |
|------|------|
| `Ghost-Agent-<版本>-arm64.dmg` | 首次安装 |
| `Ghost-Agent-arm64.zip` | 自动更新用（别手动下） |
| `latest-mac.yml` | 更新清单（electron-updater 读它判断有没有新版） |
| `*.blockmap` | 增量下载用，省流量 |

## 系统要求

macOS · Apple Silicon（M 系列）。暂无 Intel 版。
