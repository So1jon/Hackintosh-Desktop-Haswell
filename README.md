_________________________________________________________________________________________________________________________________________________

[![](https://img.shields.io/badge/Reposity-So1jon-informational?style=flat&logo=apple&logoColor=white&color=9debeb)](https://github.com/So1jon)
[![](https://img.shields.io/badge/Telegram-@Nusratov_Sobirjon-informational?style=flat&logo=telegram&logoColor=white&color=5fb659)](https://t.me/Nusratov_Sobirjon)
[![](https://img.shields.io/badge/Facebook-Nusratov_Sobirjon-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/Sobirjon.Nusratov)

_________________________________________________________________________________________________________________________________________________

### Guide Used - [OpenCore Desktop Haswell Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html)

### Bootloader : [OpenCore](https://github.com/acidanthera/OpenCorePkg) in [Project Acidanthera](https://github.com/acidanthera)

### Geekbench 6.1.0  Result Information: 
| iMacPro1,1            | Result  | ID Information                                                |
| --------------------- | -------- | ------------------------------------------------------------ |
| CPU Single-Core Score | 887      | [ID 1780635](https://browser.geekbench.com/v6/cpu/1780635)   |
| CPU Multi-Core Score  | 1739     | [ID 1780635](https://browser.geekbench.com/v6/cpu/1780635)   |
| dGPU Metal Score      | 44618    | [ID 624217](https://browser.geekbench.com/v6/compute/624217) |

_________________________________________________________________________________________________________________________________________________

### My computer hardware specifications:

| Components  | Name                                    |  Brand Links                                                                                                                        |
| ----------- | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Motherboard | Z87-DS3H v1.1                           | [Gigabayte](https://www.gigabyte.com/Motherboard/GA-Z87-DS3H-rev-11#ov)                                                             |
| CPU         | Intel® Core® i3 4130                    | [Intel Haswell](https://ark.intel.com/content/www/us/en/ark/products/77480/intel-core-i34130-processor-3m-cache-3-40-ghz.html)      |
| iGPU        | Intel® HD Graphics 4400                 | [Intel Haswell](https://ark.intel.com/content/www/us/en/ark/products/graphics/81497/intel-hd-graphics-4400.html#@Desktop)           |
| dGPU        | AMD Radeon RX 580 8GB                   | [Sapphire NITRO+](https://www.sapphiretech.com/ru-ru/consumer/nitro-rx-580-8g-g5)                                                   |
| Ram         | DDR3 16GB / 1600Mhz                     | [Kingston](https://www.kingston.com/dataSheets/KVR16N11S8_4.pdf)                                                                    |
| Storage     | SSD 480GB SATA III 6Gb/s                | [PNY CS900](https://www.pny.com.tw/en/products-detail/CS900-2-point-5-SSD/)                                                         |
| Ethernet    | RTL8111E-VL 1.0 Gigabit/s               | [Realtek](https://4ip.info/files/attachments/RTL8111E.pdf)                                                                          |
| Audio       | Codec ALC887                            | [Realtek](http://www.chipset-ic.com/datasheet/ALC887.pdf)                                                                           |
| USB Wi-Fi   | TL-WN725N V3                            | [TP-Link](https://www.tp-link.com/us/support/download/tl-wn725n/)                                                                   |
|USB Bluetooth| Cambridge Silicon Radio 4.0             | [CSR](https://en.wikipedia.org/wiki/CSR_plc)                                                                                        |
| USB Camera  | Z-Star Microelectronics Corporation     | [Vimicro](http://www.vimicro.com/english/product/pc001.htm)                                                                         |

_________________________________________________________________________________________________________________________________________________

### My computer is fully tested on the following operating systems:

| Name           | Version | Build      | Image links                                                                                                                                                                                                                                                       |
| -------------- | ------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| macOS Sonoma   | 14.0    | 23A5337a   | [DMG](https://drive.google.com/file/d/1FgkfiXhaKfVXMpzf8R4CbYFOnG7Ts5Q3/view?usp=sharing) / [pkg](https://swcdn.apple.com/content/downloads/14/54/042-41491-A_WCZEM7L2US/b5eeeylcnmf82ycto51pvy0klcyzd02on8/InstallAssistant.pkg)                                 |
| macOS Ventura  | 13.5.2  | 22G91      | [DMG](https://drive.google.com/file/d/1b5TlWf0vI17z9cWL0s3aLO7jWxnZoFwa/view?usp=sharing) / [rdr](https://rutracker.org/forum/viewtopic.php?t=6223477)                                                                                                            | 
| macOS Monterey | 12.6.9  | 21G726     | [app](https://drive.google.com/file/d/1tNgnxK6J5BH3KibsgdbE_8QEERit2xJC/view?usp=sharing) / [rdr](https://rutracker.org/forum/viewtopic.php?t=6066530)                                                                                                            |
| macOS Big Sur  | 11.7.10 | 20G1427    | [app](https://drive.google.com/file/d/1QQqPaeKqBuZv5LSfzOd_e2NiQHiR92D_/view?usp=sharing) / [rdr](https://rutracker.org/forum/viewtopic.php?t=5928524)                                                                                                            |
| Windows  11    | 23H2    | 22631.2338 | [ISO EN](https://comss.cloud/22631.2338.230906-1420.NI_RELEASE_SVC_BETAFLT_PROD1_CLIENTMULTI_X64FRE_EN-US_FIXED_2023_09_13.iso) / [ISO RU](https://comss.cloud/22631.2338.230906-1420.NI_RELEASE_SVC_BETAFLT_PROD1_CLIENTMULTI_X64FRE_RU-RU_FIXED_2023_09_13.iso) |

_________________________________________________________________________________________________________________________________________________

### Intel 8 Series/C220 Series Chipset Family BIOS settings:
|       Disable                                                          |    Enable                                                                           |
|----------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Fast Boot                                                              | VT-x                                                                                |
| Secure Boot                                                            | Above 4G Decoding                                                                   |
| Serial/COM Port                                                        | Hyper-Threading                                                                     |
| Parallel Port                                                          | Execute Disable Bit                                                                 |
| VT-d (can be enabled if you set DisableIoMapper to YES)                | EHCI/XHCI Hand-off                                                                  |
| Compatibility Support Module (CSM)                                     | OS type: "Other OS"                                                                 |
| Intel SGX                                                              | UEFI Mode                                                                           |
| Intel Platform Trust                                                   | DVMT Pre-Allocated(iGPU Memory): 64MB or higher                                     |
| CFG Lock (MSR 0xE2 write protection)                                   | SATA Mode: AHCI                                                                     |

_________________________________________________________________________________________________________________________________________________

| Specifications                                                                   | Kexts                         | [Builds/Dortania](https://dortania.github.io/builds/)  Links                                                    |
| -------------------------------------------------------------------------------- | ----------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Open source kernel extension                                                     | Lilu.kext                     | [Gihub Link](https://github.com/acidanthera/Lilu)                                                               |
| Advanced Apple SMC emulator in the kernel                                        | VirtualSMC.kext               | [Gihub Link](https://github.com/acidanthera/VirtualSMC)                                                         |
| Lilu plugin for providing patches to select GPUs                                 | WhateverGreen.kext            | [Gihub Link](https://github.com/acidanthera/WhateverGreen)                                                      |
| Lilu plugin for dynamic power management data injection                          | CPUFriend.kext                | [Gihub Link](https://github.com/acidanthera/CPUFriend)                                                          |
| Lilu plugin that combines the functionality of VoodooTSCSync                     | CpuTscSync.kext               | [Gihub Link](https://github.com/acidanthera/CpuTscSync)                                                         |
| Kernel extension for blocking unwanted processes                                 | RestrictEvents.kext           | [Gihub Link](https://github.com/acidanthera/RestrictEvents)                                                     |
| An open source kernel extension enabling native macOS HD audio                   | AppleALC.kext                 | [Gihub Link](https://github.com/acidanthera/AppleALC)                                                           |
| New Trackpad uses emulation to use the built-in macOS driver                     | VoodooPS2.kext                | [Gihub Link](https://github.com/acidanthera/VoodooPS2)                                                          |
| OS X open source driver for the Realtek RTL8111/8168 family                      | RealtekRTL8111.kext           | [Gihub Link](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases)                                         | 
| Drivers for Realtek 802.11n and 802.11ac USB Wi-Fi adapters                      | RtWlanU.kext RtWlanU1827.kext | [Gihub Link](https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter)                                         |
| USB Wake Controller                                                              | USBWakeFixup.kext             | [Gihub Link](https://github.com/osy/USBWakeFixup)                                                               |
| An open source kernel extension providing a sync between RTC variables and NVRAM | HibernationFixup.kext         | [Gihub Link](https://github.com/acidanthera/HibernationFixup)                                                   |
| Adds allowed entitlements to non-Apple signed apps when SIP is enabled           | AMFIExemption.kext            | [Gihub Link](https://github.com/osy/AMFIExemption)                                                              |
| Drivers for Cambridge Silicon Radio 4.0 USB Bluetooth adapters                   | CSRBluetoothInjector.kext     | [Gihub Link](https://github.com/So1jon/Hackintosh-Desktop-Haswell/files/12690495/CSRBluetoothInjector.kext.zip) |

### Special Config:

- Usb port mapping performed
- SSDT-Hack Essential patc

_________________________________________________________________________________________________________________________________________________

### Download the tools :

| Name                     | Version    | Links                                                                                                              |
| ------------------------ | ---------- | ------------------------------------------------------------------------------------------------------------------ |
| OpenCore Auxiliary Tools | 20230022   | [Github link](https://github.com/ic005k/OCAuxiliaryTools/releases)                                                 |
| Python                   | 3.11.5     | [official link](https://www.python.org/downloads/macos/)                                                           |
| Proper Tree              | 0.2.5      | [Github link](https://github.com/corpnewt/ProperTree)                                                              | 
| OcBinaryData             | QEMU 8.0.0 | [Github link](https://github.com/acidanthera/OcBinaryData)                                                         |
| GenSMBIOS                | Release    | [Github link](https://github.com/corpnewt/GenSMBIOS)                                                               |
| ssdtPRGen.sh             | Release    | [Github link](https://github.com/Piker-Alpha/ssdtPRGen.sh)                                                         |
| SSDTTime                 | Release    | [Github Link](https://github.com/corpnewt/SSDTTime)                                                                |
| USBMap                   | Release    | [Github Link](https://github.com/corpnewt/USBMap)                                                                  |
| USBToolBox/tool          | 0.2        | [Gihub Link](https://github.com/USBToolBox/tool)                                                                   |
| ESP Mounter Pro          | 1.0        | [Official link](https://www.olarila.com/files/Utils/ESP%20Mounter%20Pro.app_v1.9.1.zip)                            |
| Hackintool               | 3.9.9      | [Gihub Link](https://github.com/benbaker76/Hackintool)                                                             |
| RadeonSensor             | 1.3.0      | [Gihub Link](https://github.com/ChefKissInc/RadeonSensor/releases)                                                 |
| MIST                     | 0.9.1      | [Gihub Link](https://github.com/ninxsoft/Mist)                                                                     |
| About This Hack          | 0.9.1      | [Github link](https://github.com/0xCUB3/About-This-Hack/releases)                                                  |
| OpenCore Legacy Patcher  | 0.6.8      | [Gihub Link](https://github.com/dortania/OpenCore-Legacy-Patcher/releases)                                         |
| Kernel Debug Kit         | Release    | [Official link](https://developer.apple.com/download/all/)                                                         |
| Windows Install          | 5.9.1      | [official link](https://applelife.ru/threads/skript-ustanovki-windows-iz-pod-macos.2942844/page-19#post-741961)    |
| Bypass Registry          | Release    | [Github link](https://github.com/haithamaouati/BW11)                                                               |
| Brigadier                | Release    | [Github link](https://codeload.github.com/timsutton/brigadier/zip/main)                                            |
| Brigadier Command        | Release    | [Google drive link](https://drive.google.com/file/d/1eY-CONimt4J74qrx1kUciwVyLSNMd0jX/view)                        |
| Win10 EFI Folder         | Release    | [Google drive link](https://drive.google.com/file/d/1AVWyE8RkHE_e6SomJYted2wFpeiBs9Hi/view)                        |
| TransMac                 | Release    | [Official link](https://www.acutesystems.com/scrtm.htm)                                                            |
| HFS+ Paragon Software    | Release    | [Official link](https://www.paragon-software.com/home/hfs-windows/)                                                |

### MacOS bootable USB creation:

- Read the Dortania guide for creating your USB from Windows or macOS
- [Guide Dortania](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) - USB creation

_________________________________________________________________________________________________________________________________________________

### What works:

- AMD Radeon RX 580

- Intel HD Graphics 4400 

- CPU Power Management 

- Restart, Sleep and Shutdown 

- Ethernet 

- Audio Output from Front and Rear Jack 

- All USB Ports

- USB Wi-Fi 

- USB Bluetooth 

- HDMI Out
 
- HDMI Audio 




## Credits:

- [Apple](https://www.apple.com/mac/) for macOS.


_________________________________________________________________________________________________________________________________________________
