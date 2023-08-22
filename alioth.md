![Device Changelog](https://i.imgur.com/C0Wcdr5.png)
<p align="center">
<b>Project Elixir for POCO F3 (alioth) Changelogs</b>
</p>
  
## v3.1 Alioth

- Add peak and min refresh rate switch
- Import Vibrator Effects firmware
- Display correct charging speed
- Disable notification led support
- Add missing dimens.xml to fix status bar padding
- Dynamic RR
- Disable notification led support
- Dolby and Dirac for audio
- Update vibration effects
- Use Emanuel powerhint
- Switch to SkiaGL Threaded
- Rework thermal

## v3.2 Alioth

- Update to last N0Kernel and build with Clang-16
- Add proper rounded corners config 
- Tweaks on sound and dolby
- Tweaks on powerhint
- Add "Turbo Charger" overlay

## v3.2 Alioth Hotfix

- Fix hotspot
- Disable QCOM system daemon
- Optimize package manager dexopt properties
- Optimise dex flags
- Rework Dolby / Prebuilts environment
- Enable the pre-rendering feature
- Import AOSPA Trees Power Profile
- Add missing dimens.xml to fix status bar padding
- Import Charging props
- Multiple audio tweaks

## v3.3 Alioth

- Props: add ro.audio.monitor props According to https://buildpropeditor.jrummyapps.com/system-properties.html, could fix audio direction not switching on rotation
- Audio Volumes: Update volumes from Google Pixel 7 Pro
- Powerhint: limited the dex2oat resouce when thermal stress
- Better RAM Management
- Enable suspend while charging 
- Configure SQLite to operate in MEMORY mode
- Make the UI smoother
- Use surfaceflinger props from cheetah
- Use HintManager for HWUI 
- Enable display async powermode 
- Compile HWUI for performance 
- Sync suspend properties from raven

## v3.4 Alioth

- Rework trees based on 13.0.8 EU blobs, thanks to johnmart19, voidui dev
- Added Leica camera thanks to darkphnx
- Nexus kernel by default thanks to NotZeetaa
- Increase volume speaker
- Added live display with sunlight mode and anti flickering
- And more

## v3.5 Alioth

- Rework trees based on 13.0.9 EU blobs, thanks to johnmart19, voidui dev
- Sync last Nexus kernel staging branch changes
- Nuked leica camera for the moment
- Enable SSR for all subsytem types
- Enable SSR for all subsytem types
- Imported miui CarrierConfig changes from munch V13.0.5.0.SLMMIX
- Set bluetooth.device.default_name to 'Poco F3'
- Enable suspend to RAM

## v3.8 Alioth
-Silenced some logspam
-Use HintManager for HWUI
-Add battery health support
-Set Poco F3 as default hotspot ssid
-Enable aosp surfaceslinger
-Updated thermal
-If leica cam buggy use gcam instead

Note: Default kernel is No kernel. Don't flash kernelSU supported kernels.

## v3.9 Alioth
Rebased Tree
- Updated Blobs 
- Added battery health support

Note:
cts passed by default
Leica cam there
Use 14.0.9 eea firmware
Rom comes with gapps.

## v3.10 Alioth
- Fixed some previous issues
- Fixed some denials
- Import some wifi configs and improved 5ghz signal tolerance
- Disabled hvdcp_opti deamon pps control
- Enable VoLTE/ViLTE/VoWiFi for entire 470 mcc (BD)
- Updated clear speaker audio

Note:
cts passed by default
Leica cam there
Use 14.0.9 eea firmware
Rom comes with gapps

## v3.11 Alioth
- Fixed the issue where audio volume goes low and High
- If you face Delay in FP, switch to NoKernel
- Disabled SDM rotator downscaler
- Enabled Optimized Power Management
- Droped slim_daemon

Note:
cts passed by default
Leica cam there
Flash kernel su supported kernel to use kernelsu
Use 14.0.9 eea firmware
Rom comes with gapps
