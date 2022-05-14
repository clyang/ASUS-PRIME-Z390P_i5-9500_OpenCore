# ASUS Prime Z390-P Hackintosh
This setting works perfectly on macOS Monterey (12.0.1) with OpenCore 0.8.0 and latest KEXTs.

## Replace following keys with `GenSMBIOS` tool
1. Open `OpenCore/EFI/OC` with [ProperTree](https://github.com/corpnewt/ProperTree)
2. Modify the following keys with your own
  * MLB
  * ROM
  * SystemSerialNumber
  * SystemUUID

**!!!! DONOT CHANGE `SystemProductName` !!!!!**

## Hardware
| Item | Brand | Model | Driver | Comment |
|-----|-----|-----|-----|-----|
| Motherboard | ASUS | Z390-P | | |
| CPU | Intel | i9-9500 | | |
| RAM | Micron | Ballistix Sport LT DDR4-3200 | | 16GB x 2 |
| iGPU | Intel | Ultra HD Graphics 630 | built-in | use DP port to output|
| SSD | Samsung | EVO970 PRO 415GB NVMe | built-in | |
| SATA Card | UpTech | SC342 (4 SATA ports) | built-in | Marvell 88SE9230 Chip. Inserted on PCI-e 2x slot|
| Wireless | Broadcom | BCM94360CD PCIe | built-in | FV-T919 |
| Bluetooth | Broadcom | BCM94360CD PCIe | built-in | FV-T919 |
| Ethernet | Realtek | RTL8111H | [RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases) | |
| Audio | Realtek | ALC892 | [AppleALC.kext](https://github.com/acidanthera/AppleALC) | |
| Case | Fractal | Define R6 | | |
| Monitor | Dell | U2419H | | DP+HDMI|
