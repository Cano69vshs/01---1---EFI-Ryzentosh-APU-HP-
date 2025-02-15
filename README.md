<h1 align="center"> HP- AMD Ryzen 3 3300UAMD Radeon  Vega 6 Graphics </h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cd3ebc8b-136b-4566-b1b6-967d615eaf8d"
  ![HP](https://github.com/user-attachments/assets/615c0dd2-a113-4457-b517-91efb2236bc2) alt="HP Codename : Piccaso" width="750">


</p>
<h4 align="center"> OpenCore config for Hackintosh Ryzentosh AMD Radeon HP AMD Ryzen 3  3300U Vega 6 Graphics  </h4>

# Kexts

<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-red?logo=YouTube&logoColor=white" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>
<a href="https://www.buymeacoffee.com/yusufklncc">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" width="150"/> </a>

## Categories
 - [Required for macOS Installation](https://github.com/yusufklncc/About-Kexts-on-macOS#required-for-macos-installation)
 - [Audio](https://github.com/yusufklncc/About-Kexts-on-macOS#audio)
 - [USB](https://github.com/yusufklncc/About-Kexts-on-macOS#usb)
 - [Lilu Plugins](https://github.com/yusufklncc/About-Kexts-on-macOS#virtualsmc-plugin)
 - [VirtualSMC Plugins](https://github.com/yusufklncc/About-Kexts-on-macOS#virtualsmc-plugin)
 - [Touchpad & Keyboard](https://github.com/yusufklncc/About-Kexts-on-macOS#touchpad--keyboard)
 - [Ethernet](https://github.com/yusufklncc/About-Kexts-on-macOS#ethernet)
 - [Wi-Fi & Bluetooth](https://github.com/yusufklncc/About-Kexts-on-macOS#wi-fi--bluetooth)

--------------------



## Original Hardware HP - 💻
Type | Spec | Status
:---------|:---------|:----------
Model Name      | HP PAVILION LAPTOP 15-CW1XXX | ✅
CPU              | AMD Ryzen 3 3300U | ✅
GPU              | AMD Radeon(TM) Vega 6 Graphics" | ✅
RAM           | 12.0 GB (9.92 GB usable) | ✅
Internal AMD Graphics Card | AMD Radeon(TM) Vega 6 Graphics | ✅
Wi-Fi             | Realtek RTL8821CE 802.11ac PCIe Adapter| ✅
Ethernet          | Realtek PCIe GbE Family Controller | ✅
Audio       |Realtek(R) Audio : 10EC-0295 | ✅
Touchpad | Standard PS/2 Keyboard | ✅

  

-----


##  .tp-link Modifications Doungle Adaptador USB   🔨
Type | Spec | Status
:---------|:---------|:----------
Wi-Fi | TL-WN725N Doungle USB Adptador  | ✅
USB Wi-Fi | TL-WN725N| ✅ 


- *TL-WN725N*  Adaptador USB nano inalámbrico N de 150 Mbps , 
- Seguridad avanzada: compatible con 64/128 WEP, WPA, PA2/WPA-PSK/WPA2-PSK(TKIP/AES) 
- You have to install USB drivers for working USB adapter.




# Adaptador USB nano inalámbrico N de 150 Mbps

-   Diseño en miniatura elegante, tan pequeño que, una vez enchufado, puede dejarse en el puerto USB de una computadora portátil.
-   Transmisión inalámbrica rápida de hasta 150 Mbps, ideal para transmisión de video o llamadas por Internet
-   Seguridad avanzada: compatible con 64/128 WEP, WPA, PA2/WPA-PSK/WPA2-PSK(TKIP/AES)
-   Conéctese en poco tiempo con una sencilla utilidad de configuración en 14 idiomas
-   Windows 10/8.1/8/7/XP, Mac OS X, Linux




="300">


-----------------------
 
## Required for macOS Installation
 
Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS. | 8.0.0 (10.4) |
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning. | 8.0.0 (10.4) |
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. | 10.0.0 (10.6) | 
[telemetrap](https://forums.macrumors.com/threads/mp3-1-others-sse-4-2-emulation-to-enable-amd-metal-driver.2206682/page-4?post=28447707#post-28447707) | SSE 4.2 emulation | 18.0.0 (10.14)	

## Audio
 
Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[AppleALC](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. | 8.0.0 (10.4) | 
[VoodooHDA](https://github.com/chris1111/VoodooHDA-OC) | If AppleALC won't work. You can use this. | 16.0.0 (10.12)

## USB

Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[USBPorts or USBMap](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports. (via Hackintool or USBMap.command)
[USBInjectAl](https://github.com/Sniki/OS-X-USB-Inject-All) | Kext to inject USB ports. | 15.0.0 (10.11) | |
[XHCI-unsupported](https://disk.yandex.com.tr/d/OeeRKeeHThqYxQ) | Use for USB port mapping (Haswell+) | 15.0.0 (10.11)
[USBWakeFixup](https://github.com/osy/USBWakeFixup) | This extension is a workaround for that issue by creating a fake ACPI device with the right wakeup params.

## Lilu Plugins

Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection. | 10.0.0 (10.6) | 
[CPUFriendDataProvider](https://github.com/corpnewt/CPUFriendFriend) | A CPUFriend plug-in for CPU power management.
[CpuTscSync](https://github.com/acidanthera/CpuTscSync) | It is a Lilu plugin, combining functionality of VoodooTSCSync and disabling xcpm_urgency if TSC is not in sync. It should solve some kernel panics after wake.
[TSCAdjustReset](https://github.com/interferenc/TSCAdjustReset) | This kernel extension fixes the consenquences of unsyncronised TSC when booting Mac OS on an X299 board with Skylake-X CPUs.
[ECEnabler](https://github.com/1Revenger1/ECEnabler) | Allows reading Embedded Controller fields over 1 byte long, vastly reducing the amount of ACPI modification needed (if any) for working battery status. | 11.0.0 (10.7)
[HibernationFixup](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM.
[RTCMemoryFixup](https://github.com/acidanthera/RTCMemoryFixup#rtcmemoryfixup) | An open source kernel extension providing a way to emulate some offsets in CMOS (RTC) memory. It can help you to avoid some conflicts between macOS AppleRTC and firmware/BIOS of your PC.
[NoTouchID](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support. | 17.0.0 (10.13) | 19.9.9 (10.15)
[NVMeFix](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily. | 18.0.0 (10.14) | 
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.
[BrightnessKeys](https://github.com/acidanthera/BrightnessKeys) | Automatic handling of brightness keys.
[RealtekCardReader](https://github.com/0xFireWolf/RealtekCardReader) | An unofficial macOS kernel extension for Realtek PCIe/USB-based SD card readers.
[RealtekCardReaderFriend](https://github.com/0xFireWolf/RealtekCardReaderFriend) | A Lilu plugin that makes System Information recognize your Realtek card reader as a native one. |
[Sinetek-rtsx](https://www.insanelymac.com/forum/topic/321080-sineteks-driver-for-realtek-rtsx-sdhc-card-readers/page/2/#comment-2376387) | This driver is for Realtek SDHC card readers on a pci/pcie bus, most commonly found in laptops.
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control. | 16.5.0 (12.4)

## VirtualSMC Plugins

Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that parses battery info. | 8.0.0 (10.4) | 
[SMCDellSensors](https://github.com/acidanthera/VirtualSMC) |  | 11.0.0 (10.7) |
[SMCLightSensor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that activate light sensor. | 10.0.0 (10.6) | 
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that provides power info of processor temperature. | 11.0.0 (10.7) |
[SMCSuperIO](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that reads fan speed. | 10.0.0 (10.6) |
[AsusSMC](https://github.com/hieplpvip/AsusSMC) | A VirtualSMC plugin provides native support for ALS, keyboard backlight and Fn keys for Asus laptops on macOS.
[AMDRyzenCPUPowerManagement](https://github.com/trulyspinach/SMCAMDProcessor) | All AMD power management features. This kext is also required if you would like to use AMD Power Gadget.
[SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor) | Enables macOS applications like iStat to display sensor data.

## Touchpad & Keyboard

Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[AlpsHID](https://github.com/blankmac/AlpsHID) | This is a satellite kext which uses VoodooI2C's multitouch engine to bring native multitouch to the Alps touchpad using the HID protocol.
[VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) | VoodooI2C is a project consisting of macOS kernel extensions that add support for I2C bus devices. | 16.0.0 (10.12) |
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad. | 15.0.0 (10.11) |
[VoodooRMI](https://github.com/VoodooSMBus/VoodooRMI) | A port for macOS of Synaptic's RMI Trackpad driver from Linux. | 15.0.0 (10.11) |

## Ethernet

Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[AtherosE2200Ethernet](https://github.com/Mieze/AtherosE2200Ethernet) | Driver for the Qualcomm Atheros AR816x, AR817x, Killer E220x, Killer E2400 and Killer E2500 ethernet controller.
[IntelMausi](https://github.com/acidanthera/IntelMausi) | Intel onboard LAN driver for macOS. | 	13.0.0 (10.9) | 
[IntelSnowMausi](https://github.com/acidanthera/IntelMausi) | Intel onboard LAN driver for macOS. | 	10.0.0 (10.6) | 12.9.9 (10.8)
[RealtekRTL8100](https://www.insanelymac.com/forum/files/file/259-realtekrtl8100-binary/) | Driver for Realtek's RTL810X Fast Ethernet family.
[RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X) | Driver for the Realtek RTL8111/8168 family.

## Wi-Fi & Bluetooth

Name | Info | MinKernel | MaxKernel
:---------|:---------|:---------|:---------
[AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards.
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | An Intel Wi-Fi Adapter Kernel Extension for macOS. | 17.0.0 |
[AirPortAtheros40](https://github.com/sXmpwn/atheros-kexts) | An Atheros Wi-Fi Adapter Kernel Extension for macOS. | 17.0.0 | 20.9.9 
[BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices. | 14.0.0 (10.10) |
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS. | 
  
  
<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
