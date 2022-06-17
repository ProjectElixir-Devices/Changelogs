## 1.8 Juice

- Switch to OSS vendor ( CLEAN FLASH REQUIRED )
- Update blobs from miui_LIME_22.5.18_024e3361db_11.0
- Switch to Pixel Power HAL
- Import powerhint json from coral
- Tune powerhint json for our device
- Set max WFD resolution to 1080p
- Sync idle/touch timer to raven
- Sync durations props with redbull
- Enable IORap app launch prefetching

## 1.7 Juice

- Imported MIUI offline charging animation
- Fix deprecated power profile items
- msm_irqbalance: Correct the arch_mem_timer interrupt
- msm_irqbalance: Do not balance msm_drm and kgsl-3d0 IRQs
- Workaround device props based on SKU
- Add dalvik heap configuration for 4 & 6GB RAM
- Sync surfaceflinger offset with crosshatch
- Flatten APEXs for Performance
- Enable iorapd tracing with perfetto
- Decreased media volume steps
- Shipped with 4.19.241 Guuji kernel
- Compiled with AOSP clang 14.0.7

## 1.6 Juice

- Improved I/O read-write speed
- Set max frame buffer to 3
- Disable VSync for CPU rendered apps
- Enforce 24-bit audio for offload playback
- Tune ZRAM configuration
- Import sunfish cpusets configuration
- Import sunfish phase offset configuration
- Decrease media volume steps
- Fully use RRO overlays (override vendor ones)
- Reworked statusbar padding and cutout
- Kang LDAC blobs from courbet

## 1.5 Juice

- Switch to QTI BT
- Switch to user build
- Bringup XiaomiParts
- Fix for brightness flicker on some panels when turning off display
- Fix screenshot sound leakage while connected to bluetooth
- Enable some kernel side features
- Add blur support
- Shipped with 4.19.232 Juice-Bengal kernel
