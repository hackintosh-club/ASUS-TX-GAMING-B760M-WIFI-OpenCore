# [ASUS-TX-GAMING-B760M-WIFI](https://github.com/hackintosh-club/ASUS-TX-GAMING-B760M-WIFI-OpenCore)  黑苹果 OpenCore EFI

![image](ScreenShot/Motherboard.jpg)

### [English](README.EN.md)

[OpenCore 0.9.9](https://github.com/acidanthera/OpenCorePkg)

### 可安装系统

- macOS Sonoma 14.x
- macOS Ventura 13.x
- macOS Monterey 12.x

### 硬件

- 主板: ASUS-TX-GAMING-B760M-WIFI-D4
- Bios版本: 1604（12/15/2023）
- 处理器: 英特尔12代 i5-12600KF
- 内存: 光威 2x16GB DDR4 3600MHz
- 硬盘: 铠侠 EXCERIA G2 1TB Windows
- 硬盘: 铠侠 EXCERIA G2 1TB MacOS
- 硬盘: 希捷 ST1000DM010-2EP102  1TB HDD
- 独显: 华擎 AMD Radeon RX 6800 Phantom Gaming D 16G OC
- 声卡: 瑞昱 ALC897
- 网卡: 瑞昱 2.5Gbe 有线网卡
- 无线：Fenvi T919 + Intel AX201

### Bios 设置

| 名称               | 选项     |      | 名称          | 选项     |
| ------------------ | -------- | ---- | ------------- | -------- |
| VT-d               | Enabled  |      | XHCI-Hand-Off | Enabled  |
| Above 4G Decoding  | Enabled  |      | Fast Boot     | Disabled |
| CSM                | Disabled |      | Secure Boot   | Disabled |
| Resize Bar Support | Enabled  |      |               |          |

### 注意事项

- 使用[OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools/releases) 或 [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 生成 SMBIOS
- 如需使用有小核心的CPU，必须勾选配置文件中Kernel--ProvideCurrentCpuinfo选项

### 参考内容

[1.黑苹果安装过程演示](https://hackintosh.club/d/10000060)

[2.英特尔无线网卡WiFi驱动](https://hackintosh.club/d/10000015)

[3.英特尔无线网卡蓝牙驱动](https://hackintosh.club/d/10000017)

[4.我的B站黑苹果教程](https://space.bilibili.com/244390800/video)

[6.黑果之家](https://hackintosh.club)

### 联系我们

- QQ群: 23304408

![image](ScreenShot/QRCode.png)