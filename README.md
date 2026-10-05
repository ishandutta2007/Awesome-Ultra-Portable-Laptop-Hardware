# Awesome-Ultra-Portable-Laptop-Hardware

## Top Ultra-Portable Laptop Hardware Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Lightweight Linux Laptops, Open Firmware & Repairable Hardware*  

**Last updated: October 2026**



This repository tracks notable **commercial ultra-portable laptops** and **open-source hardware projects** that prioritize repairability, Linux compatibility, and open firmware. These tools range from sub-1 kg Linux-first machines to fully open-source DIY laptops where every schematic and PCB file is available.



**Examples** include Microsoft Surface Laptop Go, Apple MacBook Air M2, ASUS Zenbook S 13 OLED, Dell XPS 13, Acer Swift Edge 16, Lenovo ThinkPad Nano, HP Pavilion Aero 13, LG Gram 14, Samsung Galaxy Book3, and Fujitsu Lifebook UH-X (the category leaders).



**Open-source emphasis**: The open-source hardware movement for ultra-portable laptops is anchored by **System76** (Linux-first with coreboot firmware), **Framework** (fully repairable and modular), and **Olimex TERES-I** (complete DIY open hardware). **Libreboot** provides free boot firmware for compatible laptops. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Apple MacBook Air M2](https://www.apple.com/macbook-air/)**  

  The benchmark for ultra-portable laptops with Apple Silicon efficiency, fanless design, and exceptional battery life. **Closed hardware** with soldered RAM and storage — not repairable or upgradeable.



- **[Dell XPS 13](https://www.dell.com/xps13)**  

  Premium Windows ultrabook with InfinityEdge display and compact footprint. **Historically user-upgradeable RAM/SSD** in some models, though newer iterations increasingly solder components.



- **[Lenovo ThinkPad X1 Nano](https://www.lenovo.com/thinkpad-x1-nano)**  

  Sub-1 kg business laptop with ThinkPad keyboard and durability. **Best-in-class keyboard** for ultra-portable form factor.



- **[ASUS Zenbook S 13 OLED](https://www.asus.com/zenbook-s-13-oled/)**  

  Ultra-light OLED ultrabook with premium build quality. **Windows-only** with soldered components.



- **[LG Gram 14](https://www.lg.com/gram)**  

  Featherweight laptop with exceptional battery life and MIL-STD durability. **Windows-only** with limited repairability.



- **[Acer Swift Air 14](https://www.acer.com/swift-air/)**  

  New for 2026, weighing 1.25 kg with up to 19 hours video playback and Intel Core Series 3 processors. **Windows-only** with soldered RAM .



- **[Samsung Galaxy Book3](https://www.samsung.com/galaxy-book/)**  

  Premium ultrabook with AMOLED display and Galaxy ecosystem integration. **Windows-only**.



- **[HP Pavilion Aero 13](https://www.hp.com/pavilion-aero/)**  

  Affordable sub-1 kg laptop with AMD Ryzen options. **Windows-only** with soldered RAM.



- **[Fujitsu Lifebook UH-X](https://www.fujitsu.com/lifebook-uh-x/)**  

  Japanese ultra-portable with exceptional build quality and lightweight design. **Limited availability** outside Japan.



## Open-Source GitHub Projects



- **[System76 Lemur Pro](https://system76.com/laptops/lemur-pro)**  

  **The lightest Linux-first ultraportable laptop available**, with 14-inch model weighing just **0.998 kg** and 16-inch at 1.34 kg . Features **open-source Coreboot-based firmware** replacing proprietary BIOS, with full user control over power management and thermals . Powered by **Intel Core Ultra Series 3 "Panther Lake"** processors with up to 50 TOPS NPU, **32 GB LPDDR5X RAM**, and up to **4 TB NVMe SSD** . Boasts **up to 18 hours of continuous operation** — the longest runtime ever offered by System76 . Ships with **Pop!_OS with COSMIC desktop** or Ubuntu 24.04/26.04 LTS . Optional configuration allows **skipping Wi-Fi, Bluetooth, webcam, and microphone** for air-gapped security use cases . **The de facto open-source ultra-portable for Linux users** . Starting at $1,999 .



- **[Framework Laptop 13](https://frame.work/laptop13)**  

  **The leading repairable and modular ultra-portable laptop**, with all components user-replaceable and upgradable . **Socketed RAM and M.2 SSD** (not soldered), four swappable **Expansion Card** ports for USB-C, USB-A, HDMI, DisplayPort, Ethernet, and microSD . Battery, keyboard, touchpad, speakers, hinges, display, webcam, and **mainboard** are all replaceable . Framework has supported **generational mainboard upgrades**, allowing CPU platform refresh without replacing the entire laptop . Available with **Ubuntu Linux** pre-installed . Starting at **$899 for DIY Edition**, $1,099 pre-built . **Laptop 13 Pro** announced April 2026 with CNC aluminum chassis, haptic trackpad, and Intel Core Ultra Series 3 chips, starting at $1,199 DIY / $1,499 pre-built . **The most repairable ultra-portable available** — designed for 10+ year ownership .



- **[Olimex TERES-I](https://github.com/OLIMEX/DIY-LAPTOP)**  

  **Complete DIY Free/Open Source Hardware (FOSH) and Software (FOSS) laptop**, weighing **980 g** . Features **Allwinner A64 quad-core ARM Cortex-A53** CPU, 2 GB DDR3L RAM, 16 GB eMMC storage, and **11.6" 1366x768 LCD** . **Every hardware design file is open source** — schematics, PCB layout, and assembly manuals . Runs Linux (Ubuntu Mate pre-loaded) with support for Android and Windows . **Note: currently considered an evaluation board, not a finished consumer product** . **The most complete open-source laptop hardware project** for developers and hardware hackers.



- **[Libreboot](https://libreboot.org/)**  

  **Free and open-source boot firmware** based on coreboot, replacing proprietary BIOS/UEFI on specific Intel/AMD x86 and ARM laptops and desktops . **Provides regular tested releases with pre-compiled ROM images** for supported hardware . Designed to "Just Work" for non-technical users — automated build system and user-friendly installation instructions . **The de facto free firmware solution** for compatible laptops. Associated Project at SPI since September 2025 .



- **[noVa64](https://github.com/dmolinagarcia/nova64)**  

  **Open-source new-retro 16-bit laptop project** built around the **65816 CPU** (real silicon, not FPGA) . Envisioned as an alternate-universe successor to Commodore 8-bit computers . Features **640x400 resolution, 256 colors**, FPGA video and audio, USB peripherals, dual SD storage, and USB-C charging . **Fully open source under GNU GPLv3** — every design file and step logged . **Note: hobbyist project, not commercially viable — no deadline, learning-focused** .



- **[CyberFold](https://github.com/eggfly/cyberfold)**  

  **Pocketable Linux clamshell cyberdeck** resembling an oversized Game Boy Advance SP . Powered by **Raspberry Pi Compute Module** (CM4, CM5, or CM Zero) . Features **1024×768 capacitive touchscreen**, compact QWERTY keyboard based on **open-source Solder Party KeebDeck design**, stereo speakers, and full-size USB 3.0/USB 2.0 ports . **Touchpad doubles as secondary display** via ESP32-S3 showing battery and power data . **Design files not yet publicly released**, but maker community interest is high .



### Additional Strong Open-Source Options



- **Star Labs StarFighter** — Linux-first laptop with coreboot firmware and 4K display option, from UK-based Star Labs .

- **Purism Librem 14** — Security-focused Linux laptop with hardware kill switches for camera, microphone, and Wi-Fi.

- **Tuxedo InfinityBook** — Linux-first laptops from Germany with open firmware options.

- **Acer Swift Air 14** — New 2026 Windows ultraportable at 1.25 kg with 19-hour battery, Intel Core Series 3, and $699 starting price — the most affordable sub-1.3 kg option .

- **Geekom GeekBook X14 Pro** — Sub-1 kg full-metal laptop with OLED 2.8K display, Intel Core Ultra, and premium build quality from the mini-PC specialist .



**Frameworks for building custom ultra-portable solutions**: Choose based on priorities. **System76 Lemur Pro** for the lightest Linux-first experience with open firmware and 18-hour battery . **Framework Laptop 13** for maximum repairability, upgradeability, and 10+ year ownership . **Olimex TERES-I** for complete hardware sovereignty and DIY assembly . **Libreboot** for free boot firmware on compatible existing hardware . **noVa64** and **CyberFold** for maker-driven experimental projects . Note that **true commercial ultra-portables with integrated displays, batteries, and chassis** remain primarily proprietary; open-source projects provide strong foundations for Linux-first, repairable, and firmware-liberated computing that require varying levels of assembly or configuration.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Ultra-portable laptops involve trade-offs between weight, battery life, performance, and repairability. **No single device excels at everything**.

- **Open-source hardware projects (TERES-I, noVa64, CyberFold) are not commercial products** — they require assembly, configuration, and technical expertise. Evaluate maturity before relying on them for production use.

- **Libreboot and coreboot installation can brick unsupported hardware** — verify compatibility before flashing firmware.

- **Battery life claims are manufacturer estimates** — independent reviews may vary significantly.

- The open-source ecosystem provides strong Linux-first, repairable, and firmware-liberated foundations, but **integrated commercial ultra-portables** from Apple, Dell, Lenovo, and others remain primarily proprietary offerings.



---



**Made for Linux enthusiasts, repair advocates, and users seeking hardware sovereignty.**

Let's make ultra-portable laptops more open, transparent, and repairable.
