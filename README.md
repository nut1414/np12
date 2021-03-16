# np12
 yet another 12 keys macro pad using [QMK Firmware](https://github.com/qmk/qmk_firmware)

![np12](np12.png)

## Parts
 - a generic Arduino Pro Micro (or other pin compatible)
 - 12x MX Switches
 - an EC11 encoder
 - *(Optional)* a 6mm button for entering the bootloader
 - *(Optional)* 12x Kailh hot-swap sockets
 - *(Optional)* PJ320a TRRS Jack if you want to do a split-board

## Pin Configuration
 |Row|Pin|Arduino Wire Pin|
 |:--:|:--:|:--:|
 |0|D7|6|
 |1|E6|7|
 |2|B4|8|
 |3*|F6|A1|

 |Col|Pin|Arduino Wire Pin|
 |:--:|:--:|:--:|
 |0|D1|2|
 |1|D0|3|
 |2|D4|4|
 |3|C6|5|
 |4|F7|A0|
 
 *Used only for rotary encoder switch.
 