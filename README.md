# macOS on ThinkPad T440

![Catalina (10.15.7) on ThinkPad T440](!screenshot-1.png)
![ThinkPad T440 running Catalina 10.15.7](!screenshot-2.jpg)
_Catalina (10.15.7) on ThinkPad T440 (Mojave also works)_

## What works

- Intel HD 4400 Graphics QE/CI
- USB Ports
- Intel Ethernet
- Audio (All Inputs & Outputs with combojack)
- Sleep and Wake
- Mini DisplayPort and Mini DisplayPort Audio
- CPU and IGPU Power Management
- Battery Status
- Brightness
- Function Keys (Fn)
- ClickPad and TrackPad
- Integrated Camera
- Wireless (Intel) work with [itlwm](https://github.com/OpenIntelWireless/itlwm) (enable in config)

## Known problems

- Bluetooth
- Fingerprint Reader


## BIOS settings

| Item | Setting |
| ------------- | ------------ |
| Security Chip | Disabled |
| Memory Protection Execution Prevention | Enabled |
| Virtualization | Enabled |
| Fingerprint Reader | Disabled |
| Secure Boot | Disabled |
| UEFI/Legacy Boot | UEFI Only |
| CSM Support | YES |
| Boot Mode | Quick |

## Tools

- [InstallDiskCreator](https://macdaddy.io/install-disk-creator/) to create a USB installer
- [Clover Bootloader](https://github.com/CloverHackyColor/CloverBootloader/releases) (r5122) to modify the EFI Partition of the USB drive
- [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/) for some final EFI file modifications

### Reference links

- [Create a MacOS Catalina 10.15.0 USB Installer w/Clover Bootloader](https://hackintosher.com/forums/thread/guide-how-to-create-a-macos-catalina-10-15-0-usb-installer-drive-w-clover.2836/)
- [Guide: Lenovo ThinkPad T440](https://www.tonymacx86.com/threads/guide-lenovo-thinkpad-t440.245562/)