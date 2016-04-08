
Presentation and code corresponding to 
**Raspberries, 2016**
*FADELab and Base42 Event - 2016/11/12 Hotel d'entitats de La Cellera de Ter*

## Objective
The objective of the presentation is describe the Go language and inform of the possibility of run a high level language as is Go 

Gobot and BCM2835 binding as possible ways to take the control of the hardware peripherals of the broadcom BCM2835 SoC.


## bcm2835 library

For more details see the previous presentation Go, Rapsberries GDB Barcelona event https://github.com/efarres/GoRaspberry

It provides access to GPIO and other IO functions on the Broadcom BCM2835 chip.

It provides functions for reading digital inputs and setting digital outputs, using SPI and I2C, and for accessing the system timers.

Pin event detection is supported by polling (interrupts are not supported).

BCM2835 is a binding between Go and the bcm2835 C Library, a great C library, very well documented. 

Library source is available at http://www.airspayce.com/mikem/bcm2835

C and C++ support for Broadcom BCM 2835 as used in Raspberry Pi projects.

Author: *Mike McCauley*
