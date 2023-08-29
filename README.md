# Pi-DI

The Raspberry Pi Zero W can indeed run full DtCyber, yes.

I feel that doing so is a huge drain on the resources in a typical battery operated application for the Raspberry Pi Zero.

This project will implement the Control Data Cyber Ethernet DI, thus not only allowing the Pi to idle more, but to also have more resources available to the Raspian or bsd side, for actually doing things.

One each selectable Raspian/bsd, CDCNet, or DI Console port, initially, using the standard Pi serial console; All three possibly similar to the SCO or screen(1) virtual console switching? Any / All can be enabled / disabled (headless = yes).

Access to Pi pins and interfaces, with at least compass and ftn5 API. This will include SPI, I2C, and 1Wire, as well as parallel channel-wide I/O.  (Maybe a test program for a Cyber API to a 20x2 LCD or VFD, they are like two bucks).

Three DI types will be supported, Version 1 (68k), Version 1 (68k) with 128k, Version 2 (68030) with 4M-16M in 4M increments.

Access to USB (at least HID (Anyone got a USB SpaceBall?))??  Access to Bluetooth??  We'll see!!  A 16 meg 68k/'030 emulator can do quite a bit.
