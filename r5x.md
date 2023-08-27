![Device Changelog](https://i.imgur.com/C0Wcdr5.png)
### Project Elixir for Realme 5 Series (r5x) Changelogs

### v3.11 (HOTFIX) Realme 5 Series (r5x)
- Switched to Aidl Power Libperfmgr
- Dropped some useless camera blobs And stock camera Config
- RealmeParts: extend sound_control to realmeparts
- RealmeParts: Implement Clear Speaker
- Added Prebuilt Aperture Camera
- Fixed Freezing issues
- Misc. Fixes and Improvements

### v3.11 Realme 5 Series (r5x)
- Update Perf Blobs from LA.UM.9.11.r1-04500-NICOBAR.0
- Enabled 4K Video Recording on Back Camera
- Added Viper4Android
- Update Cutout Values from stock
- Use proper device model as device name
- Enabled config.low_ram for 3GB variants
- RealmeParts Drop Ambient Display And Gesture

### v3.10 Realme 5 Series (r5x)
- Increased ZRAM size to 60% of Ram size
- Dropped Lineage LiveDisplay And Power
- Removed max ZRAM compression streams setting
- Enabled VoLTE and VoWIFI for all
- Fixed the Screen Lag during Screen Recording
- Removed deprecated bluetooth values from power_profile.xml
- Updated adreno drivers from LAHAINA 21000
- Updated Adsp,Adsp Module,Alarm,Cdsp,Certificate Authority,Charger,Cne,Drm,Display,Gps,Listen,Media,Postprocessing,Time-services,Tui Blobs from LA.UM.9.11.r1-04500-NICOBAR.0
- Removed deprecated aptX(HD) encoder shared libs
- fully Fixed Wfd
- Correct SoC manufacturer name Qualcomm to Qti
- Upstreamed Kernel to latest v4.14.320

### v3.9 Realme 5 Series (r5x)
- Switched to retrofit dynamic partition
- Fixed all Camera related issues 
- Enable aptX(HD) offload
- props: Disable sf EGL image tracking
- Enable & pin msm_irqbalance to system-background
- Enable BT low power adaptive control feature
- media: Add attribute name for SW encoder
- Remove dynamic attributes from APS config
- Set valid output channel mask for earpiece
- media: Tune perf xml based on measured fps
- Remove the RenderScript HAL from the vendor manifest

### v3.8  Realme 5 Series (r5x)
- Enabled LTE_CA workaround
- overlay: Set LTE+ threshold bandwidth to 0
- Dropped deprecated/unneeded MAX_EGL_CACHE flags
- Dropped GL comp backpressure prop
- Adjust lmkd kill timeout
- Added filecache_min_kb tuning for lmkd
- props: Switch to AutoSingleLayer Android 13 Setting
- Enabled R8 optimizations for SystemUI & system_server
- prop: Dropped ro.hwui.render_ahead
- Misc. Fixes and Improvements


### v3.7  Realme 5 Series (r5x)
- Fixed Random Reboot
- Fixed Cpu Frequency Mismatch
- Fixed Electronic image stabilization (EIS)
- Dropped dex optimization and preopt flags/props 
- Removed flag not applicable to the target devices
- Disabled useless LMKD stats logging
- Removed deprecated TARGET_BOARD_PLATFORM_GPU
- Build required HIDL libs to vendor
- overlay: Set config_use16BitTaskSnapshotPixelFormat to true
- Optimize native executables for Cortex-A76 CPU
- Added realme_trinket to assert
- Used qcom baseband strings intead of realme baseband
- Removed deprecated TARGET_ENABLE_MEDIADRM_64
- Compile HWUI for performance
- Force disable iorapd (eat more RAM and slowdown device)
- Increased SF durations
- Enabled ro.hwui.render_ahead and set it to 20 frames
- prop: Disable ZSL mode correctly
- Misc. Fixes and Improvements


### v3.6  Realme 5 Series (r5x)
- Removed nonexistent hw_recovery nodes
- Removed nonexistent block device readahead config
- Removed swap configuration
- Disabled dalvik minidebuginfo generation
- Removed unused contexthub overriding service definition
- power: Implement extension for kernelspace battery saver
- Added Missing Gps Hal libs
- Addressed Wakeup nodes
- props: Optimize ART
- Optimize everything on preopt
- Added Some hwui props from stock RUI 2.0
- Added RealmeParts
- Massive Cleanup on Device Tree
- Rearranged all Overlay to rro_Overlay
- audio: Increase Headset and In-Built Mic Voulme Also Fixed noise issue
- RealmeParts: Address Vibrator Denials
- RealmeParts: Drop Notification and Call Vibration strength control
- Misc. Fixes and Improvements


### v3.5  Realme 5 Series (r5x)
- Force HAL1 on social apps
- Added Missing display config file
- Fixed 5i prebuilt Fingerprint
- Adressed some Denial
- Added Prop HintManager for HWUI
- Misc. Fixes and Improvements


### v3.4 Realme 5 Series (r5x)
- Added Aperture Camera And Enabled Aux
- Disable sched_conservative_pl Boosting
- Addressed Some Hardware Denials
- Fixed Offline Charging On all device (5/5i/5s/5NFC)
- Imported Dolby Atmos from OnePlus 9R
- Fixed Screen Cast 
- Added Config Inherit several Android Go configurations
- Enabled DEXPREOPT_SPEED_APPS
- Disabled per_app_memcg
- Enabled zygote critical window
- Misc. Fixes and Improvements


### v3.3 Realme 5 Series (r5x)
- Enabled Force Encryption
- Configured dext2oat pre-optimization
- Dropped Prebuilt GcamGo
- Update telephony blobs from LA.QSSI.12.0.r1-06500
- Force Disabled Vilte ! (Cause Call Cut Issue on Volte)
- Added Overlay To Allow more cached apps in the background
- Switch to AVC 3.1 for screen recording
- Dropped Adreno Stack (Cause Some Graphics Issue On Chrome/Play Store)
- Extend buffer size to 256kb for offload playback
- Enabled config_avoidGfxAccel (reduces RAM usage and gives better smoothness in the UI)
- Inlined ThunderBolt⚡ Kernel
- Misc. Fixes and Improvements


### v3.2 Realme 5 Series (r5x)
- Initial Android13 
- DECRYPTED
- Added SGcamGo Version 455
- Updated ADSP,BLUETOOTH,DSP,GRAPHICS Blobs
- And Much More Changes Here and There


Note:
- Clean Flash And Format Data Mandatory  If Coming From Other ROM

Thanks
@BabluS for Device 🎄
@IrawansAlt for Kernel 🎄

