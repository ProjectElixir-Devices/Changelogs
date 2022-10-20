# WELCOME TO PROJECT ELIXIR - ANDROID 13.0

![Changelog](https://i.imgur.com/3uuYftu.png)

## v3.2 toco Changelog
```
- Add xiaomi cit sensor service
- Drop unnecessary overlay configs
- livedisplay: Fix racy init
- overlay: Remove COLOR_MODE_SATURATED
- parts: Dirac fixes
- parts: Import BootCompletedReceiver IntentFilter
- parts: Move Thermal Profiles to system section
- Remove some packages at build time
- Restore ims-vt prop & overlay
- rootdir: Remove discard command tuning
- sepolicy: Address more health denials
- Ship VantomKernel v4.14.295
- Switch MiuiCamera repo
- udfps: Hander -> Handler
- Update from LA.QSSI.13.0.r1-06400-qssi.0
- Update system blobs from LA.QSSI.13.0.r1-05800-qssi.0
```

## v3.1 toco Changelog
```
- Build libldacBT packages
- Drop audio A2dp
- Drop keylayout
- Enable recovery updater lib
- Move Xiaomi Doze to stock ambient display preference
- overlay: Checkout CarrierConfig from LA.QSSI.13.0.r1-05500-qssi.0
- overlay: Drop dead hbm type overlay
- overlay: Remove BT related configs
- overlay: Update multiple vibration intensity levels config for T
- parts: Avoid unsafe boot completed receiver
- parts: Fix app mode layout height for Android 13
- powerhint: Remove schedtune.prefer_high_cap boosting
- prop: Add a system property for System UI compiler filter
- prop: Add new vendors for Bluetooth config migration
- prop: Disable LE audio related profiles
- prop: Drop GCam props
- prop: Enable Audio Support for Hearing Aids central support
- prop: Enable zygote critical window
- prop: Import suspend properties from gs101
- Refactor kernel configuration
- releasetools: Drop firmware inclusion
- releasetools: Use unique version-baseband strings for different regions
- rootdir: Drop power hals nodes permission
- rootdir: Drop wrappedkey
- rootdir: Set readahead_size_kb=128 on fstab
- sepolicy: Label qcom extcon sysfs
- sepolicy: Remove debugfs related rules
- Shim the GetPreviewImageData symbol on libpiex
- Switch to AOSP BT stack properly
- udfps: Update handler methods
- Update Adreno stack from LA.UM.9.14.r1-20200-LAHAINA.QSSI13.0.
- Update common system blobs from T
- Update wfdconfig from curtana
- Uprev android.hardware.bluetooth.audio & add to fcm
- Uprev audio hal to 7.1
```
## Note:
```
- SELinux is Enforcing
- OTA Supported
- GApps are included
- Based on Vantom kernel
- ONLY OrangeFox or TWRP recovery for A13 is recommended
- Recommended Firmware : MIUI Global V13.0.2.0
- CLEAN FLASH is necessary for first-time installation
