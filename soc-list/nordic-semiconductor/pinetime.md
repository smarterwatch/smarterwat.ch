[<- Nordic Semiconductor](.)

# PineTime
Pine64 PineTime

## Hardware

| Component | Datasheet |
|-|-|
| NRF52832 SoC | [Link](https://infocenter.nordicsemi.com/pdf/nRF52832_PS_v1.0.pdf)|
| Sitronix ST7789 LCD Driver | [Link](https://wiki.pine64.org/images/5/54/ST7789V_v1.6.pdf) |
| Hynitron CST816S / CST716S | [Link](http://files.pine64.org/doc/datasheet/pinetime/CST816S%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8CV1.1.pdf) |
| Bosch BMA421 Accelerometer | [Brief](http://files.pine64.org/doc/datasheet/pinetime/BST-BMA421-FL000.pdf), [Link](https://wiki.pine64.org/images/c/cc/Bst-bma400-ds000.pdf)
| TianYiHeXin HRS3300 Heartrate Sensor | [Link](http://files.pine64.org/doc/datasheet/pinetime/HRS3300%20Heart%20Rate%20Sensor.pdf)|
| SPI Flash | ~~Link~~ |
| Power Management Unit | ~~Link~~ |

## Vendors

| Vendor | Price | URL |
|-|-|-|
| Pine64 | $24.99 + Shipping | [https://store.pine64.org/?product=pinetime-dev-kit](https://store.pine64.org/?product=pinetime-dev-kit) | 

## General Information
As of mid-July 2020, the PineTime is known only to ship with the CST816 touch controller. This means you can put the touch controller to sleep and it will wake with a touch.  

The PineTime has a slightly smaller display than the P8, and the display is slightly cooler in colour temperature. The enclosure is identical to that of the Y7 Pro by DaFit/MoYoung, and however the Y7 Pro has different internals.

## Development Efforts
See https://wiki.pine64.org/index.php/PineTime#Development_efforts for info on all development efforts. 

 For reference, both [ATCwatch](https://github.com/atc1441/ATCwatch) and [p8-firmware](https://github.com/0x416c6578/p8-firmware) can be compiled for the PineTime, with the former having builds available [here](https://github.com/atc1441/DaFlasherFiles).