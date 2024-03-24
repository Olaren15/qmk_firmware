Keyboard version: dz60rgb_ansi_v2_1

To put in dfu mode: hold escape when pluggin in the board

flashing will not work on linux. Use this command:
```bash
# Assumes keyboard is mounted in /mnt
dd if=<firmware>.bin of=/mnt/FLASH.BIN bs=512 conv=notrunc oflag=direct,sync
```
