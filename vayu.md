![Elixir Banner](https://i.imgur.com/C0Wcdr5.png)

# Project Elixir v3.10
 - Upstream kernel to Linux v4.14.320 
 - Optimize audio codec 
 - Drop unused props and configs 
 - Revert back to proprietary perf 
 - Add CIT sensor service for better adaptive brightness 
 - Update blobs from MIUI 14.0.3.0 Global 
 - Patch IMS APK from MIUI 14.0.3.0 Global 

# Project Elixir v3.7
 - Switch Kernel (Kyrielight-KATO as base)
 - Upstream kernel to v4.14.312
 - Fix NFC
 - Ship MIUI 12.0.4.0 (India) firmware with the ROM package
 - Add some surfaceflinger props to reduce lags | QS lags are still there, no working fix  - found yet
 - Fix nightlight (reduced the redness of the default nightlight implementation)
 - Enable blurs (its subtle)
 - Switch to Kyrelight Kernel
 - Build Boost Framework
 - Improve status bar time and keygaurd network label positon consistency
 - Drop aptX(HD) encoder libs (depricated)
 - Drop saturated color profile in settings (It uses native color profile and it's not  - supposed to be used)
 - Enable suspend to RAM (Improves idle drain considerably.)
 - Allow GPU boosting on performance mode
 - Enable oem fast charge (Fast charging capabilites gets detected better than in generic  - impl.)
 - Enable background ART heap compaction for cached apps (Better RAM management.)
 - surface flinger: Force triple frame buffers (Reduces jitter without impacting latency.)
 - Improve kernel compilation

# Project Elixir v3.6

 - Remove depricated entries from Audio Configs
 - Update carrier config from LA.QSSI.13.0.r1-07400-qssi.0 and MIUI 13.0.5.0

# Project Elixir v3.5

 - Drop IO prefetcher
 - Drop QTI Perfd
 - Migrate from QTI to Xiaomi power HAL
 - Update default bluetooth name from model number to product name
 - Enable Zygote critical window
 - Add magisk hide props, banking apps that did not work before and recognized  - Magisk being installed now don't recognize that and work just fine
 - Updated blobs from miui_VAYUGlobal_V13.0.5.0.SJUMIXM
 - Included some smoothness tweaks

---

# Project Elixir v3.2

 - Update audio HAL to 7.1 and add some audio tweaks
 - Update surface flinger props and other smoothness tweaks
 - Switch to SkiaGL Threaded render engine
 - Import Brightness overlays from MIUI
 - Improve haptic and vibe patterns
 - Enable configurable haptic strengths
 - Import powerhint.json and power profile from coral (\*adapt for vayu)
 - Drop IORAP prefetching [DEPRECATED in Android 13 and above]
 - Drop liba2dpoffload target [source built is UNSUPPORTED in Android 13]
 - Unpin render script binaries [DEPRECATED on Android 12 and above]
 - Enable dex2oat64 to do dexopt
 - Disable vsync for CPU rendered Apps
 - Force disable low ram config [our device is having 6/8+ GB ram, so it's not low ram conditions]
 - Improve video calling
 - Tune Adaptive Suspend parameters

---

# Project Elixir v3.1

 - Rebased to Arrow OS device trees
 - Switch to Mochi kernel
 - Forward port G Cam MOD by BSG 8.1
 - Dropped Dolby

---

# Project Elixir v3.0

 - Migrate to AOSP Bluetooth stack (until QTI one is updated)
 - Improve camera shim
 - Unpin updatable-media from memory

### Notes

```
Removed Modded Pixel Launcher until stable release from Team Files
Dolby is shipped and works
Mi Parts (Device Specific Settings) is shipped and works
```
