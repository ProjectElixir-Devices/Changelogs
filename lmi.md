![Changelog](https://i.imgur.com/SDKuqap.png)

### Project Elixir for POCO F2 Pro (lmi) Changelogs

### v3.10 POCO F2 Pro (lmi)

- overlay: Switch to AVC 3.1 for screen recording
- overlay: adjust screen brightness settings values
- ADPF: support sending power hint
- ADPF: send ADPF_FIRST_FRAME hint
- Import micharge blobs
- Update Hotword Enrollment blobs from CMI V14.0.3.0.TJAEUXM
- vibrator: Import qti vibrator effect
- Bump light aidl to v2
- init: Allow all filesystems for USB-OTG
- introduce fastcharge HIDL
- overlay: Increase 5 GHz network signal tolerance
- sepolicy: update batterysecret rules
- sepolicy: label more power supply nodes
- sepolicy: label more wakeup nodes
- Enable AOSP surfaceflinger
- Add MIUI Camera
- Modify kgsl idle timer to 58ms
- powerhint: Set to powersave governor when device is idle
- powerhint: Set screen-off schedutil ratelimits
- init: Do not allow restricted tasks to run on big cores
- init: Drop input boost
- init: Configure schedutil up/down rate limit
- init: Lower down rate limit for prime CPU
- wifi: Enable Optimized Power Management

### Important Note
- Can dirty from v3.9 release
- Need clean flash from v3.8 and earlier
