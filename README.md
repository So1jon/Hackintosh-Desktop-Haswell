_________________________________________________________________________________________________________________________________________________

Guide Used - [OpenCore Desktop Haswell Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html)

• Bootloader : [OpenCore Lasted RELEASE Version](https://github.com/acidanthera/OpenCorePkg) in [Project Acidanthera](https://github.com/orgs/acidanthera/repositories)

• Operation system : [macOS Big Sur](https://www.apple.com/newsroom/2020/11/macos-big-sur-is-here/) Final Version

• [PlatformInfo:](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#platforminfo) SMBIOS [iMac14,4](https://support.apple.com/kb/SP701?locale=ru_RU) only iGPU

• Success Full [DSDT](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/10581093/DSDT_GIGABAYTE-Z87-DS3H_Intel-Core-i3-4130.zip) for GIGABAYTE Z87 DS3H v1.1

• Download image macOS Big Sur 11.7.3 (20G1116)-[(DMG Google drive-link)](https://drive.google.com/file/d/1gf-_WaHfuZsU3s7fEJiKCmjg0w-LTiOB/view?usp=share_link)

• Download image macOS Monterey 12.6.3 (21G419)-[(DMG Google drive-link)](https://drive.google.com/file/d/1wNvONhKAopXCp-OM6k9Cd1-amjXIZhn4/view?usp=share_link) via windows [(rdr torrent-link)](https://rutracker.org/forum/viewtopic.php?t=6066530)

• Download image macOS Ventura 13.2 (22D49)-[(DMG OneDrive-link)](https://79mac-my.sharepoint.com/:u:/g/personal/7_79mac_onmicrosoft_com/EVAJTSfBTjRMt56kn9s23S8B8VV8VteoNq-cCxD39_u6CA?e=MfOfLo) via windows [(rdr torrent-link)](https://rutracker.org/forum/viewtopic.php?t=6223477)

• Script from Sergey_Galan  [Windows Install Version 5.7](https://i.applelife.ru/2021/11/493507_Windows_Install_5.7.zip) - [Google drive link](https://drive.google.com/file/d/1m29LIGJOVr4UV2RkyqeOZkMV6XzFKhqJ/view) - [applelife.ru link](https://applelife.ru/threads/skript-ustanovki-windows-iz-pod-macos.2942844/page-19#post-741961) 

• Install windows on Mac (No bootcamp)-[Youtube link](https://youtu.be/3_h9yOvrAKc) Russian manual-[Youtube link](https://youtu.be/5pBLnKHz6c0)

• Download windows 11 image from microsoft official [website link](https://www.microsoft.com/ru-ru/software-download/windows11)

_________________________________________________________________________________________________________________________________________________

Downlaod Tools :

• Python Releases for macOS [official website link](https://www.python.org/downloads/macos/)

• Proper Tree        - [Github link](https://github.com/corpnewt/ProperTree)

• GenSMBIOS          - [Github link](https://github.com/corpnewt/GenSMBIOS)

• ssdtPRGen.sh       - [Github link](https://github.com/Piker-Alpha/ssdtPRGen.sh)

• SSDTTime           - [Github Link](https://github.com/corpnewt/SSDTTime)

• USBMap             - [Github Link](https://github.com/corpnewt/USBMap)

• USBToolBox/tool    - [Gihub Link](https://github.com/USBToolBox/tool)       
_________________________________________________________________________________________________________________________________________________

Hardware Specifications -

• Motherboard : [Z87-DS3H v1.1](https://www.gigabyte.ru/products/page/mb/ga-z87-ds3hrev_11#kf) Gigabayte 

• CPU : [Intel Core i3 4130](https://ark.intel.com/content/www/ru/ru/ark/products/77480/intel-core-i34130-processor-3m-cache-3-40-ghz.html) Haswell
 
• iGPU : [Intel HD Graphics 4400](https://ark.intel.com/content/www/us/en/ark/products/graphics/81497/intel-hd-graphics-4400.html#@Desktop) Desktop

• RAM : [4x4GB DDR3 / 1600Mhz](https://www.kingston.com/dataSheets/KVR16N11S8_4.pdf) Kingston
 
• Storage : [SSD 480GB](https://www.pny.com.tw/en/products-detail/CS900-2-point-5-SSD/) PNY CS900 
 
• Ethernet : [Realtek RTL8111E-VL](https://4ip.info/files/attachments/RTL8111E.pdf) Gigabit Ethernet
 
• Wi-Fi : USB [TL-WN725N V3](https://www.tp-link.com/us/support/download/tl-wn725n/) TP-Link 

• Bluetooth : USB [CSR 4.0](https://russian.alibaba.com/p-detail/Universal-1600104012497.html?spm=a2700.7724857.0.0.eaefdcc1UmOoT3) Cambridge Silicon Radio
 
• Audio Codec : [ALC887](http://www.chipset-ic.com/datasheet/ALC887.pdf) Realtek 
 
• Boot Mode : UEFI

_________________________________________________________________________________________________________________________________________________


Kexts - [Dortania](https://dortania.github.io) - [Builds](https://dortania.github.io/builds/) 


• [AppleALC.kext](https://github.com/acidanthera/AppleALC) An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. AppleALCU can be used for systems with digital-only audio.

• [RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases) OS X open source ethernet driver for the Realtek RTL8111/8168 family.Due to the lack of an OS X driver that makes use of the advanced features of the Realtek RTL81111/8168 series with the aim to create a state of the art driver that gets the most out of those NICs which can be found on virtually any cheap board on the market today.

• [Lilu.kext](https://github.com/acidanthera/Lilu) An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.

• [CPUFriend.kext](https://github.com/acidanthera/CPUFriend) A Lilu plug-in for dynamic power management data injection -[Fix CPU Intel Core i3 4130](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/9784489/CPU_Fix.zip)

• [CpuTscSync.kext](https://github.com/acidanthera/CpuTscSync) It is a Lilu plugin, combining functionality of VoodooTSCSync and disabling xcpm_urgency if TSC is not in sync. It should solve some kernel panics after wake.

• [RestrictEvents.kext](https://github.com/acidanthera/RestrictEvents) Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.

• [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC)  Advanced Apple SMC emulator in the kernel. Requires Lilu.

• [VoodooPS2.kext](https://github.com/acidanthera/VoodooPS2) Touchpad and Keyboard Driver uses VoodooInput's Magic Trackpad II emulation in order to use macOS native driver instead of handling all gestures itself. This enables the use of any from one to four finger gestures defined by Apple

• [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen) Lilu plugin providing patches to select GPUs on macOS. Requires Lilu 1.5.6 or newer.

• [USBMap.kext.zip](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/10427360/USBMap.kext.zip) Custom USB Driver SMBIOS iMac14,4

• [Wireless-USB.kext](https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter) Support macOS Ventura 13 - macOS Monterey 12 - macOS Big Sur 11 Only! (DO NOT USE ON OTHER OS's)

• [CSRBluetoothInjector.kext](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/9784693/CSRBluetoothInjector.kext.zip) USB Bluetooth CSR 4.0 Driver

• [USBWakeFixup.kext](https://github.com/osy/USBWakeFixup) On systems without a working Embedded Controller, waking up from a USB device might not wake up the display. A second key-press or mouse click is required to wake up the display. This extension is a workaround for that issue by creating a fake ACPI device with the right wakeup params.

_________________________________________________________________________________________________________________________________________________
 

Work?? -

• Intel HD Graphics 4400 

• CPU Power Management 

• Restart, Sleep and Shutdown 

• Ethernet 

• USB Wi-Fi 

• USB Bluetooth 

• Audio Output from Front and Rear Jack 

• HDMI Out
 
• HDMI Audio 

• All USB Ports

_________________________________________________________________________________________________________________________________________________
