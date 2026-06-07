<div align="center">

<!-- TODO: replace with your logo. A simple wordmark or the deck render works great. -->
<!-- ![OBI-Deck logo](docs/images/logo.png) -->

# 🎛️ OBI-Deck

### The open-source, 3D-printed macro deck with magnetic modular keys.

Rearrange your layout by hand — every key snaps into place with magnets. No tools, no soldering, no closed firmware. Powered by the ESP32‑S3 and built for a fraction of the cost of a commercial stream deck.

<!-- TODO: this GIF is the single most important thing on the page. -->
<!-- Use a 3-5s clip of the keys snapping on/off magnetically — the same shot that went viral. -->
<!-- ![OBI-Deck magnetic snap demo](docs/images/snap-demo.gif) -->

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-in%20active%20development-orange.svg)](#-roadmap)
[![GitHub stars](https://img.shields.io/github/stars/OpenBricx/OBI-Deck?style=social)](https://github.com/OpenBricx/OBI-Deck/stargazers)
<!-- TODO: add once live → [![Discord](https://img.shields.io/discord/YOUR_SERVER_ID?label=Discord&logo=discord)](https://discord.gg/YOUR_INVITE) -->

**[YouTube](https://www.youtube.com/@OpenBricx)** · **[Instagram](https://www.instagram.com/OpenBricx)** · **Discord** *(coming soon)*

</div>

---

> [!IMPORTANT]
> **OBI-Deck is under active development.** The hardware design is built and working, and the source files, build guide, and firmware are being prepared for public release. If you found this from the demo and want to build one — **⭐ star and 👁️ watch this repo**, and **Subscribe To Our YouTube Channel**, so you're notified the moment files drop. Follow the [roadmap](#-roadmap) below for live status.

---

## ✨ What makes it different

- 🧲 **Magnetic modular keys** — pull a key off and snap it somewhere else. Reconfigure your layout in seconds, by hand.
- 🔓 **Truly open source** — hardware, firmware, and the companion app. No locked bootloaders, no walled garden.
- 💰 **Built from cheap, easy-to-get parts** — an ESP32‑S3 and components you can source anywhere.
- 🖥️ **Cross-platform companion app** — configure everything from the **OpenBricx Console** (Windows, macOS, Linux, Android, iOS).
- 🛠️ **3D-printable** — print the whole enclosure yourself. Repairable and remixable.
- 🧩 **Part of a bigger ecosystem** — OBI-Deck is the first product in the [OpenBricx](#-the-openbricx-ecosystem) modular family.

## 🆚 Why not just buy one?

|                              | **OBI-Deck**       | Commercial decks |
| ---------------------------- | :----------------: | :--------------: |
| Open source (hw + fw + app)  | ✅                 | ❌               |
| Magnetic, rearrangeable keys | ✅                 | ❌               |
| 3D-printable & repairable    | ✅                 | ❌               |
| Hackable firmware            | ✅                 | ❌               |
| Cross-platform app           | ✅                 | ⚠️ varies        |
| Cost                         | ~cost of parts     | $$$              |

<!-- TODO: once your BOM is final, replace "~cost of parts" with your real build cost, e.g. "~₹X / ~$Y". Real numbers are your strongest selling point. -->

---

## 🧰 Hardware

<!-- TODO: confirm/edit these specs to match your final V1. -->

| | |
| --- | --- |
| **MCU** | ESP32‑S3 |
| **Connectivity** | USB‑HID + Wi‑Fi / BLE |
| **Keys** | Magnetically attached, hot-swappable modules |
| **Enclosure** | Fully 3D-printed |
| **License** | GPL‑3.0 (hardware + firmware) |

### Bill of Materials
📋 *Coming soon* — full parts list with sourcing links will be published with the V1 release.

### 3D-printable files
📋 *Coming soon* — STLs (and source CAD) will be released here under `/hardware`.

---

## 🔧 Building one

🚧 **The full build guide is in progress.** It will cover printing, sourcing parts, assembly, and flashing — start to finish, no IDE required.

Flashing will be done straight from the **OpenBricx Console** (our companion app), so you won't need to touch the Arduino IDE or esptool. Just plug in over USB and click flash.

> Want to be first in line? ⭐ **Star** this repo and join the **Discord** *(link coming soon)*.

---

## 💻 Companion App — OpenBricx Console

OBI-Deck is configured through the **OpenBricx Console**, a single cross-platform app for the whole OpenBricx ecosystem. Set key actions, customize lighting, remap your layout, and push firmware updates over Wi‑Fi.

🚧 *In active development.* The Console will live in its own repo under the [OpenBricx](https://github.com/OpenBricx) org — watch the org to catch it.

---

## 🗺️ Roadmap

Honest status — no vaporware.

| Status | Milestone |
| :---: | --- |
| ✅ | V1 hardware design |
| ✅ | Magnetic key mechanism |
| 🚧 | Firmware (refining toward release) |
| 🚧 | OpenBricx Console companion app |
| 🚧 | Documentation & build guide |
| 📋 | Public release: STLs, BOM, source |
| 📋 | Tindie kits & pre-made boards |
| 📋 | Console plugin system (multi-product) |

---

## 🧩 The OpenBricx Ecosystem

OBI-Deck is the first product in **OpenBricx** — an open-source, 3D-printed, ESP32-powered ecosystem of modular hardware. The goal: open alternatives to premium closed products, at the cost of parts, that anyone can build and hack.

Also in the works:

- 💡 **Lights** — modular addressable LED controller
- 🤖 **Robotics board** — a modular motor/servo carrier (open alternative to closed RC/robotics kits)
- ⌨️ **Keyboard & mouse** — open input peripherals
- …and more, all sharing one companion app and one design language.

> ⭐ **[Follow the OpenBricx org](https://github.com/OpenBricx)** to see every product as it lands.

---

## 🤝 Contributing

The codebase isn't public yet, but contributors are exactly who this project is for. Right now the most helpful things you can do:

- ⭐ **Star** and 👁️ **watch** the repo (it genuinely helps visibility)
- 💬 **Join the Discord** *(coming soon)* and share ideas, mods, and feedback
- 🐛 **Open an [issue](https://github.com/OpenBricx/OBI-Deck/issues)** with questions, suggestions, or feature requests

Full contribution guidelines (`CONTRIBUTING.md`) will land with the source release.

---

## ❤️ Support the project

OpenBricx is built independently and funded out of pocket. If you'd like to help keep it going:

- 💖 [**GitHub Sponsors**](https://github.com/sponsors/OpenBricx)
- ☕ **Buy Me a Coffee** <!-- TODO: add your link -->

Even a star or a share helps more than you'd think. 🙏

---

## 📜 License

OBI-Deck is released under the **[GNU GPL‑3.0](LICENSE)**. You're free to use, modify, and distribute it — but derivative works must remain open source under the same license. Keeping the ecosystem open is the whole point.

<div align="center">

**Built in the open. 🛠️ Powered by ESP32. 🔋**

[YouTube](https://www.youtube.com/@OpenBricx) · [Instagram](https://www.instagram.com/OpenBricx) · [GitHub](https://github.com/OpenBricx)

</div>
