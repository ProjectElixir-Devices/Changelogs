![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for MI 11 (venus) Changelogs

```
Build type: Monthly
Device: Xiaomi 11 (venus)
Device maintainer: Flower Sea
Required firmware: build-in
```

# v3.3 venus
## device/xiaomi/sm8350-common
* sm8350-common: rootdir: Remove discard command tuning
* sm8350-common: Remove odex/oat files from pinner list

## device/xiaomi/venus
* venus: Don't sign Wifi RROs with platform cert 
* venus: Set default hotspot ssid

## kernel/xiaomi/venus
* Merged the CLO tag "LA.UM.9.14.r1-20800-LAHAINA.QSSI13.0"
* Kernel version: 5.4.197 -> 5.4.210
* net: wireguard: Update to version 1.0.20220627
* cert host tools: Stop complaining about deprecated OpenSSL functions 
* qcacld-3.0: Add time slice duty cycle in wifi_interface_info 
* qcacmn: Add time slice duty cycle attribute into QCA vendor command 
* media: meson: vdec: fix possible refcount leak in vdec_probe() 
* qcacld: disable DFS on AP mode 
* sock: remove one redundant SKB_FRAG_PAGE_ORDER macro 
* zram: do not waste zram_table_entry flags bits 
* ANDROID: binder: retry security_secid_to_secctx() 
* FROMGIT: Binder: add TF_UPDATE_TXN to replace outdated txn 
* ANDROID: Configure out the macros in android_kabi and android_vendor 
* drivers/base/memory.c: cache memory blocks in xarray to accelerate lookup

## source Changelog
* Synced latest Elixir 3.3 source

# v3.2 venus

## device/xiaomi/venus
* venus: overlay: Remove dsp. prefix from audio and video power profiles
* venus: Replace BTM_DEF_LOCAL_NAME with a sysprop

## device/xiaomi/sm8350-common
* sm8350-common: Drop media target variant property from system_ext.prop
* sm8350-common: gps: Revert oem changes 
* sm8350-common: Move Bluetooth power overlays to sysprops 
* sm8350-common: Enable zygote critical window 
* sm8350-common: Migrate to AIDL ClearKey DRM HAL 
* sm8350-common: Add a system property for System UI compiler filter. 
* sm8350-common: Preopt SystemUI for AOSP builds.
* sm8350-common: update wfd system blobs 
* sm8350-common: update DPM, IMS, and RIL system blobs
* Fix hot issues
