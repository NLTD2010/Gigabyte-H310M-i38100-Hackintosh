# <div align="center">Gigabyte H310M DS2 i3-8100 Hackintosh</div> 

## Intro

| | Version |
|-|---------|
| OpenCore | 0.9.3 Mod |
| macOS | Monterey 13.4.1 |


## Desktop Specification

|                     | Specifications| Note |
| ---------------------------- | ---------------------- |------------------|
| ``CPU``| Intel Core i3-8100 |  |
| ``Memory``| 8GB DDR4 |  |
| ``iGPU``| Intel UHD Graphics 630 |  |
| ``Bluetooth``| ORICO BTA-508 | Native? with BluetoolFixup|
| ``Ethernet``| RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | Use [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases). |
| ``Audio``| Realtek ALC887 | Add `alcid=1` to boot-arg or add layout-id to DeviceProperties. |

## Features

| ``Features``|``Working``| 
|-------------|-----------|
| ``Audio``|✅|
| ``Wifi and Bluetooth``|✅|
| ``Keyboard``|✅|
| ``Headphone Jack``|✅|
| ``Graphics``|✅|
| ``Power Management``|✅|                                                                        
| ``USB Port``|✅|
| ``Facetime and iMessage``|✅|
| ``Ethernet``|✅|
| ``Sleep``|✅|
