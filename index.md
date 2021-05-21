# DIR882刷openwrt记录

#### 首先刷回原厂固件

1. 上电时按住WPS键10秒进入breed界面，点击固件更新，点击编程器固件，文件选择**DIR-878_A1_DDWRT_FULL.bin**, 更新
2. 更新完成之后重启，再次进入breed界面，继续点击固件更新，选择更新bootloader，选择文件**mtd0-u-boot.bin**, 重启
3. 断电后按RESET键，上电10秒松开，进入DLINK恢复界面，选择```DIR878A1_FW101B04.bin, 刷完之后重启
4. 断电后按RESET键，上电10秒松开，进入DLINK恢复界面, 选择**DIR882A1_Middle_FW_Unencrypt.bin**, 更新重启

#### 刷openwrt
5. 断电后按RESET键，上电10秒松开，进入DLINK恢复界面, 选择**openwrt-ramips-mt7621-dlink_dir-882-a1-squashfs-factory.bin**, 更新重启

