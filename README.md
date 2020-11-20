# MSI GS66 Stealth 10SFS-480IT Hackintosh

| Specifications | Details |
|:-: |:-: |
| Processor | i7-10875H Hexa Core  |
| RAM | 32GB DDR4 |
| SSD | 2xNVMe |
| Graphics Card | Intel UHD Graphics |
| eGPU | Nvidia GeForce RTX 2070 Super Max-Q 8GB (disabled with -wegnoegpu) |
| Monitor | 15.6" Full HD 300Hz |
| Sound Card |  |
| Network Card | Killer 1650i (Intel AX201NGW) |

#### Current status:
Working:
- Audio
- Touchpad 
- Intel Graphics
- Keyboard
- USBs (apart from the Thunderbolt 3)
- Brightness adjustment
- Battery managment
- Power managment (Non-native because of CFG Lock)
- WiFi/BT (Intel drivers still in development, not realiable)

To be fixed:
- Sleep/Wake
- Ethernet
- USBs still need to be mapped

#### IMPORTANT

Please generate a new SMBIOS (MacBookPro16,1 or MacBookPro16,4) as I deleted my serials. 
Use https://github.com/corpnewt/GenSMBIOS
