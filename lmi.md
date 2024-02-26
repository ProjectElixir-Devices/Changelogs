![Changelog](https://i.imgur.com/MsgqFFz.png)

### Project Elixir for POCO F2 Pro (lmi) Changelogs

### v4.0

```
- Initial A14 buid
- Initial Official A14 build
- Switch to Wifi service AIDL
- import libprotobuf from munch V14.0.5.0.TLMCNXM
- inherit updatable_apex
- Switch to AIDL NXP NFC
- Build android.hardware.nfc@1.2 service
- enable AIDL DRM HALs
- Enforce fstab suffix to qcom
- Set androidboot.init_fatal_reboot_target=recovery
- Build legacy android.frameworks.sensorservice@1.0
- build vendor.display.config@1.9
- sepolicy: allow perf hal to access audio hal process
- sepolicy: allow perf hal to access fingerprint hal process
- sepolicy: label audio wakeup node
- sepolicy: Allow system_app to read /proc/pagetypeinfo
- sepolicy: Add camera label's
- Use speed tuning for performance critical applications
- props: RIL edits for battery life
- init: rm package cache on early boot
- init: Remove useless sensingdaemon, ptt_socket_app, ssgqmigd, qvop-daemon
- init: Remove useless qseeproxydaemon, esepmdaemon
- init: Remove redundant CHRE daemon
- init: Set default Wi-Fi country code to '00'
- revert props: Import more surface flinger flags
- props: disable Skia tracing by default
- props: Clean up useless log spams
- props: Enable config_avoidGfxAccel
- overlay: drop duplicate available Color Modes config
- overlay: do not show Smooth Display setting
- sepolicy: Allow system apps to get SettingsLib prop
- overlay: Disable gms components for better WiFi speeds
- overlay: move udfps enroll radius to settings
- sepolicy: update battery supply wakeup nodes
- wifi: tune bmps listening interval
- Speed profile services and wifi-service to reduce RAM and storage
- Update daxService to a14 from Sony pdx234
- DaxUI: Recompile to API 34
- Link dolby blobs against v33 libstagefright_foundation
- dolby: Add mediacodecs support
- dolby: Drop AC4 codec support
- Setup SecureNFC for Redmi K30 Pro / Zoom Edition / POCO F2 Pro
- Support MultiGen LRU
- Update graphics blobs from LA.UM.9.12.r1-14400-SMxx50.0
- Update adreno blobs from OnePlus 12
```

<br>

> [!Important]
> **Credits: A very special thanks to Project Elixir & TEAM**
> * **Donate**: [Do consider donating or buying us a coffee](https://projectelixiros.com/donate)
> * Android 14 Recovery Link : [Tap here for link](https://projectelixiros.com/download)
> * Any Extra File link if required : [Tap Here for link](https://sourceforge.net/projects/project-elixir/files/fourteen)

<br>

> [!Note]
> * Installation Guide: [Tap here](https://projectelixiros.com/download)
> * Gapps is already included in zip no need to flash additionally
> * Make sure to use V14.0.5.0.SJKCNXM firmware
> * For fixing play integrity: Open Updater, click on 'Update PlayIntergrity Fp' then clear play store data and reboot once
> * If you are coming from PORTs then you need to Format Data and flash latest firmware [depending on the device]
> * If you are coming from Android 12 or 13 to Android 14 then clean flash is compulsory and format data.
> * If you are encrypted do format Data before flashing build to avoid bugs.
