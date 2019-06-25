# CAN Bus resources

## Table of content

[Overview](#Overview)  

[MCP2515 resources](#Resources)

[MCP2515 to Arduino](#Arduino)

[MCP2515 to RaspberryPi](#RaspberryPi)

[CAN Tools](#Tools)

[Vector CANoe simulator](#Canoe)

[Lectures and Presentations](#Pres)

[Articles and Documents](#Docs)

<a name="Overview"></a>
## Overview

List of articles, blog-posts, libraries and tools usefull when using a MCP2515 CAN Bus Interface. 

<a name="Resources"></a>
## MCP2515 Resources

[SHOP LINK: MCP2515 CAN Controller with TJA1050 Driver and SPI Interface](https://www.optimusdigital.ro/en/others/2392-modul-controller-can-mcp2515-cu-driver-tja1050-i-interfaa-spi.html)

[MICROCHIP: Stand-Alone CAN Controller with SPI Interface](http://ww1.microchip.com/downloads/en/DeviceDoc/MCP2515-Stand-Alone-CAN-Controller-with-SPI-20001801J.pdf)

<a name="Arduino"></a>
## MCP2515 to Arduino

[Arduino MCP2515 CAN interface library ](https://github.com/autowp/arduino-mcp2515)

[SHOP LINK: Arduino MEGA 2560 (ATmega2560 + CH340)](https://www.optimusdigital.ro/ro/compatibile-cu-arduino-mega/471-placa-de-dezvoltare-compatibila-cu-arduino-mega-2560-atmega2560-ch340.html)

[https://www.youtube.com/watch?v=3GmVrIWT3Bo](https://www.youtube.com/watch?v=3GmVrIWT3Bo)

[Arduino MCP2515 CAN Bus Interface Tutorial](https://www.electronicshub.org/arduino-mcp2515-can-bus-tutorial/)

[Wiring Arduino to MCP2515](https://cdn.instructables.com/FUY/QEZH/J2UPDZQZ/FUYQEZHJ2UPDZQZ.LARGE.jpg)

### Wiring Arduino UNO to MCP2515

| NAME | UNO | MCP2515 |
|:----:|:---:|:-------:|
|  INT |  2  |   INT   |
| MISO |  12 |    SO   |
| MOSI |  11 |    SI   |
|  SCK |  13 |   SCK   |
|  SS  |  10 |    CS   |

### Wiring Arduino MEGA2560 to MCP2515

| NAME | MEGA2560 | MCP2515 |
|:----:|:--------:|:-------:|
|  INT |     2    |   INT   |
| MISO |    50    |    SO   |
| MOSI |    51    |    SI   |
|  SCK |    52    |   SCK   |
|  SS  |    53    |    CS   |

<a name="RaspberryPi"></a>
## MCP2515 to RaspberryPi

[CAN-Bus with Raspberry Pi: HowTo/Quickstart MCP2515 Kernel 4.4.x+](https://vimtut0r.com/2017/01/17/can-bus-with-raspberry-pi-howtoquickstart-mcp2515-kernel-4-4-x/)

[raspberrypi.org: CAN bus on raspberry pi with MCP2515](https://www.raspberrypi.org/forums/viewtopic.php?f=44&t=141052&sid=37e6879817d1f410311246f97a0a20a3)

[How to Connect Raspberry Pi to CAN Bus](http://youness.net/raspberry-pi/raspberry-pi-can-bus)

[Say it with a CAN Bus and a Raspberry Pi](https://modis.io/blog/say-it-with-a-can-bus/)

<a name="Tools"></a>
## CAN Tools

[CAN utils](https://github.com/linux-can/can-utils) Also available on debian and ubuntu through package-managers or [deb package](https://packages.debian.org/sid/can-utils).

[CANard: Python library for CAN bus communication](https://pypi.org/project/CANard/)

Wireshark

<a name="Pres"></a>
## Vector CANoe simulator

[Presentation: Analysis and Test of CAN Applications](https://indico.esa.int/event/162/contributions/1184/attachments/1162/1375/Analysis_and_Test_of_CAN_Applications.pdf)

[Example: Getting started with CANoe ISO11783](https://assets.vector.com/cms/content/know-how/_application-notes/AN-ION-1-4200_Getting_Started_With_CANoe_ISO11783.pdf)

<a name="Canoe"></a>
## Lectures and Presentations

[NorthSec 2015 - Eric Evenchick - Hopping on the CAN bus](https://www.youtube.com/watch?v=eoQO5TVKgSE)

[Eric Evenchick - CANtact: An Open Tool for Automotive Exploitation](https://www.youtube.com/watch?v=77PXh8mqH98)

[Roderick Currie - Hacking the CAN Bus: Presentation](https://www.youtube.com/watch?v=WjncMlpX85I)

[DEF CON 26 CAR HACKING VILLAGE - Ben - CANT](https://www.youtube.com/watch?v=TRn_Rz2JIYQ)

<a name="Docs"></a>
## Articles and Documents
[Introduction to the Controller Area Network (CAN)](http://www.ti.com/lit/an/sloa101b/sloa101b.pdf)
