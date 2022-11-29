![Device Changelog](https://i.imgur.com/C0Wcdr5.png)

### Vince 3.3
- November Security Patch
- Disable EGL buffer_age extension support
- Disable Skia tracing by default
- Disable client composition cache
- Disable phantom process monitoring
- Enable zygote critical window
- Do not block binder thread on incoming calls
- Switch to AutoSingleLayer Android 13 Setting
- Set BT device name via sysprop
- Enable Preferred network type options menu by default
- Migrate "rounded_corner_content_padding"
- Migrate rounded corner size to A13
- Remove FDE related property trigger
- Remove IO read_ahead_kb tune
- Remove unused fast dormancy persist property
- Remove unused tcp property change actions
- Remove hbtp components
- Enable discard option to retain speed.
- Disable the usage of ConfigStore
- Remove bdroid_buildcfg.h
- Remove packages at build time
- Upstream kernel to 4.9.344

### Vince 3.1
- Drop FDE support entirely 
- rootdir: Drop quota flags 
- rootdir: Remove encryptable=userdata for external SD 
- props: Use the ?= operator so BT properties can be overridden 
- overlay|props: Disable Recovery overrides from source
- Correct TARGET_RECOVERY_DEVICE_MODULES 

### Vince 3.0 hotfix
- Fixed Bluetooth issues
- Fixed Hotspot issues
- Fixed USB tethering

### Vince 3.0
- September Security Patch
- Initial BETA Release
- Enforcing Build
- CTS passes by default
