# 🕷️ Spider-Man — Bruce Theme

<p align="center">🇺🇸 <b>English</b> · 🇫🇷 <a href="README.fr.md">Français</a></p>

[![Bruce firmware](https://img.shields.io/badge/firmware-Bruce-8A2BE2?logo=github)](https://github.com/BruceDevices/firmware) [![Device](https://img.shields.io/badge/device-LilyGO%20T--Embed%20CC1101-1E90FF)](https://github.com/BruceDevices/firmware) [![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

A **Spider-Man** UI theme for the **[Bruce firmware](https://github.com/BruceDevices/firmware)** on the LilyGO T-Embed CC1101 (320×170). Big white picto of the current menu on the left, its name beside it in the classic comic font, with the previous / next menu names above and below — all laid out to the left of Spider-Man.

![Spider-Man theme](docs/hero.png)

| 🖥️ On the device |
|:---:|
| ![on device](docs/device.jpg) |

## ✨ Details

- 🕸️ **Large current picto** on the left (white, bold strokes), name **beside it** in **The Amazing Spider-Man** font.
- 🔠 **Previous / next** menus as text only (smaller), above / below, centered on the current name.
- 🎯 Layout tuned so that even the longest label (**ETHERNET**) fits without touching the picto or Spider-Man.
- 🔢 Neighbours drawn in the **real order** of the Bruce T-Embed CC1101 menu (FM included). *Note: the font turns digits into spiders → "NRF24" is shown as "NRF".*

![grid](docs/grid.png)

## 📦 Contents

**4 sizes** × **16 PNGs** + `.json`:

| Folder | Image | Target screen |
|---|---|---|
| `105px/` | 240×105 | M5StickC Plus (240×135) |
| `140px/` | 320×140 | **T-Embed CC1101 / Cardputer (320×170)** |
| `180px/` | 320×180 | ~320×210 screens |
| `192px/` | 320×192 | ~320×222 screens |

> ℹ️ **Status bar** — Bruce reserves **30 px at the top**. Size = screen height − 30 → **T-Embed CC1101 = `140px`**.

## 🚀 Installation

1. Copy the **`Spiderman`** folder to the root of the SD card.
2. On the device: **Config → UI Theme → `Spiderman/140px/Theme_Spiderman.json`**.
3. Over WiFi: **Files → WebUI**, upload the folder, then select the `.json`.

## 🛒 Hardware

*Amazon affiliate links: if you buy through these links, the project earns a small commission at no extra cost to you.*

<table>
<tr>
<td align="center" width="33%">
  <a href="https://www.amazon.com/dp/B0D45MSMJR?linkCode=ll2&amp;tag=koua29bspidermanthem-20&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0D45MSMJR.jpg" width="200" alt="Anker 545 power bank (10,000 mAh)"></a><br>
  <b><a href="https://www.amazon.com/dp/B0D45MSMJR?linkCode=ll2&amp;tag=koua29bspidermanthem-20&amp;ref_=as_li_ss_tl">Anker 545 power bank (10,000 mAh)</a></b><br><sub>Keeps the T-Embed running away from an outlet</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&amp;tag=koua29bspidermanthem-20&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0C1FCZM94.jpg" width="200" alt="433 MHz SMA antenna (2-pack)"></a><br>
  <b><a href="https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&amp;tag=koua29bspidermanthem-20&amp;ref_=as_li_ss_tl">433 MHz SMA antenna (2-pack)</a></b><br><sub>Sub-GHz antenna for the CC1101 radio</sub>
</td>
<td align="center" width="33%">
  <a href="https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&amp;tag=koua29bspidermanthem-20&amp;ref_=as_li_ss_tl"><img src="docs/amazon-B0B7NVMBPL.jpg" width="200" alt="SanDisk 64 GB microSD (2-pack)"></a><br>
  <b><a href="https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&amp;tag=koua29bspidermanthem-20&amp;ref_=as_li_ss_tl">SanDisk 64 GB microSD (2-pack)</a></b><br><sub>For Bruce themes, scripts and captures</sub>
</td>
</tr>
</table>

<sub>As an Amazon Associate I earn from qualifying purchases.</sub>

## 🎨 Credits

- Theme by **koua29**. Rendering font: **The Amazing Spider-Man** (SpideRaYsfoNtS, free for personal use — **not included** in this repository).
- Runs on the excellent **[Bruce firmware](https://github.com/BruceDevices/firmware)**.

## ☕ Buy me a coffee

<img src="docs/paypal-qr.png" width="180" alt="PayPal" />

## 📄 License

Repository assets under **MIT** (see [LICENSE](LICENSE)). **Spider-Man and Marvel are trademarks of Marvel/Disney**; **unofficial fan project**, not affiliated, non-commercial.
