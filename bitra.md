![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for Realme GT Neo 2 (5G)  Changelogs

### v3.6 bitra - Realme GT Neo 2
- Bumped to Project Elixir v3.6.
- Fix ripple animation lag.
- Divide IRQ affinity correctly.
- Adjust FOD sensor position values.
- Add missing sensor for UDFPS AOD.
- Enable option for full screen aspect ratio.
- Removed GcamGo (Aperture cam is good enough).
- Import some audio/bt configs from stock.
- Fixed "dc dimming" button getting turned off even if it's enabled.
- Add Livedisplay 2.1 support (thanks to @cristianvaz).

### v3.5 bitra - Realme GT Neo 2
- Bumped to Project Elixir v3.5.
- Updated to Redfin January FP.
- Removed smart charging and battery health.
- Change perms to hide Magisk in banking apps.
- Enable USB debugging on boot.
- Fixed brightness level mapping.
- Update Audio configs from C.10.
- Update blobs to RMX3370_11.C.10.

### v3.4 bitra - Realme GT Neo 2                                    
- Bumped to Project Elixir v3.4.
- Updated to Redfin December FP.
- Switch to OSS dtbo.
- Introduce Oplus Vibrator.
- Introduce smooth_level and sensitive_level for touchpanel.
- Added some audio rotation props.
- Tweaked Vibration, Auto brightness and Livedisplay.
- Imported Display Eye Protection Data from stock.
- Fix brightness mapping + add new autobrightness config.
- Update WCNSS and power profile configs.
- Update blobs to RMX3370_11.C.10.

### v3.3 bitra - Realme GT Neo 2

- Bumped to Project Elixir v3.3.
- Updated to RedfiNovember FP.
- Switched to user build.
- Fixed SuperDart Charging text.
- Fixed ScreenOff FOD.
- Imported OOS 11 Dolby (thanks to @revolwoc)
- Decrease launch boost to 3sec.
- Removed Battery and Notification LED option.
- Add Dragon Ball Edition fastchg firmware and support into libinit.
- Misc powerhint improvements.
- Update blobs to RMX3370_11.C.09.

### v3.2 bitra - Realme GT Neo 2

- Bumped to Project Elixir v3.2.
- Updated to Redfin October FP.
- Update blobs to RMX3370_11.C.09.
- Place volume panel on the left by default.
- Fixed cpu_dma_latency value.
- Fixed lockscreen charging info of mA & watts.
- Modify kgsl idle timer to 58ms.
- Reserved some space on system, system_ext, product partitions.
- Switched to AOSP NXP NFC HAL.

### v3.1 bitra - Realme GT Neo 2

- Bumped to Project Elixir v3.1.
- Updated to Redfin September FP.
- Fixed top speaker crackling & mic issue (thanks to Elias).
- Switch to prebuilt audio hal and stock audio volume curve.
- Tuned statusbar padding to match with stock. 
- Updated blobs to RMX3370_11.C.08
- Add aptX blobs from raven.
- Add oplusSensor hal.
- Cleanup kernel from oplus bloats.
- Don't allow aux cam usage for Telegram / Telegram X.
- Don't mount tracefs twice and debugfs.
- Don't pin launcher in device memory.
- Improve recording microphone volume.


### v3.0 bitra - Realme GT Neo 2

- Initial A13 beta build.
- Selinux is Enforcing.
- Bumped to Project Elixir v3.0.
- Updated to Redfin August FP.
- CTS passes by default now.
- Added OPlusExtras.

### Credits: 
- [Elias](https://t.me/TheMalachite) for initial trees.
- [Anierin Bliss](https://t.me/Anierin_Bliss) for OPlusExtras.
