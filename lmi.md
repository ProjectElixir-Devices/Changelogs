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
### Notes

```
- Make sure to use V14.0.5.0.SJKCNXM firmware
- If you are coming from ports or HentaiOS = Format Data and Boot to MIUI first.
- Dirty flash from A13 to A14 is possible and already tested but clean flash is still recommended.
```
