![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for Google Pixel 2 XL (taimen) Changelogs

### v3.11
- August security patch
- Correct the slot ID of non-removable ESIM
- Dumpstate: Don't dump serial number
- Ueventd: Remove all permissions from /sys/devices/soc0/serial_number
- Sepolicy: Restrict access to /sys/devices/soc0/serial_number
- Build GcamMod 8.4

### v3.9
- May security patch
- Enable AOSP surfaceflinger
- Switch to AutoSingleLayer Android 13 Setting
- Enable ro.hwui.render_ahead
- Lower gps debug level
- Drop Google Camera
- Fixed live captions

### v3.8
Device Changelog:
- May security path
- Flatten APEXs for performance
- Disable battery healt
- Misc improvements

### v3.7
- Aril security path
- Drop kernel-su
- Remove aptX blobs
- Drop GoogleCamera
- Misc

Bug:
- Wifi display
- GoogleCamera crash
- Live caption

### v3.6
- Feb security path
- Increase rounded corner radius adjustment (This fixes the top corner radius on the lockscreen)
- Bring back GoogleCamera
- Switch to lineage kernel
- Implement kernelsu
- Update multiple vibration strength levels overlay for 13
- Disable use buffer age to workaround driver issue (Fixed lag issue)
- Drop xz ramdisk

Note v3.6:
- Do not update google camera (will fix in the next relese)
- Clean flash required (Since switch to lineage kernel, need clean flash)
- Ship with kernelsu or root acces (Need install kernelsu.apk to activated)

### v3.5
- Initial Official Relese Project Elixir
- Crash in Essence menu (Lock Screen) fixed