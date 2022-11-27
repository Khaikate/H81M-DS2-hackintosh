# H81M-DS2-hackintosh

## PC specification

macOS Monterey 12.6 + OpenCore 0.8.6


| Part  | Info |
| ------------- | ------------- |
| Mainboard | Gigabyte H81M-DS2 |
| CPU:  | Intel Xeon E3-1240 v3 (Haswell, 3,40 GHZ up to 3.80 GHz, 4 core 8 thread)  |
| RAM:  | 8GB (DDR3)  |
| GPU:  | NVIDIA Geforce GTX 1050TI (GP107, 128bit, 4GB GDDR5) |
| Network: | Realtek RTL8111 |
| Sound:  | Realtek ALC887 (best layout-id in my build is 3)  |
| SMBIOS:  | iMacPro1,1  |

## Compatible with

- [x] Windows 10
- [x] macOS Monterey 12.6
- [ ] macOS Ventura 13.0 (Graphics not working)

## What is working

- [x] Microphone (pink 3.5mm input)
- [x] Speaker (green 3.5mm input)
- [x] Services (App Store, Apple Music,...)
- [x] Graphics card
- [x] USB 2.0/3.0
- [x] Bootcamp
- [x] HoRNDIS
- [ ] You tell me.

## How to install graphic card
- Patch OpenCore Legacy Patcher 0.4.11 ( 0.5.0 and higher not working )
- Clean and Reset NVram before Patch OpenCore Legacy Patcher

## Configurations

#### PlatformInfo
`iMacPro1,1` smbios 
You should set your own `MLB` / `ROM` / `SystemSerialNumber` / `SystemUUID` .

## Screenshot

![](SS.jpg) 
