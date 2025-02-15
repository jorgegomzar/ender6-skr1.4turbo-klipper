# Custom Ender 6

- Base ender 6 printer
- BTT skr 1.4 turbo board
- Klipper as firmware running on RaspberryPi3A+

## Wiring

Just follow the wiring on the PDF from this repo.

## Firmware

Follow this video for the skr board:

![https://www.youtube.com/watch?v=N41JY1Gukuk&t=1214s&ab_channel=Vector3D](https://www.youtube.com/watch?v=N41JY1Gukuk&t=1214s&ab_channel=Vector3D)

with some changes:

- build the klipper.bin
- rename it to firmware.bin
- move it to SD card with FAT32 format
- install the firmware in the board by inserting the SD card, wait for a few seconds and then reset the board
- you can follow the rest of the video as usual

Then, for the configuration just replace the printer.cfg with the one in this repo.
