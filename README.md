Presentation and code corresponding to 
**Raspberries, 2016**
*FADELab and Base42 Event - 2016/11/12 Hotel d'entitats de La Cellera de Ter*

## Objective
The objectives of the presentation are:

- Describe the SBC Raspberry Pi
- Describe the Go language and inform of the possibility of run a high level language as is Go over the Raspberry Pi.
- Preser Gobot and BCM2835 binding library as possible ways to take the control of the hardware peripherals of the broadcom BCM2835 SoC.

## Presentation online
"Raspberries, 2016" slides are stored in the [preset format](https://godoc.org/golang.org/x/tools/present), you can see the presentation online at [Raspberries, 2016](http://go-talks.appspot.com/github.com/efarres/RaspberryPi-2016/RaspberryPi_2016_day1.slide)

## Gobot
>[Gobot](http://www.gobot.io) is a framework for robotics, physical computing, and the Internet of Things, written in the Go programming lnaguage.

## About bcm2835 library

It provides access to GPIO and other IO functions on the Broadcom BCM2835 chip.

It provides functions for reading digital inputs and setting digital outputs, using SPI and I2C, and for accessing the system timers.

Pin event detection is supported by polling (interrupts are not supported).

BCM2835 is a binding between Go and the bcm2835 C Library, a great C library, very well documented. 

Library source is available at [http://www.airspayce.com/mikem/bcm2835](http://www.airspayce.com/mikem/bcm2835) Author: *Mike McCauley*

For more details see the previous presentation Go, Rapsberries at GDB Barcelona event [GoRaspberry](https://github.com/efarres/GoRaspberry)
