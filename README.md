# Asrock-B560M-HACKINTOSH

## Prerequisite

Devices Running Windows, MacOS or Linux
- Python [Here](https://www.python.org/)
- GenSMBIOS [Here](https://github.com/corpnewt/GenSMBIOS)
- Propper tree (for editing config to add serial number) [Here](https://github.com/corpnewt/ProperTree)
- EFI mounter tools (ex. Minitool Partition Wiz)
- Flashdrive 16GB or higher
- Balena Etcher [Here](https://www.balena.io/)
- MacOS Vanilla Images Ver(12 - 13) [Here](https://www.olarila.com/topic/6278-hackintosh-and-macintosh-olarila-vanilla-images-macos-installer/)

## Preview

<img src=https://github.com/Anemonastrum/Asrock-B560M-HACKINTOSH/blob/main/Screenshoot1.png width="auto" height="auto"/>

## Configuration

PC Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Mainboard model | Asrock B560M-HDV R2.0 |
| Processor | Intel Core i5-10400 (non F) Processor |
| Memory | 16GB PNY XLR8 DDR4 3600MHz XMP |
| Storage | ADATA NVMe SSD SX8200 Pro |
| Integrated Graphics | Intel UHD Graphics 620 |
| Dedicated Graphics | Asrock Challenger AMD Radeon RX 6600 XT 8GB |
| Sound Card | Realtek ALC897 (layout-id: 13) |
| Wireless Card | Broadcom BCM94360NG WIFI 5 |
| Ethernet | Intel I219V |

Bootloader Configuration

| Config | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Bootloader type | OpenCore |
| SMBIOS model | iMac20,1 |
| Supported MacOS | Monterey - Ventura |

BIOS Configuration

| Config | Detail                                                  |
| ------------------- | ------------------------------------------- |
| BIOS Type | UEFI |
| SATA Type | AHCI |
| XHCI Handoff | ON |
| Resizable Bar | ON |
| CFG LOCK | OFF |
| SR-IoV | OFF 
| VT-d | OFF |
| VT-x| ON |
| Trusted Platform | OFF |
| CSM | OFF |
| iGPU Multi Monitor | ON |


## Current Status

Stable Enough to be used as Daily Driver!

| Things | Status                                                  |
| ------------------- | ------------------------------------------- |
| Airdrop | Working |
| Sidecar | Working |
| iMessage | Working |
| Facetime | Working |
| AppleID | Working |
| DRM | Working |
| Sleep | Working |
| RX 6600 XT Acceleration | Working |
| Headless Intel UHD 620 | Working |
| Sound | Working |
| Wifi | Working |
| Bluetooth | Working |
| dGPU Display Out | Working |
| Onboard Display Out | Not Working |

## Installation

- Get all the Prerequisite
- Download the latest EFI release suitable for your MacOS Version want to install
- Configure the Serial Number, ETC to the config
- Flash the MacOS image to the flashdrive
- Mount the flashdrive EFI partition
- Copy the EFI configuration to the flashdrive EFI partition
- Unmount the flashdrive EFI parition
- Boot the flashdrive and install :)


