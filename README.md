# Meshy Mac

Yet another collection of OpenCore configuration files that allow me to run macOS on my desktop PC.
I'm using Opencore [0.9.1](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.9.1) and macOS Ventura (13.3).

<div align="center">
    <img alt="About Meshy Mac" src='./about-meshy-mac.png'>
</div>

## PC Specs

| Component | Description                              |
| --------: | :--------------------------------------- |
|       CPU | AMD Ryzen 5 3600                         |
|        MB | Gigabyte B550I AORUS PRO AX (rev. 1.0)   |
|       RAM | Crucial Ballistix 16GB DDR4 3600MHz CL16 |
|       GPU | ASUS Dual series Radeon RX 580 8GB       |
|       SSD | SATA based                               |
| WIFI & BT | Intel Wi-Fi 6 AX200 (onboard)            |
|       LAN | Realtek 2.5GbE                           |
|     Audio | ALC1220-VB                               |

---
## Issues

Everything seems to work ok, except:

- I have an NVMe drive (SK Hynix) - currently unsupported and is causing issues
- Boot time is long (~1 minute) - The NVMe drive is causing delays (because of dual boot I haven't disabled it)
