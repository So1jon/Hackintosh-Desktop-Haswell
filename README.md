_________________________________________________________________________________________________________________________________________________

Guide Used - [OpenCore Desktop Haswell Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#starting-point)

• Bootloader Version : [OpenCore-0.8.5-RELEASE](https://github.com/acidanthera/OpenCorePkg/releases/download/0.8.5/OpenCore-0.8.5-RELEASE.zip) on Oct 4, 2022

[• macOS Big Sur 11.7 (20G817)](https://support.apple.com/en-us/HT211896) updated on Sep 12, 2022

• [PlatformInfo:](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#platforminfo) SMBIOS [iMac15,1](https://support.apple.com/kb/SP718?locale=ru_RU)

• Success Full [DSDT](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/9710260/DSDT_GIGABAYTE-Z87-DS3H_Intel-Core-i3-4130.zip) for GIGABAYTE Z87 DS3H v1.1

• IORegistryExplorer document - [iMac15.1.ioreg](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/9718366/iMac2015.ioreg.zip)

• DMG image [macOS Big Sur 11.7 (20G817)](https://drive.google.com/file/d/1GZZc3CiFkPzgx67jN-hz1xyjyaNuhTbg/view?usp=sharing)

_________________________________________________________________________________________________________________________________________________

Hardware Specifications -

• Motherboard : [Z87-DS3H v1.1](https://www.gigabyte.ru/products/page/mb/ga-z87-ds3hrev_11#kf) Gigabayte 

• Processor : [Intel Core i3 4130](https://ark.intel.com/content/www/ru/ru/ark/products/77480/intel-core-i34130-processor-3m-cache-3-40-ghz.html) Haswell
 
• IGPU : [Intel HD Graphics 4400](https://ark.intel.com/content/www/us/en/ark/products/graphics/81497/intel-hd-graphics-4400.html#@Desktop) Desktop

• RAM : [4x4GB DDR3 / 1600Mhz](https://www.kingston.com/dataSheets/KVR16N11S8_4.pdf) Kingston
 
• Storage : [SSD 480GB](https://www.pny.com.tw/en/products-detail/CS900-2-point-5-SSD/) PNY CS900 
 
• Ethernet : [Realtek RTL8111E-VL](https://4ip.info/files/attachments/RTL8111E.pdf) Gigabit Ethernet
 
• Wi-Fi : USB [TL-WN725N V3](https://www.tp-link.com/us/support/download/tl-wn725n/) TP-Link 

• Bluetooth : USB [CSR 4.0](https://russian.alibaba.com/p-detail/Universal-1600104012497.html?spm=a2700.7724857.0.0.eaefdcc1UmOoT3) Cambridge Silicon Radio
 
• Audio Codec : [ALC887](http://www.chipset-ic.com/datasheet/ALC887.pdf) Realtek 
 
• Boot Mode : UEFI

_________________________________________________________________________________________________________________________________________________


Kexts -


• [AppleALC.kext](https://github.com/acidanthera/AppleALC) An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. AppleALCU can be used for systems with digital-only audio.

• [RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases) OS X open source ethernet driver for the Realtek RTL8111/8168 family.Due to the lack of an OS X driver that makes use of the advanced features of the Realtek RTL81111/8168 series I started a new project with the aim to create a state of the art driver that gets the most out of those NICs which can be found on virtually any cheap board on the market today. Based on Realtek's Linux driver (version 8.035.0) I have written a driver that is optimized for performance while making efficient use of system resources and keeping the CPU usage down under heavy load.

• [Lilu.kext](https://github.com/acidanthera/Lilu) An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.

• [CPUFriend.kext](https://github.com/acidanthera/CPUFriend) A Lilu plug-in for dynamic power management data injection -[CPU Fix](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/9784489/CPU_Fix.zip)

• [CpuTscSync.kext](https://github.com/acidanthera/CpuTscSync) It is a Lilu plugin, combining functionality of VoodooTSCSync and disabling xcpm_urgency if TSC is not in sync. It should solve some kernel panics after wake.

• [RestrictEvents.kext](https://github.com/acidanthera/RestrictEvents) Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.

• [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC)  Advanced Apple SMC emulator in the kernel. Requires Lilu.

• [VoodooPS2.kext](https://github.com/acidanthera/VoodooPS2) Touchpad and Keyboard Driver uses VoodooInput's Magic Trackpad II emulation in order to use macOS native driver instead of handling all gestures itself. This enables the use of any from one to four finger gestures defined by Apple

• [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen) Lilu plugin providing patches to select GPUs on macOS. Requires Lilu 1.5.6 or newer.

• [USBPro.kext](https://github.com/So1jon/Gigabayte-Z87-DS3H-Intel-Core-i3-4130-Intel-HD-Graphics-4400/files/9784205/USBPro.kext.zip) Custom USB Driver SMBIOS iMac15.1

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
