
# TUF B760M PLUS i5 13600KF RX550 LEXA

## Screenshot  
![System Info](https://github.com/duongnguyen16/TUF-B760M-PLUS-i5-13600KF-RX550-LEXA/blob/main/Screenshot/MacInfo.jpg?raw=true)

## Attendtion!
This project was forked from **cuihairu** (https://github.com/cuihairu). You can view the original repository [here](https://github.com/cuihairu/TUF-GAMING-B760M-PLUS-WIFI-i714700KF-RX6950XT-Hackintosh).

## Modifications:
- Updated all **kexts** to the latest versions (**December 17, 2024**).  
- Changed **alcid (code)** to support the front audio port of the case (if you're using a different case, change the alcid until you find the correct one).  
- Added support for the **AMD RX 550 graphics card**.  


## Known Issues:
1. **Wi-Fi/Bluetooth is not working in macOS Sequoia**  
   - As of **December 17, 2024**, no kexts are available for macOS Sequoia. Therefore, these two components are non-functional (Ethernet still works fine).  
   - If you need Wi-Fi/Bluetooth, consider using **macOS Sonoma**.  

2. **Performance**  
   - macOS does not support **P-core and E-core**. As a result, performance (based on benchmarks) is significantly lower compared to Windows.  
   - **Note**: Some solutions exist to mitigate this issue. I will update as I test further.  


## Specs  

| **Component**         | **Details**                         |
|------------------------|-------------------------------------|
| **Mainboard**          | TUF GAMING B760M Plus Wifi D4       |
| **Processor**          | Intel Core i5 13600KF              |
| **Memory**             | Gskill RIPJAWS V 32 GB             |
| **Storage**            | SAMSUNG MZ7PC128HAFU-000H1         |
| **Graphics**           | AFox Radeon RX550 4G DDR5          |
| **Audio**              | Realtek ALC897                     |
| **Wi-Fi/Bluetooth**    | Intel AX201                        |
| **Ethernet**           | Realtek Gaming 2.5GbE Network Adapter |
| **Case**               | Jonsbo D31 STD Black               |


## Installation Notes:
1. **Generate SMBIOS** using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) and apply it to your `config.plist` before installation.  
2. **BIOS Settings**: Follow the guide [here](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#intel-bios-settings).  



## Acknowledgements

 - [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
 - [AppleALC Supported Codecs](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs)

