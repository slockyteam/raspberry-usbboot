make

sudo ./rpiboot

diskutil list

sudo dd if=image-lite.img of=/dev/disk2 bs=32m
