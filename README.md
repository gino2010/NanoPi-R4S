# NanoPi R4S Firmware

This project is original from https://github.com/LewiVir/NanoPi-R4S

Create this own repo to build firmware for myself with customize configuration

No overclocking. In long-term use, the equipment is maintained at about 47 degrees, no need for additional fans

Remove rarely used components, keep minimum available set

## Tips
* Default Gateway: 192.168.2.1
* Default Password: password

## File System Type
Refer to [Filesystems](https://openwrt.org/docs/techref/filesystems) 
* squashfs read only (Recommended), smaller image from gzip file
* Ext2/3/4 is used on x86, x86-64 and for some arch with SD-card rootfs

## TF Size
Lean OpenWrt 16G is for 16GB TF card

Lean OpenWrt 32G is for 32GB TF card, and only provide image within SQUASHFS file system

You can edit below item to adjust partition size
```
CONFIG_TARGET_ROOTFS_PARTSIZE=14336
```

## How to Build Image
This repo is built by github actions

### Github Actions
https://docs.github.com/en/actions

### Crontab Job
Use this website to check you scheduler job

https://crontab.guru/

## References
* [SuLingGG/OpenWrt-Rpi/README.md](https://github.com/SuLingGG/OpenWrt-Rpi/blob/main/README.md)
* https://github.com/coolsnowwolf/lede
* https://github.com/immortalwrt
* https://github.com/SuLingGG/OpenWrt-Rpi
* https://github.com/friendlyarm/friendlywrt
* https://github.com/P3TERX/Actions-OpenWrt
* https://github.com/WikiHacker/WikiHacker-R4S-2021
* https://github.com/DHDAXCW/NanoPi-R4S-2021