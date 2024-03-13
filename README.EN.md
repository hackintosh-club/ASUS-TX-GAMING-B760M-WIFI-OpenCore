# [ASUS-TX-GAMING-B760M-WIFI](https://github.com/hackintosh-club/ASUS-TX-GAMING-B760M-WIFI-OpenCore) Hackintosh OpenCore EFI

![image](ScreenShot/Motherboard.jpg)

### [简体中文](https://github.com/hackintosh-club/ASUS-TX-GAMING-B760M-WIFI-OpenCore)

[OpenCore 0.9.9](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Sonoma   14.x
- macOS Ventura    13.x
- macOS Monterey 12.x

### Hardware

- Motherboard: ASUS-TX-GAMING-B760M-WIFI-D4
- Bios Version: 1604（12/15/2023）
- CPU: Intel 12th i5-12600KF
- RAM: Gloway 2x16GB DDR4 3600MHz
- SSD：KIOXIA EXCERIA G2 1TB Windows
- SSD：KIOXIA EXCERIA G2 1TB MacOS
- HDD:  Seagate ST1000DM010-2EP102  1TB
- GPU: ASROCK AMD Radeon RX 6800 Phantom Gaming D 16G OC
- Audio: Realtek ALC897
- Ethernet: Realtek 2.5GbE Family Controller
- Wireless: Fenvi T919 + Intel 

### Bios Setup

| Name               | Option   |      | Name          | Option   |
| ------------------ | -------- | ---- | ------------- | -------- |
| VT-d               | Enabled  |      | XHCI-Hand-Off | Enabled  |
| Above 4G Decoding  | Enabled  |      | Fast Boot     | Disabled |
| CSM                | Disabled |      | Secure Boot   | Disabled |
| Resize Bar Support | Enabled  |      |               |          |

### Notes

- Use[OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools/releases) or [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your SMBIOS
- If you want to use a CPU without Efficient-Core, you must uncheck the option in the config.plist file Kernel--ProvideCurrentCpuinfo

### Contact Us

- QQ Group: 23304408

![image](ScreenShot/QRCode.png)
