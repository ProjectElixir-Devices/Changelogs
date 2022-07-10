## 1.2 Alioth

- Switch to optimus drunk kernel
- Improved Ram mangement
- Added adaptive Charging 
- Updated alioth PowerHint
- Fix hardware denial 
- Advertise fingerprint on power button
- Enable vibration multiple intensities 
- Many more underhood stuff

## 1.3 Alioth
- Switched To Nextkernel CAF
- Cleanup Early_boot script
- Enable 50% Zram Size
- Enable Zram Optimizations
- Apply latest Kryo 785 & 385 Optmiziations 
- Added GCamGo
- Inclued Firmware V12.5.5.0.RKHMIXM

## 1.4 Alioth
- Switched to n0kernel By Emanuel
- Updated PowerHint and msm-irqbalance Thanks to Emanuel 
- Switch to vulkan ui Renderer 
- Optimized ART build flags  
- Switched to Proton Clang for kernel compile  
- Remove FM Tuner From Audio Input Devices 
- Enable Audio Fluence for Voicerec 
- set persist.sys.sf.color_mode to 9 instead to 12 
- Enabled LimitedAlpha and FadingMarquee for have UI more Smooth.

## 1.5 Alioth
- Switch to QTI BT 
- Full cleanup and rework imported blobs from Miui 13.0.3.0 and 23.02.2022
- Use HintManager for HWUI
- Build more libstagefright packages
- Introduced Battery Friendly PocketMode 
- Updated GcamGo To 2.5 Greatness Special
- Major Fixes on NextKernel 
- Fixed Ok Google not working on display off
- Fixed issue with Third Party Screen Recording Apps
- Added increase touch response

## 1.6 Alioth
- Switched Again to N0kernel
- Removed GcamGo for some issue and let users decide the cam
- Disable Async MTE on system server
- Removed IO read_ahead_kb tune 
- Set readahed_size_kb to system,data,vendor,product,system_ext to avoid memory pressure
- Updated Adreno Graphics Blobs to v@615_v2 
- Fixed Some Issues with drivers Vulkan
- Disable unspecialized app process pool 

## 1.7 Alioth
- parts: Bump target SDK version to 30 
- Remove no-op TARGET_KERNEL_ARCH flag
- Rootdir: Override imsdatadaemon
- Fix Some sepolicy denials
- Fix High Jitter issue
- Re-Enable Zygote Preforking
- Switch to AOSP WFD
- Set max fling ticks per sec to 24
- Don't send interaction hint for unnecessary events 
- Default to 0 compression ratio
- use Cloudflare DNS as the default fallback
- limit direct share targets to reduce lag 

## 1.8 Alioth
- Fixed Crashing apps
- Fixed Video Calling
- Cleanup early_boot script
- Enable NR by default on both slots
- Dexpreopt SystemUI for speed 
- Updated Adrano Graphics Blobs to v@0615_v3
- Remove gc_urgent from powerhint *it is handle by N0kernel*

## 1.9 Alioth
- Initial build
- Switch to dora clang
- Switch to Immensity kernel
