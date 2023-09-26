![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for Google Pixel 3 XL (crosshatch) Changelogs

## v3.12 Crosshatch
- User Build
- Selinux is Enforcing
- CTS passes and banking apps working
- Update display vendor packages
- b1c1: drop android.hardware.tetheroffload.config manifest
- b1c1: Modify kgsl idle timer to 58ms 
- b1c1: overlay: Switch to AVC 3.1 for screen recording
- b1c1: overlay: Disable gms components for better WiFi speeds 
- b1c1: Optimize Launcher3 and Settings for speed
- b1c1: props: add smoother scrolling and better responsivenes
- b1c1: props: Disable sf EGL Image tracking
- b1c1: rro_overlays: Increase 5 GHz network signal tolerance
- b1c1: switch to Vulkan UI
- b1c1: vendor.prop: set HWUI Render to 20
- b1c1: wifi: Add parameters for Hotspot 2.0
- b1c1: wifi: Disable RX wakelock feature
- b1c1: wifi: Disable firmware log
- b1c1: wifi: Disable TDLS offchannel
- b1c1: wifi: Enable Optimized Power Management
- b1c1: wifi: Relax WiFi re-association RSSI threshold
- b1c1: wifi: Switch gEnablePowerSaveOffload to 5
- b1c1: wifi: smarter decisions on whether to use a 2- or 5Ghz AP
- revert: b1c1: Switch cpu variant to kryo 385
- Misc. Fixes and Improvements

## v3.10 Crosshatch
- User Build
- Selinux is Enforcing
- CTS passes and banking apps working
- Configure default light sensor type
- Add Google platform certificate
- Remove google_battery support
- Remove all permissions from /sys/devices/soc0/serial_number
- Restrict access to /sys/devices/soc0/serial_number
- dumpstate: Don't dump serial number

## v3.9 Crosshatch
- User Build
- Selinux is Enforcing
- CTS passes and banking apps working
- Enable AOSP Surfacefliger
- Enable BT low power adaptive
- Switch to AutoSingleLayer Android 13
- RIL powersaving for battery life and import more props
- Add enable usb data service
- Reclean CarrierSettings integration
- Try to restrict USB early in boot
- Rebase kernel lineage
- crosshatch: Adjust horizontal position of statusbar

## v3.8 Crosshatch
- Merged May Security Patch
- User Build
- Selinux is Enforcing
- CTS passes and banking apps working
- Fixed Now Playing
- Fixed Microphone when video call in Whatsapp,Telegram,etc.
- Update AiAi to S.10.playstore.pixel3.408937249 
- Switch back to HIDL 2.1 btAudio
- Improvements kernel lineage
- Prop: enable ro.hwui.render_ahead
- Misc. Fixes and Improvements

### v3.7 Crosshatch
- Initial official release
- User Build
- Selinux is Enforcing
- CTS passes and banking apps working

### Note:
- No need to flash gapps (included)