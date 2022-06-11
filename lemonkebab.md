# lemonkebab: OnePlus 8T/9R

## Corvus VS3.1 - Medusa

- Switched to libperfmgr
- Switched to erofs
- Miscellaneous kernel phukery
- Bootloader lock support (Only if the build is flashed through some recovery and not through fastboot)
- Inbuilt recovery has issues so flash through either TWRP or fastboot if even TWRP doesn't work
- Since the inbuilt recovery has issues, it is discouraged to lock the bootloader for now
