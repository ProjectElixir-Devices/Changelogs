![Device Changelog](https://i.imgur.com/vDxXjpT.png)

### Project Elixir for POCO F2 Pro (lmi) Changelogs

### v3.8 POCO F2 Pro (lmi)

- Update blobs from V14.0.4.0.SJKCNXM
- rootdir: Enable ufs powersaving after boot
- overlay: disable proximity usage during doze
- overlay: Update deprecated powerprofile item
- Build vendor.display.config@1.9
- Kang vendor.qti.hardware.camera.postproc@1.0-service-impl.so from LAHAINA
- props: Enable ro.hwui.render_ahead
- props: Disable sf EGL image tracking
- overlay: Allow automatic adjusting of the screen brightness while dozing in low power state
- props: Disable debug.sf.latch_unsignaled
- props: Import more surface flinger flags
- Enable AOSP surfaceflinger
- props: Enable apk fs-verity
- remove KProfiles support
- Build some missing LDAC libs
- props: Properly disable phantom process killing
- init: Do not allow restricted tasks to run on big cores
- overlay: Switch to AVC 3.1 for screen recording
- Remove max ZRAM compression streams setting
- powerhint: Add some CPU frequencies for power saving
- powerhint: Set to powersave governor when device is idle
- powerhint: Set screen-off schedutil ratelimits
- powerhint: set /dev/cpu_dma_latency value in hex

### Important Note
- This update maybe needs clean flash
