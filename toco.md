# WELCOME TO PROJECT ELIXIR - ANDROID 13.0

![Changelog](https://i.imgur.com/3uuYftu.png)

## v3.6 toco Changelog
```
- audio: Fix 24bit audio playback
- dolby: Drop AC4 codec support
- overlay: Disable UI touch sounds by default
- overlay: List aux camera IDs ignored by Aperture
- overlay: Use AOSP default ripple animation duration
- overlay: Unlock additional camera framerates
- parts: Add Dirac logo
- powerhint: Don't mess with CPU FREQ
- powerhint: Set GPU idle timeout to match kernel
- prop: Disable SF composition prediction model
- prop: Force device to treat 170M as sRGB in SF
- prop: Remove unused persist.bluetooth.a2dp_offload.cap
- props: Move fling props to system to avoid denials
- props: Move IORapd props to system to avoid denials
- sepolicy: Allow parts to get SettingsLib prop
- sepolicy: Allow system_server to set tethering properties
- Update blobs from sweet V13.0.16.0.SKFMIXM
- Update system from LA.QSSI.13.0.r1-08600-qssi.0
- Update system from LA.QSSI.13.0.r1-09000.01-qssi.0
- vendorsetup: Drop miuicamera for now
- vendorsetup: Switch to PlayGroundTC Clang 17
```

## v3.5 toco Changelog
```
- Add AOSP RCS packages
- Add compilation of legacy audio
- Add wakelock to citsensor service group
- Add xiaomi misys support
- configs: Update qdcm display calibration to MIUI V13.0.4.0
- Configure aux camera for Aperture
- Drop custom APM flag along with no-op audio flags
- Fixup Vulkan deQP permission copy
- gps: Silence all warnings
- gps: Update to LA.UM.9.1.r1-13000-SMxxx0.QSSI13.0
- Import Pixel thermal HAL
- Import Xiaomi displayfeature
- Inherit several Android Go configurations
- media: Add swap width and height feature
- media: Fix VTS issue
- Move to common Xiaomi displayfeature HIDL
- overlay: Add default vibration intensites
- overlay: Configure SQLite to operate in MEMORY mode
- overlay: Don't pin camera app in memory
- overlay: Restore COLOR_MODE_SATURATED
- overlay: Set google autofill service as default
- overlay: Update pinner list
- overlay: Update vibration patterns from stock
- parts: Add Dirac logo
- parts: Disable startup provider
- parts: Drop support for Hi-Fi
- parts: Remove proximity sensor gestures
- parts: Restore MiSound scene on boot complete
- powerhint: Fix undefined value in Node[PMQoSCpuDmaLatency]
- powerhint: Import camera hints
- powerhint: Restore EnergyAware node
- powerhint: Set camera cpuset to little cores when unused
- prop: Add touch improvements sysprops
- prop: Disable QCRIL power saving
- prop: Disable Skia tracing by default
- prop: Do not block binder thread on incoming calls
- prop: Don't set to adaptive mode by default
- prop: Enable apk fs-verity
- prop: Enable DPM Connection Tracking (CT)
- prop: For smoother scrolling and better responsiveness
- prop: Pull props for USB controller configuration
- prop: Remove QTI BT stack bits
- prop: RIL edits for battery life
- prop: Switch to AutoSingleLayer A13 setting
- prop: Use HintManager for HWUI
- Purge mi_thermald
- Remove references to a2dp module
- rootdir: Enable suspend to RAM
- rootdir: Import oriole cpuctl tuning
- rootdir: Remove package cache on early boot
- sepolicy: Address more batterysecret denials
- Speed profile services and wifi-service
- Switch to common QTI vibrator HAL
- Switch to EROFS for relevant partitions
- Switch to OnePlus Dolby
- Update blobs from sweet V13.0.14.0.SKFMIXM
- Update blobs from sweet V13.0.15.0.SKFMIXM
- Update build fp & desc to MIUI V13.0.4.0.SFNMIXM
- Update system blobs from LA.QSSI.13.0.r1-08200-qssi.0
- Update system from LA.QSSI.13.0.r1-07400-qssi.0
- Use LZ4 compression for ramdisks
- Use RSA4096 key also for vbmeta_system
- wifi: Create another interface during driver load
- WifiSM6150: Enable set channel on NDP setup
```

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
