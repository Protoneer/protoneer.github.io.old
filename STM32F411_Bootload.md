
[Zadig USB driver](https://zadig.akeo.ie/)

dfu-utils -l

Get the device id , replace it in the -S parameter

dfu-util -S 398238553339 -a 0 -s 0x08000000:leave -D adafruit-circuitpython-stm32f411ce_blackpill-en_US-5.2.0.bin
