

# Readme

This is the readme file for the Electronic Compass (E.C.) project. This project has the aim to create a low-cost, open-source electronic geological compass. This repository has the objective to document and share the hardware construction process and software development needed. 

The planned compass features are:


+ Measure dip and dip direction of a plane
+ Measure strike slip, trend and plunge
+ Different measures profiles
+ Automatic txt files save
+ Acceletometer and magnetometer calibration
+ More to come!

## Licences
Since the E.C. project covers hardware and software licences that cover both are necessary. You can find the choosen licences in the "Licences folder" in PDF and .txt format.

| Type | License name | Source link | 
| :----: |:----: | :----:|
| **Software** | GNU General Public License v3.0 or later | [SPDX](https://spdx.org/licenses/GPL-3.0-or-later.html) |
| **Hardware** | CERN-OHL-S-2.0 or any later version | [OHWR](https://ohwr.org/cern_ohl_s_v2.txt) |

Table: Licences used

The copyrights to both hardware and software are explicited in the copyright.pdf and copyright.md files and the original copies are stored in the License folder. If you want to apply any kind of change you **always need to log it in the changes.md file** and include all the original source and copyright files as per licences.

## Components list


The Electronic Compass components are searched to be the most cost-effective and easy to solder available that I could find. I provide the links from where the components are purchased but some are europe based (mostly Germany) so check if worldwide shipping is convenient or not.



| Component Name | Quantity | Price | Link |
|:---|:----:|:----:| ---: |
| Adafruit adalogger M0 | x1 | 26€ | [ThePiHut](https://thepihut.com/products/adafruit-feather-m0-adalogger) |
| GY-61 ADXL335 acceletometer | x1 | €6.79 | [AZ-Delivery](https://www.az-delivery.de/en/products/gy-61-adxl335-beschleunigungssensor-3-axis-neigungswinkel-modul-1?variant=20332875546720) |
| 128x32 Oled display | x1 | €6.29 | [AZ-Delivery](https://thepihut.com/products/adafruit-feather-m0-adalogger) |
| GY-271 QMC5883L magnetometer | x1 | €5.79 | [AZ-Delivery](https://www.az-delivery.de/en/products/gy-271-kompassmodul-kompass-magnet-sensor-fuer-arduino-und-raspberry-pi?variant=18912984432736) |
| SD card | x1 | may vary | [Amazon](https://www.amazon.com/)
| 1200mAh 3.7V LiPo battery | x1 | 5.36€ | [Welectron](https://www.welectron.com/LiPo-Pouch-Battery-503562-37V-1200mAh) |
| Potentiometer | x1 | ? | [Amazon](https://www.amazon.com/) |
| Buttons | x? | ? | [Amazon](https://www.amazon.com/) |


Table: Table of components



## Software used

To have a truly open-source project the software used is 100% free and open-source from the CAD project files to the software used to code and flash the code on the adalogger chip.

| Type | Software program | Source link | 
| :----: |:----: | :----:|
| CAD | FreeCAD | [FreeCAD](https://www.freecadweb.org/) |
| Electronics | KiCad EDA| [KiCad](https://kicad.org/) |
| Code environment and upload | ArduinoIDE | [Arduino](https://www.arduino.cc/en/software) |

Table: Software used

