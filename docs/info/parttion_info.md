# 分区信息

| 显示名称 | 实际分区 | 用处 |
| ---- | ---- | ---- |
| DDR | /dev/block/mmcblk0p22 | |
| DRIVER | /dev/block/mmcblk0p30 | |
| LOGO | /dev/block/mmcblk0p17 | |
| aboot | /dev/block/mmcblk0p4 | |
| abootbak | /dev/block/mmcblk0p5 | aboot 备份 |
| boot | /dev/block/mmcblk0p25 | boot 引导 |
| cache | /dev/block/mmcblk0p28 | 缓存 |
| fsc | /dev/block/mmcblk0p19 | |
| fsg | /dev/block/mmcblk0p23 | |
| hyp | /dev/block/mmcblk0p10 | |
| hypbak | /dev/block/mmcblk0p11 | |
| misc | /dev/block/mmcblk0p18 | |
| modem | /dev/block/mmcblk0p1 | |
| modemst1 | /dev/block/mmcblk0p13 | |
| modemst2 | /dev/block/mmcblk0p14 | |
| oppodycnvbk | /dev/block/mmcblk0p15 | |
| oppostanvbk | /dev/block/mmcblk0p16 | |
| pad | /dev/block/mmcblk0p12 | |
| persist | /dev/block/mmcblk0p27 | |
| recovery | /dev/block/mmcblk0p29 | |
| reserve1 | /dev/block/mmcblk0p31 | |
| reserve2 | /dev/block/mmcblk0p32 | |
| reserve3 | /dev/block/mmcblk0p33 | |
| reserve4 | /dev/block/mmcblk0p34 | |
| rpm | /dev/block/mmcblk0p6 | |
| rpmbak | /dev/block/mmcblk0p7 | rpm 备份 |
| sbl1 | /dev/block/mmcblk0p2 | |
| sbl1bak | /dev/block/mmcblk0p3 | sbl1 备份 |
| sec | /dev/block/mmcblk0p24 | |
| splash | /dev/block/mmcblk0p21 | |
| ssd | /dev/block/mmcblk0p20 | |
| system | /dev/block/mmcblk0p26 | 系统 |
| tz | /dev/block/mmcblk0p8 | |
| tzbak | /dev/block/mmcblk0p9 | tz 备份 |
| userdata | /dev/block/mmcblk0p35 | 用户信息存储 |

以上信息可以使用一下命令获取(需要有 root 权限)

``` bash
ls -l /dev/block/platform/7824900.sdhci/by-name/
```
