# 1stChip

**See your PC specs and drivers at a glance.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/1stchip?lang=en)

![1stChip screenshot](images/1stchip-ko.webp)

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

### The basic flow

1. Run `1stChip.exe`. The hardware list appears within a few seconds.
2. The list is grouped as **CPU → Mainboard → Graphics card → Multimedia → Network card → Other devices**. The first line in each category is the representative device; the rest follow in grey.
3. Under each device name you see the **installed driver version and date**.
4. A yellow `!` means there is something to look at. Hover to see why, and **click** it to open that device's driver page in your browser.
5. The bottom of the window shows the CPU clock, memory size and Windows version.

The list is read once at startup. After installing a driver, close and run 1stChip again to see the result.

### The window

| Part | What it shows |
|---|---|
| Logo | Manufacturer logo (initials for makers without a logo) |
| Device name | The name Windows assigned. Identical devices are grouped as `(×2)` |
| Second line | Installed driver version · date |
| `!` | No driver / problem / newer driver known — hover to tell which, click for the driver page |
| Bottom panel | CPU clock (base clock) · memory size · operating system |

### How to…

**You just installed Windows and don't know which drivers to install**
Run 1stChip and look for devices marked `!`. If hovering says "No driver is installed", that device is missing its driver. Click `!` to open the driver page, install, then run 1stChip again to check that the `!` is gone. If the PC has no internet because the network driver is missing, use 1stChip to read the network card's maker and model, then fetch the driver on another PC.

**Device Manager shows an "Unknown device"**
Device Manager cannot name a device without a driver, but 1stChip identifies the manufacturer and category without one. Find the device in its category and click `!`.

**Check whether your drivers are up to date**
When a newer driver is known, the device gets a `!` and hovering shows "You can update to version x.x.x". No `!` means it is current as far as is known.

**Check your PC specs quickly**
Read just the first line (representative device) of each category and you have the CPU, mainboard chipset, graphics card, sound and network card at a glance, with memory size and Windows version in the bottom panel. Handy when writing a for-sale listing or comparing against a game's recommended specs.

**Several identical devices**
Identical devices are grouped on one line with a count such as `(×2)`. Structural devices you never need to care about — USB hubs, internal bridges — are left out of the list.

**Checking many PCs**
1stChip needs no installation and no administrator rights, so keep it on a USB drive and run it on each PC. It leaves nothing behind on the PC it runs on.

**On a PC without internet**
The hardware list and installed driver details work fully offline. Only the "newer driver available" marks and the driver page opened by clicking `!` need an internet connection.

**The window is dark (or light), or in English**
1stChip follows Windows. Change dark/light under Windows *Settings → Personalization → Colors → App mode*, and the UI language via the Windows display language (Korean → Korean, everything else → English).

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

1stChip does **not** update itself. New versions are released manually after internal verification, and are announced on the [1stChip page](https://v2.kilho.net/1stchip). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

**Version history**

| Version | Date | Notes |
|---|---|---|
| 0.9.0 | 2026-09-18 | First release |

## License

1stChip is **Freeware**.

You may use it anywhere — at home, at the office, in schools and government offices — and redistribute it freely in its unmodified form.

## Links

- Website: <https://v2.kilho.net/1stchip>
- Forum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
