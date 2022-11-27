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
