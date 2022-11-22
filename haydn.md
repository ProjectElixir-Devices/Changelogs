![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for Redmi K40 Pro/Pro+/Mi 11X Pro/11i (haydn) Changelogs

### v3.0 haydn

- Initial OFFICIAL Build
- Nuked Miuicam
- Switched to Aosp BT
- Audio Hal 7.0
- Added per app refresh rate
- Power optimisation profiles
- Switched DRM to aidl
- Gapps shipped with ROM
- CTS passes by default


### v3.1 haydn

- Added Gcam
- Hotspot Fixed
- Fixed random lags
- Fixed ideal drain issue caused by ril
- Fixed NFC & Primary (main) camera issue for Global users
- Fixed some sepolicy stuff related to surfaceflinger
- Under the hood changes

### v3.2 haydn

- October Patch
- Tweaked thermals to unlock 2.8Ghz on prime cores (Expect some heating)
- Added Moto Dolby
- Under the hood changes

### v3.3 haydn

- Switch to vendor-defined color modes 
- Migrate vendor.camera.aux.packagelist to overlay 
- Sepolicy: Fix faceunlock denial
- Remove references to a2dp module 
- Statusbar and corner config from aospa/alioth 
- Create IMS symlinks
- Nfc: Fix Mifare Classic reading
- Nfc: Tone down debugging
- Pin ImsRcsService form cupid-user-13
- Set bt name via init on basis of marketname
- Lower sf idle timer 
- Relax timers for automatic refresh rate switching 
- Configure RefreshRate brightness thresholds
- Sync brightness overlays with miui
- Fix Mifare Classic readings
- Add temp divider value for cpu info overlay
- Switch to AutoSingleLayer Android 13 Setting 
- Remove non-existent packages
- Switch to SkiaGL Threaded
- Build more drm vendor hal

### Credits: A very special thanks to Grewal for trees, Akshay for bringup, Saurav and Elixir team, & Einsel for testing.  

