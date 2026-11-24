# 余音 · Reverb

> 余音绕梁，隽永悠长。 · *Every echo lingers.*

一款轻量的多端播客客户端，四个原生端：**Android**(Kotlin / Compose)、**HarmonyOS**(ArkTS / ArkUI)、**macOS**(Swift / SwiftUI)、**iOS**(Swift / SwiftUI)。水墨底 + 青瓷 + 梁金配色，图标以「金色横梁 + 环绕向上的声波」诠释「余音绕梁」。

---
本仓库提供四个端的安装包。iOS 的常规分发仍走 TestFlight；GitHub 上的是明确标注的开发签名测试包，不是 TestFlight 安装包。

## 当前版本：1.1.0（2026-11-24）

下载：[Releases](https://github.com/cxyxlxdm/reverb-cast/releases/latest)

| 文件 | 平台 | 大小 | SHA-256 |
|---|---|---:|---|
| `reverb.apk` | Android | 270,327,060 B | `7c18e84c12ae7399ab920fd59c446fc7424584e96c3aefba227146d39e67da73` |
| `Reverb.dmg` | macOS（universal：Intel 与 Apple 芯片同一份） | 6,842,799 B | `c208619bc372a7736bd3b88d76fc9ea97dac2c9d0b065066e0a07f043fcea266` |
| `reverb-ios-1.1.0-4-development-signed.ipa` | iOS 开发签名测试包 | 3,291,567 B | `983344f1cde568e8e3c758ff0a71797d52b037155a0734cbaaed1cd019f86105` |
| `reverb-harmony-1.1.0.app.zip` | HarmonyOS（解压后得到 `reverb.app`） | 181,877,498 B | `cabbb625fd2254aedad003f0cda2a1367cf8bd1dc646f54e85be5464dedd1740` |
| `reverb-symbol.zip` | HarmonyOS 崩溃栈还原符号包 | 14,975,663 B | `f9bb27801e4e9264288cee25dadd45e13a51211305c8056bf9012ca2f1643fad` |

下载后可自行核对：`shasum -a 256 <文件>`，应与上表逐字相同。

> Android 安装包自 1.0.8 起约 270 MB：离线语音识别改用 SenseVoice 模型，模型随包提供，装完即离线可用。
>
> iOS 开发签名包只能安装到描述文件登记的测试机，有效期为 2026-11-30，**不是 TestFlight 安装包**。
