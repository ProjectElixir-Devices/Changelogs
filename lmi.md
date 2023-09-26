![Changelog](https://i.imgur.com/VHEzeIF.png)

### Project Elixir for POCO F2 Pro (lmi) Changelogs

### v3.12 POCO F2 Pro (lmi)

- Rebase Kernel from CLO LA.UM.9.12.r1-15600-SMxx50.0
- Upstream kernel to 4.19.294
- Enable BT low power adaptive control feature
- Enable TWS plus feature using persist property
- prop: Enable Qualcomm TrueWireless™ Stereo
- Add simple FEAS support
- Switch back to QTI perf
- Switch to kernel based DT2W
- Switch to AutoSingleLayer
- Steal SurfaceFlinger offsets from taro
- parts: Add a setting to calibrate the motor
- parts: Implement HBM & Auto HBM
- Disable HBM when DC Dimming enabled
- hbm: Add preference for time-based HBM disable
- hbm: Do not enable HBM if DC Dimming is ON
- props: Properly disable phantom process killing
- Tune zram performance
- Change zram swap size and swappiness
- Enable zram writeback
- fstab: Switch zram swap to /data/per_boot
- init: Set 50% Zram size
- sepolicy: Allow ioctl to zram_swap for performance
- sepolicy: Allow system_app to access zram sysfs nodes
- Remove max ZRAM compression streams setting

### Important Note
- Make sure to use V14.0.5.0.SJKCNXM firmware
