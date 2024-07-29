
<p></p>
<p align="center"><img src="https://i.imgur.com/HJnpvwQ.png" width="200" height="48"/> EFI</p>
<p align="center">
  <a href="https://github.com/acidanthera/OpenCorePkg">
  <img src="https://img.shields.io/badge/OpenCore-0.9.9-informational.svg">
 </a>
</p>

<a href="https://github.com/So1jon">
    <img src="https://img.shields.io/github/followers/So1jon?label=So1jon&logo=GitHub&style=social" />
</a> 

[![GitHub all releases](https://img.shields.io/github/downloads/So1jon/Hackintosh-Desktop-Haswell/total?style=flat&logo=github&logoColor=white&color=1A91FF)](https://github.com/So1jon/Hackintosh-Desktop-Haswell/releases)

<details>
<summary><strong>Hardware specifications:</strong></summary>

<br />

| Components      | Name                                    |  Brand Links                                                                                                                                               |
| --------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Motherboard** | `Z87-DS3H v1.1`                         | [`Gigabyte`](https://www.gigabyte.com/Motherboard/GA-Z87-DS3H-rev-11#ov)                                                                                  |
| **Power Supply** |`P550B 550w 80 PLUS Bronze certified`   | [`Gigabyte`](https://www.gigabyte.com/Power-Supply/GP-P550B#kf)                                                                                  |
| **CPU**         | `Intel® Core® i7 4790`                  | [`Intel Haswell`](https://www.intel.com/content/www/us/en/products/sku/80806/intel-core-i74790-processor-8m-cache-up-to-4-00-ghz/specifications.html)      |
| **iGPU**        | `Intel® HD Graphics 4600`               | [`Intel Haswell`](https://ark.intel.com/content/www/us/en/ark/search.html?_charset_=UTF-8&q=HD+Graphics+4600)                                              |
| **dGPU**        | `AMD Radeon RX 580 8GB`                 | [`Sapphire NITRO+`](https://www.sapphiretech.com/en/consumer/nitro-rx-580-8g-g5)                                                                        |
| **Ram**         | `DDR3 16GB / 1600Mhz`                   | [`Kingston`](https://www.kingston.com/dataSheets/KVR16N11S8_4.pdf)                                                                                         |
| **Storage**     | `CS900 SSD 480GB SATA  6Gb/s`           | [`PNY`](https://www.pny.com.tw/en/products-detail/CS900-2-point-5-SSD/)                                                                              |
| **Ethernet**    | `RTL8111E-VL 1.0 Gigabit/s`             | [`Realtek`](https://4ip.info/files/attachments/RTL8111E.pdf)                                                                                               |
| **Audio**       | `Codec ALC887`                          | [`Realtek`](http://www.chipset-ic.com/datasheet/ALC887.pdf)                                                                                                |
| **USB Wi-Fi**   | `TL-WN725N V3`                          | [`TP-Link`](https://www.tp-link.com/us/support/download/tl-wn725n/)                                                                                        |
|**USB Bluetooth**| `Cambridge Silicon Radio 4.0`           | [`CSR`](https://en.wikipedia.org/wiki/CSR_plc)                                                                                                             |
| **USB Camera**  | `Z-Star Microelectronics Corporation`   | [`Vimicro`](http://www.vimicro.com/english/product/pc001.htm)                                                                                              |

</details>

<details>
<summary><strong>Hardware BIOS settings:</strong></summary>

<br />

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

</details>

<details>
<summary><strong>Download the Kexts:</strong></summary>

<br />


| Specifications                                                                        | Kexts                           | [Builds/Dortania](https://dortania.github.io/builds/)  Links                                                    |
| ------------------------------------------------------------------------------------- | ------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Open source kernel extension                                                          | `Lilu.kext`                     | [Gihub Link](https://github.com/acidanthera/Lilu)                                                               |
| Advanced `Apple SMC` emulator in the kernel                                           | `VirtualSMC.kext`               | [Gihub Link](https://github.com/acidanthera/VirtualSMC)                                                         |
| `Lilu` plugin for providing patches to select GPUs                                    | `WhateverGreen.kext`            | [Gihub Link](https://github.com/acidanthera/WhateverGreen)                                                      |
| `Lilu` plugin for dynamic power management data injection                             | `CPUFriend.kext`                | [Gihub Link](https://github.com/acidanthera/CPUFriend)                                                          |
| `Lilu` plugin that combines the functionality of `VoodooTSCSync`                      | `CpuTscSync.kext`               | [Gihub Link](https://github.com/acidanthera/CpuTscSync)                                                         |
| Kernel extension for blocking unwanted processes                                      | `RestrictEvents.kext`           | [Gihub Link](https://github.com/acidanthera/RestrictEvents)                                                     |
| An open source kernel extension enabling native `macOS` HD audio                      | `AppleALC.kext`                 | [Gihub Link](https://github.com/acidanthera/AppleALC)                                                           |
| New Trackpad uses emulation to use the built-in `macOS` driver                        | `VoodooPS2.kext`                | [Gihub Link](https://github.com/acidanthera/VoodooPS2)                                                          |
| `OS X` open source driver for the `Realtek RTL8111/8168` family                       | `RealtekRTL8111.kext`           | [Gihub Link](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases)                                         | 
| Drivers for `Realtek 802.11n` and `802.11ac USB Wi-Fi` adapters                       | `RtWlanU.kext RtWlanU1827.kext` | [Gihub Link](https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter)                                         |
| USB Wake Controller                                                                   | `USBWakeFixup.kext`             | [Gihub Link](https://github.com/osy/USBWakeFixup)                                                               |
| An open source kernel extension providing a sync between `RTC` variables and `NVRAM`  | `HibernationFixup.kext`         | [Gihub Link](https://github.com/acidanthera/HibernationFixup)                                                   |
| Adds allowed entitlements to non-`Apple` signed apps when `SIP` is enabled            | `AMFIExemption.kext`            | [Gihub Link](https://github.com/osy/AMFIExemption)                                                              |
| Drivers for `Cambridge Silicon Radio 4.0 USB Bluetooth` adapters                      | `CSRBluetoothInjector.kext`     | [Gihub Link](https://github.com/So1jon/Hackintosh-Desktop-Haswell/files/12690495/CSRBluetoothInjector.kext.zip) |


</details>

<details>
<summary><strong>Download the tools:</strong></summary>
<br />

[![](https://img.shields.io/badge/acidanthera-OpenCorePkg-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/acidanthera/OpenCorePkg)[![GitHub all releases](https://img.shields.io/github/downloads/acidanthera/OpenCorePkg/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/acidanthera/OpenCorePkg/releases)

[![](https://img.shields.io/badge/acidanthera-OcBinaryData-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/acidanthera/OcBinaryData)[![GitHub all releases](https://img.shields.io/github/downloads/acidanthera/OcBinaryData/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/acidanthera/OcBinaryData/archive/refs/heads/master.zip)

[![](https://img.shields.io/badge/acidanthera-MaciASL-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/acidanthera/MaciASL)[![GitHub all releases](https://img.shields.io/github/downloads/acidanthera/MaciASL/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/acidanthera/MaciASL/releases)

[![](https://img.shields.io/badge/dortania-OpenCore_Legacy_Patcher-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/dortania/OpenCore-Legacy-Patcher)[![GitHub all releases](https://img.shields.io/github/downloads/dortania/OpenCore-Legacy-Patcher/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/dortania/OpenCore-Legacy-Patcher/releases)

[![](https://img.shields.io/badge/ic005k-OCAuxiliaryTools-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/ic005k/OCAuxiliaryTools)[![GitHub all releases](https://img.shields.io/github/downloads/ic005k/OCAuxiliaryTools/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/ic005k/OCAuxiliaryTools/releases)

[![](https://img.shields.io/badge/corpnewt-ProperTree-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/corpnewt/ProperTree)[![GitHub all releases](https://img.shields.io/github/downloads/corpnewt/ProperTree/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip)

[![](https://img.shields.io/badge/corpnewt-GenSMBIOS-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/corpnewt/GenSMBIOS)[![GitHub all releases](https://img.shields.io/github/downloads/corpnewt/GenSMBIOS/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip)

[![](https://img.shields.io/badge/corpnewt-USBMap-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/corpnewt/USBMap)[![GitHub all releases](https://img.shields.io/github/downloads/corpnewt/USBMap/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/corpnewt/USBMap/archive/refs/heads/master.zip)

[![](https://img.shields.io/badge/corpnewt-SSDTTime-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/corpnewt/SSDTTime)[![GitHub all releases](https://img.shields.io/github/downloads/corpnewt/SSDTTime/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/corpnewt/SSDTTime/archive/refs/heads/master.zip)

[![](https://img.shields.io/badge/Piker_Alpha-ssdtPRGen.sh-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/Piker-Alpha/ssdtPRGen.sh)[![GitHub all releases](https://img.shields.io/github/downloads/Piker-Alpha/ssdtPRGen.sh/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/Piker-Alpha/ssdtPRGen.sh/archive/refs/heads/Beta.zip)

[![](https://img.shields.io/badge/USBToolBox-tool-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/USBToolBox/tool)[![GitHub all releases](https://img.shields.io/github/downloads/USBToolBox/tool/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/USBToolBox/tool/releases)

[![](https://img.shields.io/badge/utopia_team-IORegistryExplorer-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/utopia-team/IORegistryExplorer)[![GitHub all releases](https://img.shields.io/github/downloads/utopia-team/IORegistryExplorer/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/utopia-team/IORegistryExplorer/releases)

[![](https://img.shields.io/badge/CloverHackyColor-HWMonitorSMC2-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/CloverHackyColor/HWMonitorSMC2)[![GitHub all releases](https://img.shields.io/github/downloads/CloverHackyColor/HWMonitorSMC2/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/CloverHackyColor/HWMonitorSMC2/releases)

[![](https://img.shields.io/badge/ChefKissInc-RadeonSensor-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/ChefKissInc/RadeonSensor)[![GitHub all releases](https://img.shields.io/github/downloads/ChefKissInc/RadeonSensor/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/ChefKissInc/RadeonSensor/releases)

[![](https://img.shields.io/badge/benbaker76-Hackintool-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/benbaker76/Hackintool)[![GitHub all releases](https://img.shields.io/github/downloads/benbaker76/Hackintool/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/benbaker76/Hackintool/releases)

[![](https://img.shields.io/badge/0xCUB3-About_This_Hack-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/0xCUB3/About-This-Hack)[![GitHub all releases](https://img.shields.io/github/downloads/0xCUB3/About-This-Hack/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/0xCUB3/About-This-Hack/releases)

[![](https://img.shields.io/badge/ninxsoft-Mist-informational?style=flat&logo=github&logoColor=white&color=FFFFFF)](https://github.com/ninxsoft/Mist)[![GitHub all releases](https://img.shields.io/github/downloads/ninxsoft/Mist/total?style=flat&logo=github&logoColor=white&color=008080)](https://github.com/ninxsoft/Mist/releases)

### Download the other tools:

| Name                       | Links                                                                                                                |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| `Mactracker`               | [Official link](https://mactracker.ca/)                                                                              |
| `Python`                   | [Official link](https://www.python.org/downloads/macos/)                                                             |
| `OpenCore Configurator`    | [Official link](https://mackie100projects.altervista.org/download-opencore-configurator/)                            |
| `PlistEdit Pro`            | [Official link](https://www.fatcatsoftware.com/plisteditpro/)                                                        |
| `Intel Power Gadget`       | [Official link](https://www.intel.com/content/dam/develop/external/us/en/documents/downloads/intel-power-gadget.dmg) |  
| `ESP Mounter Pro`          | [Official link](https://www.olarila.com/files/Utils/ESP%20Mounter%20Pro.app_v1.9.1.zip)                              |
| `Kernel Debug Kit`         | [Official link](https://developer.apple.com/download/all/)                                                           |
| `Windows Install`          | [Official link](https://applelife.ru/threads/skript-ustanovki-windows-iz-pod-macos.2942844/page-19#post-741961)      |
| `TransMac`                 | [Official link](https://www.acutesystems.com/scrtm.htm)                                                              |
| `HFS+ Paragon Software`    | [Official link](https://www.paragon-software.com/home/hfs-windows/)                                                  | 


</details>


<details>
<summary><strong>Operating systems:</strong></summary>

<br />

✅ My computer has been fully tested on the following operating systems:

| Name           | Version | Build      | Image links                                                                                                                                                                                                                                                           |
| -------------- | ------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `macOS Sequoia`|`15.0 Beta 4`|`24A5298h`| [`pkg`](https://swcdn.apple.com/content/downloads/48/45/062-39268-A_36NTYE5BPL/0cd85jhjwcbnmk5fqvu4yp323wcmzr9jmu/InstallAssistant.pkg) / [`ISO`](https://disk.yandex.ru/d/a5DeFl1FQjEZSA) |
| `macOS Sonoma` |`14.5`   | `23F79`    | [`DMG`](https://drive.google.com/file/d/1xbmsGcAx2NFdQDOVavN0M-WzzyVNyA1x/view?usp=sharing) / [`rdr`](https://rutracker.org/forum/viewtopic.php?t=6372743)                                                                                                            |
| `macOS Ventura`| `13.6.7`| `22G720`   | [`DMG`](https://drive.google.com/file/d/1YBoZio8yaiURgJNl7SIXly0l2dvI8Fvt/view?usp=sharing) / [`rdr`](https://rutracker.org/forum/viewtopic.php?t=6223477)                                                                                                            | 
|`macOS Monterey`| `12.7.5`| `21H1222`  | [`DMG`](https://drive.google.com/file/d/1fnlLVPrWgrMpAeC_3GjGk5vIV5-3tO4b/view?usp=sharing) / [`rdr`](https://rutracker.org/forum/viewtopic.php?t=6066530)                                                                                                            |
| `macOS Big Sur`|`11.7.10`| `20G1427`  | [`DMG`](https://drive.google.com/file/d/1urRARlkOi6NVc5b6CM0RFLvDLhsCcU5D/view?usp=sharing) / [`rdr`](https://rutracker.org/forum/viewtopic.php?t=5928524)                                                                                                            |

</details>


<details>
<summary><strong>Special Config:</strong></summary>
<br />

⚠️ Usb port mapping performed 👉 [guide](https://github.com/corpnewt/USBMap)

⚠️ SSDT-Hack Essential patc 👉 [guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#acpi)

:closed_lock_with_key: You will need to generate your own SMBIOS and configure, since is required to fully work with macOS. As per you can use the following SMBIOS:

|  SMBIOS    |  Hardware                                     |  macOS Big Sur              |  macOS Monterey            |  macOS Ventura   |  macOS Sonoma  |
| ---------- | --------------------------------------------- | --------------------------- | -------------------------- | ---------------- | -------------- |
| Macmini7,1 | Haswell with only iGPU                        |  full supported             |  full supported            | not supported    | not supported  |
| iMac14,4   | Haswell with only iGPU                        |  full supported             |  not supported             | not supported    | not supported  |
| iMac15,1   | Haswell with dGPU (Enabled iGPU Acceleration) |  full supported             |  not supported             | not supported    | not supported  |
| iMac16,2   | Haswell with only iGPU                        | supported (not recommended) |supported (not recommended) | not supported    | not supported  |
| iMac17,1   | Haswell with dGPU (Enabled iGPU Acceleration) | supported (not recommended) |  full supported            | not supported    | not supported  |
| iMacPro1,1 | Haswell only dGPU (Disabled iGPU Acceleration)|  full supported             |  full supported            | full supported   | full supported |
| MacPro7,1  | Haswell only dGPU (Disabled iGPU Acceleration)|  full supported             |  full supported            | full supported   | full supported |

⚠️ It's fully **required** to generate your own serials with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) and put it in your config.plist.

- Config.plist -> PlatformInfo -> Generic

![SMBIOS on config.plist screenchot](https://dortania.github.io/OpenCore-Install-Guide/assets/img/smbios.65baf9a9.png "SMBIOS on config.plist screenchot")

⚠️ Setting a NVRAM variable


| Boot Arguments             |    Сomments                                                                                                                       |
|--------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| `-v`                       | This enables verbose mode, which shows all the behind-the-scenes text that scrolls by as you're booting instead of the Apple logo and progress bar. |
| `revpatch=sbvmm`           | Enable macOS Ventura and macOS Sonoma system updates                                                                              |
| `-no_compat_check`         | Сancel scan system board id                                                                                                       |
| `-wegnoegpu`               | Disable all external GPUs                                                                                                         |
| `-wegnoigpu`               | Disable internal GPU                                                                                                              |
| `nv_disable=1`             | Forces GPU into VESA mode(no GPU acceleration), useful for troubleshooting and when having issues installing Nvidia's WebDrivers. |
| `-igfxvesa`                | Forces GPU into VESA mode(no GPU acceleration), useful for troubleshooting                                                        |
| `igfxonln=1`               | Forces all displays online, useful for resolving screen wake issues in 10.15.4+ on Coffee and Comet Lake                          |
| `igfxfw=2`                 | Enables loading Apple's GUC firmware for iGPUs, requires a 9th Gen chipset or newer(ie Z390)                                      |
| `-igfxdvmt`                | Fix the kernel panic caused by an incorrectly calculated amount of DVMT pre-allocated memory on Intel ICL platforms               |
| `enable-dvmt-calc-fix`     | Property on IGPU                                                                                                                  |
| `-igfxblt`                 | An alternative to the Backlight Registers Fix and make Backlight Smoother work on KBL/CFL platforms running macOS 13.4 or later.  |
| `enable-backlight-registers-alternative-fix`| Property on IGPU                                                                                                 |


</details>

<details>
<summary><strong>Drivers:</strong></summary>
<br />

| Driver                  | Status   | Description                                        |
| ----------------------- | -------- | -------------------------------------------------- |
| `OpenRuntime.efi`       | Required | Required for proper operation                      |
| `HfsPlus.efi`           | Required | Needed for seeing HFS volumes                      |
| `OpenCanopy.efi`        | Optional | This is an optional OpenCore GUI                   |
| `ResetNvramEntry.efi`   | Optional | Required to reset the system's NVRAM               | 
| `OpenPartitionDxe.efi`  | Optional | Required to boot macOS 10.7-10.9 recovery          |
| `ToggleSipEntry.efi`    | Optional | Enabling and Disabling System Integrity Protection |
| `AudioDxe.efi`          | Optional | Unrelated to Audio support in macOS                |
 
</details>



<details>
<summary><strong>What work:</strong></summary>

<br />

 `✅ AMD Radeon RX 580` Graphics acceleration.

 `✅ dGPU & CPU` Power Management.

 `✅ HDMI`video & audio output.

 `✅ Ethernet.` 

 `✅ Audio` Output from 3.5mm Front and Rear headphone Jack.

 `✅ PS2` Keyboard & Mouse. 

 `✅ USB 2.0/3.0` All Ports.

 `✅ USB` Wi-Fi, Bluetooth, WebCam, Keyboard and Mouse.

 `✅` Restart, Sleep and Shutdown. 

 `✅ Bootcamp.`

 `✅ Apple` Services `iCloud, App Store, iMessage, FaceTime.`

 `❌ VGA` port output.  ⚠️ Not supported for macOS.

 `❌ Intel HD Graphics 4600`  ⚠️ For `macOS Ventura` and `macOS Sonoma` disabled iGPU not supported  `Intel Quick/Sync` Hardware Acceleration.
 
 `❌ AirDrop & Handoff`  ⚠️ Only `AirDrop` and `Handoff` are not working since the `USB Wi-Fi` and `USB Bluetooth` are not fully compatible with `macOS`. For all this to work, you need to replace the card with a native one, such as  `PCI Fenvi` cards before `macOS Sonoma`.

  
</details>

<details>
<summary><strong>Geekbench:</strong></summary>
|<br />

| Information           | Result   | ID Information                                                 | Operating system  | Model ID    |
| --------------------- | -------- | -------------------------------------------------------------- | ----------------- | ----------- |
| CPU Single-Core Score | 1279     | [ID 4337338](https://browser.geekbench.com/v6/cpu/4613419)     | `macOS Sonoma`    | `MacPro7,1` |
| CPU Multi-Core Score  | 4108     | [ID 4337338](https://browser.geekbench.com/v6/cpu/4613419)     | `macOS Sonoma`    | `MacPro7,1` |
| dGPU OpenCL Score     | 42667    | [ID 2350057](https://browser.geekbench.com/v6/compute/2350057) | `macOS Sonoma`    | `MacPro7,1` |
| dGPU Metal Score      | 46180    | [ID 1667557](https://browser.geekbench.com/v6/compute/1667557) | `macOS Sonoma`    | `MacPro7,1` |
| iGPU OpenCL Score     | 3298     | [ID 1995546](https://browser.geekbench.com/v6/compute/1995546) | `macOS Big Sur`   | `iMac14,4`  |
| iGPU Metal Score      | 1329     | [ID 1995533](https://browser.geekbench.com/v6/compute/1995533) | `macOS Big Sur`   | `iMac14,4`  |




</details>


<details>
<summary><strong>Tips:</strong></summary>
<br />

### ⚠️ Help Fix Screen Sleep:

```bash
sudo pmset autopoweroff 0
sudo pmset powernap 0
sudo pmset standby 0
sudo pmset proximitywake 0
sudo pmset tcpkeepalive 0
```

### ⚠️ This will do 5 things for us:

- `Disables` **autopoweroff**: This is a form of hibernation
- `Disables` **powernap**: Used to periodically wake the machine for network, and updates(but not the display)
- `Disables` **standby**: Used as a time period between sleep and going into hibernation
- `Disables` wake from iPhone/Watch: Specifically when your iPhone or Apple Watch come near, the machine will wake
- `Disables` **TCP Keep Alive** mechanism to prevent wake ups every 2 hours

### ⚠️ Отключение функции `Gatekeeper`

Запуск повреждённого приложения невозможен без обхода функции Карантин, или отключения `Gatekeeper` - технологии, которая обеспечивает запуск только доверенного программного обеспечения на компьютере Mac.

### ⚠️ Решение (вариант 1).
Данный вариант позволит обойти Карантин для конкретного приложения. Обратите внимание, что команда включает путь к приложению, или образу (.dmg).
Эту процедуру часто называют `"декарантин"` или `"de-quarantine"`.

1.  Запустите утилиту "Терминал".
Это стандартная утилита, которую не нужно устанавливать дополнительно. Терминал можно найти через `Spotlight`.

2.  Используйте команду: `sudo xattr -r -d com.apple.quarantine` поставьте пробел и перетащите повреждённую программу или образ (.dmg) в окно Терминал. Команда допишется. 

2.1 Или используйте команду: `sudo xattr -r -c`  поставьте пробел и перетащите повреждённую программу или образ (.dmg) в окно Терминал. Команда допишется.
Обычно достаточно использовать только первую команду, но бывают ситуации, когда ее выполнение не помогает, в отличие от выполнения второй.

3.  Нажмите `Enter` и введите пароль Администратора.
Пароль при вводе в Терминал не отображается, но вводится.
Если пароль не задан - создайте его.

4.  Приступайте к запуску повреждённой программы.
Дождитесь завершения проверки и вы сможете её Открыть.
Время проверки может занимать до 30 минут.


### ⚠️ Решение (вариант 2).
Данная команда позволит отключить `Gatekeeper`, т.е. восстановить настройки, разрешающие использование программ, загруженных из Любого источника в Системных настройках / Защита и безопасность.

1.  Запустите утилиту "Терминал".

2.  Используйте команду: `sudo spctl --master-disable`
Перетаскивать в Терминал ничего не нужно. Для включения Gatekeeper, замените `"disable"` на `"enable"`.  

3.  Нажмите `Enter` и введите пароль Администратора.

4.  Приступайте к запуску повреждённой программы.


### ⚠️ Итак, как скрыть папку или файл в macOS?

В окне командной строки нужно ввести следующую команду: 
`chflags hidden` и не нажимая `Enter`, добавить пробел.
Теперь необходимо выбрать папку или файл, которую следует скрыть от других. 
Выделяем и переносим в окно командной строки. 
Подтверждаем наши намерения кнопкой `Enter`.
Всё готово. Требуемый файл или папка больше не будут отображаться в `Finder`.

</details>

<details>
<summary><strong>Credits:</strong></summary>
<br />

⚠️ `Apple` for 👉 [`macOS`](https://www.apple.com/mac/)

⚠️  Forum 👉 [`applelife.ru`](https://applelife.ru/)

⚠️ `OpenCore Desktop Haswell` 👉 [Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html)

⚠️ Creating your `USB` from `Windows` or `macOS` 👉 [Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide) 

⚠️ Information and Technical Resources on YouTube 👉 [@AlexeyBoronenkov](https://www.youtube.com/@AlexeyBoronenkov)


</details>

<details>
<summary><strong>Disclaimer:</strong></summary>
<br />

⚠️ Highly Recommend you to build the EFI for your device on your own and only use this for reference even though you have the same device as mine since, when something fails you will be on your own.

⚠️ If you want to report or rasie an issue, you must mention your device details in it. And give a detailed information about your issue(images or videos are encouraged)

</details>



### You can contact me through:

[![](https://img.shields.io/badge/iCloud-nusratov.sobirjon@icloud.com-informational?style=flat&logo=apple&logoColor=white&color=cbcdcc)](mailto:nusratov.sobirjon@icloud.com)[![](https://img.shields.io/badge/Telegram-@Nusratov_Sobirjon-informational?style=flat&logo=telegram&logoColor=white&color=89e2ff)](https://t.me/Nusratov_Sobirjon)[![](https://img.shields.io/badge/Facebook-Nusratov_Sobirjon-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/Sobirjon.Nusratov)





