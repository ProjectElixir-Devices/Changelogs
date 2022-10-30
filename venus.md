![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for MI 11 (venus) Changelogs

```
Build type: Monthly
Device: Xiaomi 11 (venus)
Device maintainer: Flower Sea
Required firmware: build-in
```


### v3.2 venus

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
