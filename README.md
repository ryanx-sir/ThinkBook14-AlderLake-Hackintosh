# ThinkBook14+ 2022 macOS Ventura with OpenCore

# Details
| OpenCore Version | 0.9.8 |
| --- | --- |
| macOS Version | 13.6 (Ventura) |
| SMBios | MacBookPro16,1 |

# Hardware Specifications

| Hardware | Specification | Status |
| --- | --- | --- |
| CPU | Intel Core i7-12700H | ✅ Working |
| RAM | LPDDR5 32GB | ✅ Working |
| Audio | Realtek ALC257 | 🔶 In progress |
| WiFi | Intel AX201 | ✅ Working |
| Bluetooth | AX201 | ✅ Working |
| SSD | SAMSUNG PM9A1 512GB | ✅ Working |
| Keyboard | - | ✅ Working |
| Trackpad | ELAN0662 I2C(force-polling mode) | ✅ Working |
| Webcam | Microdia RGB IR HD camera | 🔶 In progress |
| MicroSD Card | RTS5260 Card Reader | 🔶 In progress |
| GPU | Intel Iris Xe Graphics | ❌ Not Working |
| eGPU | AMD Sapphire Radeon RX6650XT | 🔶 In progress |

# Overview

With this configuration it is possible to install and run macOS Ventura with eGPU.

# issue
CFG Lock: both modGRUBShell.efi and ru.efi unlock fail: write variable failed 0x00000008
    0xCA60C 	VarStoreEFI: VarStoreId: 0x3 [B08F97FF-E6E8-4193-A997-5E9E9B0ADB32], Attrubutes: 7, Size: 379, Name: CpuSetup {26 23 03 00 FF 97 8F B0 E8 E6 93 41 A9 97 5E 9E 9B 0A DB 32 07 00 00 00 79 03 43 70 75 53 65 74 75 70 00}
    0xCFC8F 		One Of: CFG Lock, VarStoreInfo (VarOffset/VarName): 0x43, VarStore: 0x3

# BIOS Settings

Secure Boot: Disabled
STAT Controller Mode: AHCI
orther All Default Setting.

