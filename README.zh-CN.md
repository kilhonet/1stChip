# 1stChip

**一眼看清电脑配置与驱动。**

[English](README.md) · [한국어](README.ko.md) · 简体中文 · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> 本文档为译文。如有出入，以[英文版](README.md)为准。

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/1stchip?lang=zh)

<!-- screenshot: images/main.png -->

## 简介

1stChip 在一个界面上显示电脑内部的硬件——CPU、主板、显卡、多媒体、网卡及其他设备——并同时列出每个设备已安装驱动的版本和日期。

即使在刚装好的 Windows 上也能使用：尚未安装驱动、在设备管理器中只显示为"未知设备"的硬件，也会连同制造商一起出现在列表中。重装系统后想知道还缺哪些驱动时，这一点特别方便。

解压即用。无需安装，无需管理员权限，也不需要安装任何其他组件。

## 主要功能

- **单屏硬件摘要** — CPU、主板、显卡、多媒体、网卡、其他设备，均带有制造商标志。
- **已安装驱动的版本和日期**，显示在设备名称下方。
- **无驱动也能识别** — 未安装驱动的设备同样会连同制造商一起列出，并标记 `!`。
- **驱动更新检查** — 将列表与 1stChip 服务器比对；若已知有更新的驱动，会标记该设备，鼠标悬停可查看可用版本。
- **一键打开驱动页面** — 点击 `!` 标记即可打开该设备的驱动页面。
- **系统信息栏** — 底部显示 CPU 频率、内存总量以及 Windows 版本。
- **合并重复设备** — 相同设备只显示一次，以 `(×N)` 表示数量。
- **便携** — 只有一个 EXE 文件，可以放在 U 盘里随身携带。
- **无需管理员权限。**
- **跟随 Windows 设置** — 深色/浅色模式跟随 Windows 应用主题；界面语言跟随 Windows 显示语言（英语、韩语）。

## 下载 / 安装

| 类型 | 链接 |
|---|---|
| 安装版 | [下载](https://down.kilho.net/1stchip?lang=zh) |
| 便携版 (ZIP) | [下载](https://down.kilho.net/1stchip?lang=zh&nosetup) |

1stChip 可作为**便携**应用使用：下载 ZIP，解压到任意位置，运行 `1stChip.exe` 即可，无需安装。从 U 盘直接运行也没有问题。

## 使用方法

1. 运行 `1stChip.exe`，硬件列表会立即显示。
2. 每个类别下列出其设备；第一行是代表设备，其余以灰色显示。
3. 设备名称下方显示**已安装**驱动的版本和日期。
4. 设备旁的黄色 `!` 表示以下情况之一：
   - 未安装驱动，或
   - 设备报告了问题代码，或
   - 已知有更新的驱动——鼠标悬停可查看版本。
5. **点击** `!` 标记，会在浏览器中打开该设备的驱动页面。
6. 底部面板显示 CPU 频率、内存大小和操作系统。

程序同时只运行一个实例；再次启动时会把已打开的窗口置于前台。

## 设置

没有设置窗口。1stChip 会自动跟随 Windows 设置：

| 项目 | 依据 |
|---|---|
| 浅色 / 深色模式 | Windows *设置 → 个性化 → 颜色 → 应用模式* |
| 界面语言 | Windows 显示语言（韩语 → 韩语，其他 → 英语） |
| 日期格式 | 按语言本地化（韩语 `yyyy-mm-dd`，英语 `mm-dd-yyyy`） |

## 系统要求

- Windows 10 或 Windows 11，**64 位**
- 无需管理员权限
- 网络连接可选——仅用于驱动更新检查

## 更新

1stChip **不会**自动更新。新版本经内部验证后手动发布，并在 [1stChip 页面](https://v2.kilho.net/zh/1stchip)公告。请参阅[更新政策说明](https://en.kilho.net/archives/notice/2940)。

**版本历史**

| 版本 | 日期 | 说明 |
|---|---|---|
| 0.9.0 | 2026-09-18 | 首次发布 |

## 许可

1stChip 是**免费软件（Freeware）**。

您可以在任何地方使用——家庭、办公室、学校、政府机关——并可以未经修改的形式自由再分发。

## 链接

- 网站：<https://v2.kilho.net/zh/1stchip>
- 论坛：<https://groups.google.com/g/kilhonet>
- X (Twitter)：<https://www.twitter.com/kilhonet>

© KILHO.NET
