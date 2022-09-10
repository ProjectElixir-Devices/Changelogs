## 2.1 Toco

- EOL Android 12 build

## 2.0 Toco

- Add more gnss seccomp_policy
- audio: Add compress recording configurations
- audio: Add Stereo config channel support to usb surround sound
- audio: Fix copyright
- audio: Fix in-call mic with headphones
- audio: Fix mic volume
- audio: Import stock audio_policy_engine_stream_volumes.xml
- audio: Increase mic volume values
- audio: Provide missing audio_tuning_mixer.txt
- audio: Remove dynamic attributes from APS config
- audio: Set the maximum music group volume to 15
- audio: Update compress recording configurations
- Build android.hidl.base@1.0
- Build missing omx lib
- Drop remnant Snap stuff
- Drop Vulkan UI renderer (Fixes video colors)
- gps: Add nmea tag block grouping feature
- gps: Comment out ANTENNA_INFO_VECTOR_SIZE by default
- gps: Update configs from sweet V13.0.8.0.SKFMIXM
- gps: Update to LA.UM.9.1.r1-11200-SMxxx0.0
- Import more camera libs from stock
- Make all elf prebuilts packages
- media: Update max resolution from True4k to UHD
- parts: Drop support for zero brightness doze mode
- parts: Update and polish vector drawables
- perfd-client: Refactor dummy libqti-perfd-client 
- perfd-client: Remove namespace declaration
- perfd-client: Return a dummy value
- powerhint: Add F2fsRecessModeEnable
- prop: Fix mic volume in Apps
- prop: Force disable iorapd
- prop: Sync up /system_ext properties with QSSI 12
- Provide module name for libcameraservice
- Re-enable zram writeback
- Rename camera face detection libs
- Restrict interrupts to cores 0 and 1
- rootdir: Add edgnss socket directory
- rootdir: Increase the console log level
- rootdir: Set Netflix property based on target
- rootdir: Set permissions for KGSL sysfs node
- rootdir: Stop using hardcoded boot device
- sepolicy: Add F2FS sysfs permission
- sepolicy: Address camera hal denial
- sepolicy: Address dpmd denial
- sepolicy: Address dolby denials
- sepolicy: Address mi_thermald-related denials
- sepolicy: Address neuralnetworks hal neverallow
- sepolicy: Address some duplicate
- sepolicy: Address some wifi denials
- sepolicy: Allow bluetooth to read incremental prop
- sepolicy: Allow radio to connect to dpmd stream socket
- sepolicy: Extend vendor_toolbox permissions to files in persist
- sepolicy: Fix setting ims props on boot
- sepolicy: Label new telephony properties
- sepolicy: Rework & label more wakeup nodes
- sepolicy: Suppress zeroth.debuglog.logmask warning
- Set soc properties
- Ship VantomKernel v4.14.290
- Switch to new Elixir flags
- udfps: Refactor udfps handler lib
- Update adreno stack from from LA.UM.9.14.r1-19300.01-LAHAINA.QSSI12.0
- Update blobs from sweet V13.0.8.0.SKFMIXM
- Update blobs from sweet V13.0.12.0.SKFMIXM
- wifi: Update from sweet V13.0.8.0.SKFMIXM
- WifiSM6150: Add & increase 5 GHz network signal tolerance
- WifiSM6150: Align config.xml with AOSP

## 1.9 Toco

- Add missing status bar dimensions
- Add MIUI camera flag from stock
- Add telephony system-ext privapp permissions
- Address elliptic denials
- Address QCOM WFD denials
- Allow platform app to find SoterService
- Allow system_app to write thermal sysfs
- Build custom UDFPS animations
- Disable zram writeback
- Drop QCOM wfd HDCP support
- Enable auto brightness while dozing
- Fix fingerprint labels
- Import lmkd props from google gki
- Label fingerprint props as restricted vendor
- media: Add Attribute name for SW encoder
- media: Finetune performance xml
- media: MPEG4 sw encoder only supports max 720p
- Move deviceid props to vendor
- parts: Add dynamic thermal profile implementation
- parts: Display icon beside thermal profiles
- parts: Don't explicitly set android:theme for activities
- parts: Use directBootAware
- Remove unused hwservice label
- Rename ANXCamera to MiuiCamera
- Revoke system_server access to fingerprint prop
- Ship VantomKernel v4.14.286
- Switch SchedTune to UClamp
- Switch to status_bar_height_portrait
- Update build fp & desc to MIUI V13.0.2.0.SFNMIXM
- Uprev radio config into 1.2
- Use coral tuning for columbus feature

## 1.8 Toco

- Drop QCOM thermal engine components
- Drop updatable GPU drivers
- Fix UDFPS not registering
- Implement UDFPS handler
- Import dolby codecs
- Move to common Xiaomi fingerprint HIDL
- parts: Handle more errors for dirac
- parts: Use directBootAware
- Pull sepolicy from SM8250
- Ship Lawnchair launcher
- Ship VantomKernel v4.14.282
- Switch to EROFS for dynamic partitions
- Support F2FS compression and garbage collector
- Update blobs from LA.QSSI.12.0.r1-07100-qssi.0
- Update display color compositions
- Update system WFD blobs from 07100

## 1.7 Toco

- Add missing seccomp policy
- Add Moto Dolby audio
- Address various seolicy denials
- Allow more cached apps in the background
- Configure burnin shift interval
- Convert overlays into RRO_Overlays
- Copy verified boot permissions
- Drop all component overrides
- Drop useless volume_listener
- Enable VoLTE and VoWIFI for all
- Fix being stuck in bootanimation for users
- Fix NFC denials
- Include new gnss seccomp rules
- Set valid and supported channel mask for earpiece
- Ship VantomKernel v4.14.278
- Some performance improvements
- Switch to full IWLAN mode
- Update GPS config for A12
- Update Media configs from LA.UM.9.12.r1-13400.02-SMxx50.QSSI12.0
- Update surfaceflinger props
- Use QTI health implementation
- Wi-Fi improvements

- Improve haptic and vibe patterns
- Switch to full_base_telephony
- Include firmware by default
- Include ANXCamera
- Use QCOM implementation for audio effects
- Turn down doze brightness a little bit more
- Update vendor security patch level
- Enable NearbyMessagingService
- Update Media configs
- Import QTI Codec2 HAL
- Powersaving in charger mode
- Fix broken EGL symlinks
- Update CarrierConfig overlay
- Update wifi overlay from MIUI
- Fixup QTI health implementation
- Update blobs from sweet V13.0.7.0.SKFMIXM
- Enable screen-off udfps by default
- Fix display animation while AOD on/off screen
- Switch to PlayGround clang
- Update config_safe_media_volume_index
- Switch to source-built MliPay interface
- Tune for AOD

## 1.6 Toco

- Initial official build
- Enforcing user build
- CLEAN FLASH is required
- SafetyNet pass without root
