# 余音 · Reverb

> 余音绕梁，隽永悠长。 · *Every echo lingers.*

一款轻量的多端播客客户端，四个原生端：**Android**(Kotlin / Compose)、**HarmonyOS**(ArkTS / ArkUI)、**macOS**(Swift / SwiftUI)、**iOS**(Swift / SwiftUI)。水墨底 + 青瓷 + 梁金配色，图标以「金色横梁 + 环绕向上的声波」诠释「余音绕梁」。

---
本仓库提供 Android 端和 macOS 端的安装包。HarmonyOS 端可以在华为应用商店下载；iOS 的正式分发走 TestFlight。

## 当前版本：1.0.9（2026-11-22）

下载：[Releases](https://github.com/cxyxlxdm/revert-cast/releases/latest)

| 文件 | 平台 | 大小 | SHA-256 |
|---|---|---|---|
| `reverb.apk` | Android | 270,294,292 B | `e5ba9a0720b840119daaef1a51c133ea6e27c167fb579258a277aea41c360bec` |
| `Reverb.dmg` | macOS（universal：Intel 与 Apple 芯片同一份） | 6,622,867 B | `d48502ad57d3745086dd3a0b9100744b5ed1347bdfd5f4fe122c44152ee6505a` |

下载后可自行核对：`shasum -a 256 <文件>`，应与上表逐字相同。

> Android 安装包自 1.0.8 起约 270 MB：离线语音识别改用 SenseVoice 模型，模型随包提供，装完即离线可用。
