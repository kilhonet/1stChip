# 1stChip

**See your PC specs and drivers at a glance.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/1stchip?lang=en)

<!-- screenshot: images/main.png -->

## Overview

1stChip shows what is inside your PC — CPU, mainboard, graphics card, multimedia, network card and other devices — on a single screen, together with the driver version and date installed for each one.

It works even on a freshly installed Windows: a device is listed with its manufacturer even when no driver is installed yet and Device Manager only shows "Unknown device". That makes it handy right after a clean install, when you need to find out which drivers are still missing.

Just unzip and run. No installation, no administrator rights, nothing else to install.

## Features

- **One-screen hardware summary** — CPU, Mainboard, Graphics card, Multimedia, Network card and Other devices, each with the manufacturer's logo.
- **Installed driver version and date** for every device, shown under the device name.
- **Works without drivers** — devices with no driver are still listed with their manufacturer and marked `!`.
- **Driver update check** — the list is compared against the 1stChip server; when a newer driver is known, the device is marked and a tooltip shows the available version.
- **One click to the driver page** — click the `!` mark to open the driver page for that device.
- **System line** at the bottom: CPU clock, total memory and Windows edition/version.
- **Duplicate devices are merged** — identical devices appear once as `(×N)`.
- **Portable** — a single EXE you can carry on a USB drive.
- **No administrator rights needed.**
- **Follows Windows** — dark or light mode from the Windows app theme; UI language from the Windows display language (English, Korean).

## Download / Installation

| Package | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/1stchip?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/1stchip?lang=en&nosetup) |

1stChip is available as a **portable** app: download the ZIP, unzip it anywhere and run `1stChip.exe` — no installation needed. It also runs fine from a USB drive.

## Usage

1. Run `1stChip.exe`. Your hardware list appears immediately.
2. Each category shows its devices; the first line is the representative device, the rest are shown in grey.
3. Under each device name you see the **installed** driver version and date.
4. A yellow `!` next to a device means one of:
   - no driver is installed, or
   - the device reports a problem code, or
   - a newer driver is known — hover to see the version.
5. **Click** the `!` mark to open the driver page for that device in your browser.
6. The bottom panel shows CPU clock, memory size and operating system.

Only one instance runs at a time; launching it again brings the existing window to the front.

## Configuration

There is no settings window. 1stChip follows Windows automatically:

| Item | Source |
|---|---|
| Light / dark mode | Windows *Settings → Personalization → Colors → App mode* |
| UI language | Windows display language (Korean → Korean, everything else → English) |
| Date format | Localized (`yyyy-mm-dd` for Korean, `mm-dd-yyyy` for English) |

## Requirements

- Windows 10 or Windows 11, **64-bit**
- No administrator rights required
- An internet connection is optional — used only for the driver update check

## Updates

1stChip does **not** update itself. New versions are released manually after internal verification, and are announced on the [1stChip page](https://v2.kilho.net/en/1stchip). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

**Version history**

| Version | Date | Notes |
|---|---|---|
| 0.9.0 | 2026-09-18 | First release |

## License

1stChip is **Freeware**.

You may use it anywhere — at home, at the office, in schools and government offices — and redistribute it freely in its unmodified form.

## Links

- Website: <https://v2.kilho.net/en/1stchip>
- Forum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
