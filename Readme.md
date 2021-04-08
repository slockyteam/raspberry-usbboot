https://www.raspberrypi.org/documentation/hardware/computemodule/cm-emmc-flashing.md

make

sudo ./rpiboot

diskutil list

sudo dd if=image-lite.img of=/dev/disk2 bs=32m
