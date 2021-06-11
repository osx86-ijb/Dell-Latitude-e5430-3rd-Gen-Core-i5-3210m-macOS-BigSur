
# Dell Latitude e5430 Intel Core i5 3210m macOS OpenCore EFI

This repository and project hosts the files necessary to boot macOS Big Sur successfully on the Dell Latitude e5430 3rd Generation Core i5 3210m notebook.

![Dell Latitude e5430 Notebook](https://i.ibb.co/TtHJR2j/3764-dell-latitude-e5430-3.jpg)

## Acknowledgements

 - [Core x86 Group & Team](https://discord.corex86.com)
 - [Dortania Team for their OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

  
## Authors

- [@osx86_iJB](https://www.github.com/osx86-ijb)
  

## Deployment

To deploy this project properly, please obtain the EFI folder from this repository, edit the config.plist to generate new serial number, rom, UUID, etcetera, then save config.plist, and place the files onto the appropriate ESP EFI partition in order to boot using OpenCore bootloader and proceed with your installation of macOS.
  
## Documentation

_*The hardware in this Laptop is as follows:*_

- **AUDIO CHIPSET:** IDT 92HD93BXX + Intel HDMI Output
- **CPU:** Intel Core i5-3210M 2.5Ghz Ivy Bridge
- **GPU:** Intel HD Graphics 4000
- **LAN CHIPSET:** Broadcom NetXtreme BCM5761 Gigabit Ethernet
- **RAM:** 16GB 1600MHz DDR3
- **STORAGE / SSD:** Patriot Burst 120GB SSD
- **WIFI + BLUETOOTH:** Broadcom BCM94352HMB Azurewave AW-CE123H + Bluetooth 4.0
