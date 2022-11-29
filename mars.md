![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for MI 11 Pro (mars) Changelogs

```
Build type: Monthly
Device: Xiaomi 11 Pro (mars)
Device maintainer: Flower Sea
```

# v3.3 mars
## device/xiaomi/sm8350-common
* sm8350-common: rootdir: Remove discard command tuning
* sm8350-common: Remove odex/oat files from pinner list

## device/xiaomi/mars
* mars: Don't sign Wifi RROs with platform cert 
* mars: Set default hotspot ssid

## kernel/xiaomi/mars
* Flower kernel v2.10
* Merged the CLO tag "LA.UM.9.14.r1-20800-LAHAINA.QSSI13.0"
* Kernel version: 5.4.197 -> 5.4.210
* net: wireguard: Update to version 1.0.20220627
* cert host tools: Stop complaining about deprecated OpenSSL functions 
* qcacld-3.0: Add time slice duty cycle in wifi_interface_info 
* qcacmn: Add time slice duty cycle attribute into QCA vendor command 
* media: meson: vdec: fix possible refcount leak in vdec_probe() 
* qcacmn: Disable all of qdf_trace when WLAN_DEBUG is disabled 
* qcacld: disable DFS on AP mode
* mars_defconfig: Disable stack frame size warning
* drm/msm/sde: Don't read and clear VBIF errors upon commit 
* drm/msm/sde: Compile out sde debug if DEBUG_FS disabled 
* gpu: drm: Use power efficient workingqueues 
* drm/msm/sde: Skip heavy autorefresh checks when it's not enabled 
* msm/dsi: free phy_timing_val if it's not used anymore 
* qca-wifi-host-cmn: Fix unused function/variable warnings 
* qcacld-3.0: Disable debugging bloat as much as possible 
* cnss2: discard non-critical logs 
* net/bluetooth: Queue delayed work on power efficient wq 
* techpack/dataipa: Conditionally enable ipa wakelocks 
* techpack/dataipa: Run delayed work on power efficient workqueues 
* drivers/qca-wifi-host-cmn: Run delayed work on power efficient wq 
* mars_defconfig: Disable NL80211_TESMODE
* ipa: Allocate page with __GFP_RETRY_MAYFAIL and __GFP_NOWARN 
* msm: ipa3: Fix non-atomic read on atomic_t variable 
* GKI: wireless: allow disabling NL80211_TESTMODE 
* sock: remove one redundant SKB_FRAG_PAGE_ORDER macro 
* zram: do not waste zram_table_entry flags bits 
* ANDROID: binder: retry security_secid_to_secctx()
* FROMGIT: Binder: add TF_UPDATE_TXN to replace outdated txn
* NDROID: Configure out the macros in android_kabi and android_vendor 
* drivers/base/memory.c: cache memory blocks in xarray to accelerate lookup

## source Changelog
* Synced latest Elixir 3.3 source

# v3.2 mars

## device/xiaomi/mars
* mars: overlay: Remove dsp. prefix from audio and video power profiles
* mars: Replace BTM_DEF_LOCAL_NAME with a sysprop

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