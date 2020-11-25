# Hackintosh Opencore 0.6.3 and MacOS Catalina 10.15.7
insert system info here

## DISCLAIMER - This guide was made to help those with similar hardware who's trying to hackintosh via Opencore 0.6.3. FOLLOW AT YOUR OWN RISK!

## Hardware

Components | Type
------- | ------
Processor | [i7 - 9700K](https://www.memoryexpress.com/Products/MX73773)
CPU Fan | [Arctic Cooling Alpine 12 CO](https://www.memoryexpress.com/Products/MX75882)
Mobo | [Gigabyte z390 Aorus Pro Wifi (bios version F12j)](https://www.memoryexpress.com/Products/MX74024)
Memory | [Kingston HyperX Fury RGB 2x8GB](https://www.memoryexpress.com/Products/MX80353)
Storage (Mac) | [Adata Swordfish M.2 NVMe PCI-E 3.0 500GB](https://www.memoryexpress.com/Products/MX00112811)
Monitor | [MSI Optix G24C](https://www.memoryexpress.com/Products/MX68746)
PSU | [Thermaltake Toughpower RGB Gold Modular 750w](https://www.memoryexpress.com/Products/MX65335)
Case | [Thermaltake V250 TG ARGB Mid-Tower Chassis](https://www.memoryexpress.com/Products/MX00112902)
Keyboard & Mouse | [Logitech MK120 Desktop keyboard and Mouse combo](https://www.memoryexpress.com/Products/MX30139)
Graphics | iGPU - UHD 630
Wifi/BT | Built-in

## Software

* [MountEFI](https://github.com/corpnewt/MountEFI) - To mount EFI dir to filesystem
* [ProperTree](https://github.com/corpnewt/ProperTree) - To edit config.plist
* [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) - To generate serials
* [gibMacOS](https://github.com/corpnewt/gibMacOS) - To install preferred macOs version
* [AppleIntelWifi (AirportItlwm) kexts](https://www.tonymacx86.com/threads/success-working-intel-wifi-drivers-for-7265ac-on-catalina.292207/page-74#post-2177829) - ketxs files for wifi/bluetooth connectivity using motherboard builtin wifi

## Installation Guide

1. [READ THIS FIRST!](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites)
2. [Create the BOOTABLE macOS via USB](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
3. [BIOS Configuration](https://github.com/isyan/gigabyte-z390-aorus-pro-wifi-opencore-hackintosh-install-guide/blob/main/images/bios/) 
   * Bios menu as image filename. e.g. boot.jpg
4. Insert bootable usb to pc usb port and turn on.
5. Press F12 while the Aorus logo is displaying to show the boot menu
6. Select the bootable usb on the boot menu picker
7. Setup/configure macOs

