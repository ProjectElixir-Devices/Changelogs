![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Project Elixir for Redmi Note 7 Pro (violet) Changelogs

### v3.7 violet
```
- Remove aptX(HD) encoder shared libs (Encoder shared libraries are no longer required as of Android 13 QPR2)
- Redefined bluetooth a2dp offload capabilities (Dropped unsupported aptx codecs)
- Enabled enable hwui render ahead
- Corrected routing order for voip output
- Added primary input sources for voip_tx
- Switched to stock acdb loader libs
- Enabled carrier aggregation workaround (Tnx to @DarkJoker360)
- Removed duplicated prop definitions
- Removed dsp. prefix from audio and video power profiles
- Removed dynamic attributes from APS config 
- Fixed deprecated power profile items
- Updated system blobs from LA.QSSI.13.0.r1-09400.01-qssi.0 
- Updated Carrier Config from LA.QSSI.13.0.r1-08600-qssi.0
- Update vendor blobs from LA.UM.9.1.r1-12900-SMxxx0.0
- Dropped Neural Network stack
- Fixed voip echo & mic issues (Tested and confirmed myself)
```

### v3.6 violet
```
- Removed broken slow motion support
- Enabled movie effects
- Enabled sticker avatars
- Enabled document mode
- Enabled panorama direction switch
- Enabled pro video mode
- Enabled advanced pro mode features
- Added two channels for echo referece (Another attempt to fix echo on calls when in speaker for the receiver)
- Disabled protected buffers support (AOSP WFD doesn't support protected Wi-Fi Display buffers)
- Enabled world phone bool (Allows changes regarding network operations to users)
- Injected custom doze settings into lockscreen settings
- Updated blobs to LA.UM.9.1.r1-11500.02-SMxxx0.QSSI12.0
```

### v3.5 violet
```
- Included stable MiuiCamera as default camera
- Improved charging speed
- Updated radio to v1.5 (Sim enable/disable option is unlocked now)
- Full base tree and cleanup
- Misc changes and fixes
```

### v3.4 violet
```
- Switched back to Xcalibur️ kernel
- violet: parts: Adapt to A13 QPR-1
- Build Aperture Cam app
- violet: overlay: Compact cached app heaps in the background 
- violet: Compile HWUI for performance 
- violet: Enable use of dedicated device for voip
- Misc changes and fixes 
```

### v3.3 violet
```
- Switched to prebuilt Azure kernel
- Increased In-call earpiece volume
- Cleaned up some death targets & adapted existing props to Android 13
- Misc changes and fixes 
```

### v3.2 Violet
```
- violet: Migrate to AIDL ClearKey DRM HAL
- violet: Enable zygote critical window
- violet: Add apk/jar/vintf fragments to PRODUCT_PACKAGES
- violet: Update system blobs from LA.QSSI.13.0.r1-05500-qssi.0
- violet: Drop trusted user interface
- violet: Enable vibration intensity levels
- violet: Update adreno stack from LA.UM.9.14.r1-20200-LAHAINA.QSSI13.0
- violet: Checkout CarrierConfig to LA.QSSI.13.0.r1-05500-qssi.0
- violet: Checkout CarrierConfig to LA.QSSI.12.0.r1-05800.01-qssi.0 
- violet: overlay: Migrate rounded corner content padding 
- violet: Update system blobs from LA.QSSI.13.0.r1-05800-qssi.0
- violet: overlay: Remove BT related configs
- violet: Move Bluetooth power overlays to sysprops
- Misc changes and fixes
```

### v3.1 Violet
```
- violet: Switch to metadata FBE
- violet: sepolicy: Address init denial
- violet: Don't build FM for now
- violet: Switch back to AOSP bluetooth stack
- violet: Disable LE audio related profiles 
- violet: Switch BtAudio to AIDL
- violet: Revert back to old media codecs 
- violet: Update adreno stack from from LA.UM.9.14.r1-19300.01-LAHAINA.…
- violet: Checkout media config files to LA.UM.9.1.r1-11500.02-SMxxx0.Q… 
- violet: audio: Increase In-call earpiece volume
- violet: rootdir: Add Offline Charging LED Indicator 
- Misc changes and fixes
```

### v3.0 Violet
```
- Initial release
- Selinux is Enforcing
- Build is encrypted
- CTS passes and banking apps working
- No need to flash firmware or gapps (included)
```

### Credits: A very special thanks to Nipin 
