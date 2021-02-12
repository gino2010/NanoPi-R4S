# NanoPi R4S Firmware

This project is original from https://github.com/LewiVir/NanoPi-R4S

Create this own repo to build firmware for myself with customize configuration

## Tips
* Default Gateway: 192.168.2.1
* Default Password: password

## TF Size
Lean OpenWrt 16G is for 16GB TF card

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
* https://github.com/SuLingGG/OpenWrt-Rpi
* https://github.com/friendlyarm/friendlywrt
* https://github.com/P3TERX/Actions-OpenWrt
