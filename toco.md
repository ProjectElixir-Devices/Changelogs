# WELCOME TO PROJECT ELIXIR - ANDROID 13.0

![Changelog](https://i.imgur.com/3uuYftu.png)

## v3.12 toco Changelog
```
- Add fastcharge implementation
- Add keylayout mapping for Xbox360 compatible controllers
- Build Lineage Health HAL
- Build needed `libbthost_if_sink` package
- Import Qualcomm CameraX Vendor Extensions
- keylayout: Import joystick keylayouts from 1Controller v1.5.2
- parts: Refactor ClearSpeakerFragment code
- parts: Rename app to Xiaomi Parts
- Restore soundtrigger
- Ship VantomKernel v4.14.325
- Update to Moto Dolby Atmos v06.03.1558
- wifi: Enable Optimized Power Management
- wlan: Remove arp_ac_category INI item
- wlan: Remove obselete gEnableBypass11d config
- wlan: Remove obsolete gEnableSifsBurst config
- wlan: Remove obsolete INI called gFixedRate
- wlan: Remove obselete McastBcastFilter config
- wlan: Remove obselete SapSccChanAvoidance config
```

## v3.11 toco Changelog
```
- configs: Update dax-default profiles
- Explicitly disable serial console
```

## v3.10 toco Changelog
```
- Add needed librmnetctl.so lib
- Build vendor.xiaomi.hardware.touchfeature from source
- Decommonize misys prebuilts
- Disable continuous transaction tracing on all build types
- Disable per-cgroup PSI accounting
- Drop QCOM wfd HDCP support
- Drop unused RIL properties
- Drop vestigial FM board-flags
- Enable casefolding support on userdata
- Fix IMS symlink as per dynamic partitions
- Fix libGLESv2_adreno.so symlink 
- media: Add Vorbis Decoder 
- parts: Use vector drawable for Dirac™ logo
- prop: Default to boosted color mode
- prop: Disable debug.sf.latch_unsignaled 
- prop: Use FUSE passthrough by default
- rootdir: Don't specify fstab path unnecessarily
- sepolicy: allow system app access zram0
- sepolicy: Label fpc wakeup node
- Set PRODUCT_SET_DEBUGFS_RESTRICTIONS
- Ship VantomKernel v4.14.320
- Switch to Moto Dolby
- Update CarrierConfig from LA.QSSI.13.0.r1-10000.02-qssi.0
- Update common blobs from sweet MIUI V14.0.4.0.TKFMIXM
- Update system blobs from LA.QSSI.13.0.r1-10000.02-qssi.0
```

## v3.9 toco Changelog
```
- Ship VantomKernel v4.14.318
```

## v3.8 toco Changelog
```
- Ship VantomKernel v4.14.314
- Switch to common Xiaomi 1.0 sensors implementation
- Update blobs from LA.QSSI.13.0.r1-09700-qssi.0
- Update CarrierConfig from LA.QSSI.13.0.r1-09700-qssi.0
```

## v3.7 toco Changelog
```
- audio: Use 24bit as primary output
- Import Xiaomi TouchFeature service
- overlay: Disable lock screen rotation
- overlay: Disable Pocket Lock
- overlay: Fix hyper orange night light
- overlay: Update battery info every second when charging
- parts: Remove Dirac logo
- parts: Update from sdm845-common
- prop: Redefine bluetooth a2dp offload capabilities
- Restore QCOM wfd HDCP support
- rootdir: Remove deprecated max comp streams
- sepolicy: Address location denials
- sepolicy: Update fast charging perms
- sepolicy: Update some Dolby sepolicy
- Update adreno stack from LA.UM.9.14.r1-21000-LAHAINA.QSSI13.0
- Update ADSP from LA.UM.9.1.r1-12900-SMxxx0.0
- Update blobs from sweet V14.0.1.0.TKFMIXM
- Update gps configs from LA.UM.9.1.r1-12900-SMxxx0.0
- Update keymaster from LA.UM.9.1.r1-12900-SMxxx0.0
- Update some blobs from msmnile LA.UM.9.1.r1-12900-SMxxx0.0
- Update system from LA.QSSI.13.0.r1-09400.01-qssi.0
- Update ueventd from LA.UM.9.1.r1-12900-SMxxx0.0
```

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
