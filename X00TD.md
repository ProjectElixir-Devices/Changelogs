## v2.0 X00T/D
```
- Reverted FP to stock A10
- Camera: Imported FOSS camera hals
- Camera: Upstreamed camera blobs from LA.UM.9.2.r1-03600-SDMxx0.0
- Camera: Disabled lib2d rotation
- Camera: Link to libhidltransport instead of android.hidl.base
- Disabled triple buffering
- Disabled slow blur effect to avoid laggish blur effect
- Fixed camera lags
- Dropped all SF offset related props
- Fixed Google Camera crashes issue
- Switched to SkiaGL threaded
- Updated some GPS changes from LA.UM.9.1.r1-11200-SMxxx0.0
- Changed default GPU idle timeout to 60ms
- Disabled SF client composition cache
- Removed duplicated triple frame buffer prop
- Updated surfaceflinger props from CAF
- CTS passed by default
- Some misc improvements and fixes
- ROM is NON-FBE & LV build
```


## v1.9 X00T/D

```
- Updated FP to Raven july
- Props: Enable skia reduceOpsTaskSplitting
- Props: Disable unsignaled prop
- Rootdir: Boost performance during bootup
- Ships with ANX Camera by default
- Properties: Disable debug.sf.enable_hwc_vds
- Cleaned up dead build packages
- Configured cpusets for dex2oat
- Updated dexpreopt configuration
- Tuned dalvik heapminfree for devices with 3gb ram
- Debloated some google apps
- Updated blobs from LA.UM.9.2.r1-03500-SDMxx0.0
- CTS passed by default
- Some misc improvements and fixes
- ROM is NON-FBE & LV build
```


## v1.8 X00T/D

```
- Updated FP to Raven june
- Enabling 24 bit profile for audio capture
- Kang sensors.ssc from Nokia PL2
- Build graphics.allocator @3.0 and @4.0
- Audio: Increase earpiece volume for calling
- Added OpenGL ES and update Vulkan dEQP feature flags
- Re-enabled some audio features
- Refactored all audio props
- CTS passed by default
- Some misc improvements and fixes
- ROM is NON-FBE & LV build
```


## v1.7 X00T/D

```
- Updated FP to Raven May
- Hide Magisk better for Banking Apps
- Disabled ART debug and optimize dexpreopt 
- Dropped soundtrigger HAL
- Updated Graphics blobs from LA.UM.8.2.r1-07400-sdm660.0
- Improved performance
- LV and Non FBE build
- Use latest Orfox recovery
- Some misc improvements and fixes
- CTS passed by default
```

## v1.6 X00T/D

```
- Updated FP to Raven April
- Dropped userspace LMKD
- Rollbacks to stock charger blob
- Updated SurfaceFlinger pin on all targets
- Some misc improvements and changes
- Fixed App Data usage stats & upload speed indicator
- Audio: allocate dedicated pcm node for in call recording
- Audio: Use qcom implementation for sw effects
- Audio: Add new flag name to compress offload case
- Updated Graphics EGL blobs from taimen
- rootdir: Create a cpuset for camera-specific processes
- rootdir: Remove CPUBW min freq setting
- Switched from Schedtune to UClamp
- Switch back to Vulkan rendering
- LV and Non FBE build
- Use latest Orfox recovery
- Some misc improvements and fixes
```

## v1.5 X00T/D

```
- Used speed tuning for performance critical applications
- Added memory optimizations
- Disabled camera perflock
- Audio: Removed surround recording support from audio policy config xml
- Audio: Added built-in/Back mic and remove TelePhony Rx from primary input
- Updated media codecs from LA.UM.9.2.r1-03700-SDMxx0.0
- Nuked Zenparts
- Added touchscreen gestures HIDL HAL
- Fixed sepolicy denials
- Switched to Vulkan UI renderer
- Using upstreamed 4.4.302 kernel
- LV and Non FBE build
- Use latest Orfox recovery
- Some misc improvements and changes
```

## v1.3 X00T/D

```
- Jan ASB build
- Switched to AOSP WFD
- Cleanedup unused blobs
- Added ZenPartsV2
- Fixed VoLte issues
- Fixed screen cast
- Fixed WFD lags
- Fixed all Network issues
- SELinux status is Enforcing
- SafetyNet passes by default
- Using upstreamed 4.4.299 kernel
- LV and Non FBE build
- Use latest Orfox recovery
- Some misc improvements
```

## v1.2 X00T/D

```
- Updated audio, media blobs from LA.UM.9.2.r1-03500-SDMxx0.0
- Updated thermal blobs from LA.UM.9.2.r1-03500-SDMxx0.0
- SELinux status is Enforcing
- SafetyNet passes by default
- Using 4.4 kernel
```