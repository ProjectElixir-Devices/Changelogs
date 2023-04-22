![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

## v3.7 Veux/Peux
```
•Comes with April Security Patch
•Volume steps are increased to 18
•Fixed hyper orange Night Light
•Fixed Quicksettings Lags
•Fixed fake Root Detection in few Apps
•Includes Launcher 3
•Miui Camera is shipped by default with Rom
•Updated surfaceflinger props(Made UI much more fluent.)
•Fixed Qs Pulldown lags
•Improved overall stability and battery backup seems good too.
```

## v3.6 Veux/Peux
```
Improved Display Colors
Some minimal fixes and Improvements
```

## v3.5 Veux/Peux
```
veux: Import XiaomiParts 
veux: Enable set channel on NDP setup 
veux: wifi: Configure correct overlay configuration. 
veux: Enable zygote critical window 
veux: gps: Update to LA.UM.9.14.r1-19200.02-LAHAINA.QSSI13.0 
veux: qcc-tr: Define new AID for qcc-trd 
veux: config.fs: Add mapping for imsdaemon 
veux: config.fs: init: add AID_VENDOR_FASTRPC group for fastrpc 
veux: Slim up filesystem configuration 
veux: Use RSA4096 key also for vbmeta_system 
veux: Removing GSI keys 
veux: Switch BtAudio to AIDL 
veux: Drop qti thermal 2.0 service hals 
veux: Remove non-existing or implicitly included IPACM packages 
veux: Remove A2DP input module in audio policy configuration 
veux: extract-files: Allow extracting proprietary-files for recovery 
veux: Add Aperture to config_cameraAuxPackageAllowList 
veux: Migrate vendor.camera.aux.packagelist to overlay 
veux: Remove QTI BT stack bits 
veux: Move BT profiles props to vendor 
veux: overlay: Remove BT related configs 
veux: Remove Bluetooth power overlays 
veux: Don't override bluetooth name on recovery 
veux: Update build fingerprint version 
veux: Import more vendor blobs from stock 
veux: Prevent adding same dependency twice in blob_fixup 
veux: Inherit updatable_apex.mk 
veux: Symlink libvndfwk_detect_jni.qti for CneApp 
veux: Create Adreno symlinks   
veux: Fix bluetooth and USB device name props assignment
```

## v3.4 Veux/Peux
```
Synced with latest source changes
Miscellaneous other changes to make rom smoother and better
```

## v3.0 Veux/Peux

```
veux: Add Bluetooth power overlays to sysprops
veux: Use the ?= operator so BT properties can be overridden
veux: Set default the Bluetooth class of device
veux: Update LE Audio profile properties to match spec and implementa…
veux: Enable bluetooth profiles with product.prop
veux: Remove junk BT props
veux: Improve camera shim
veux: shim the GetPreviewImageData symbol on libpiex
veux: Set show avatar display settings
veux: proprietary-files: Update veux vendor blobs
veux: Unpin updatable-media from memory
veux: proprietary-files: Import missing NFC lib
veux: Updated multihal to use new sensors AIDL interface.
veux: Fix Wbitwise-instead-of-logical introduced by clang-r445002
veux: Inherit developer gsi keys
veux: Remove ndk_platform backend. Use the ndk backend.
veux: Removed audio A2dp from device.mk
veux: overlay: Add reboot_fastboot action to power menu
veux: Strip size of com.qti.node.mialgocontrol.so
veux: proprietary-files: Update veux vendor blobs
veux: prebuilts: Update Google Camera Go v3.6.455515391
```

## v3.1 Veux/Peux

```
veux: overlays: Display correct charging speed 
veux: overlay: Set default value night display color temperature 
veux: Fix AAPT config 
veux: Drop sound trigger 
veux: overlay: Enable front-facing camera protection 
veux: overlay: Configure camera cutout 
veux: prebuilts: Update Google Camera Go v3.8.466520855 
veux: overlay: Set screen timeout to 30 seconds 
veux: proprietary-files: Back 32-bits RIL lib
veux: Reorder kernel session 
veux: Drop DTC and LLVM flags for building kernel
veux: Use libhidlbase from vndk v32 for vendor/lib64/libvendor.goodix… 
veux: sepolicy: Allow apps and camera HAL access to secure ADSP domain 
veux: sepolicy: Allow neural networks HAL to read ADSP properties 
veux: Make fastrpc_shell_3 publicly available 
veux: gpt-utils: Update PTN_SWAP_LIST and handle multiimg(oem/qti), 
veux: gpt-utils: Do fsync after writing partition entries 
veux: gpt-utils: Add product to ab partiti
veux: gpt-utils: Drop unused sparse_crc32 
veux: bootctrl: Remove bootctrl.xiaomi_holi target 
```
