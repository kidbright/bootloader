# KidBright Bootloader

command for programming ESP-12F

	./esptool.py --port /dev/ttyUSB0 write_flash -fs 8m 0x00000 rboot.bin 0x82000 rom1.bin 0xfc000 blank4.bin
