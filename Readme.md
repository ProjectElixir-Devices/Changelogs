![Changelog](https://i.imgur.com/3uuYftu.png)

<br>
<br>

<h1 align="center"> Project Elixir All Version Update Changelog </h1> 

<br>
<h2 align="center">- Below changes are from Android 13 </h2> 
<br>

### v3.1 (19.09.2022)
- Merged latest September Security patch
- CTS Passes by default and banking apps are working fine
- Essence: Bring back icon shapes, icon packs, fonts Customisation
- SystemUI: Optional haptic feedback on back gesture
- Essence: Add charging info on lockscreen
- BatteryService: add dash, warp, vooc charging support
- AlertSlider: Introduce user interface for Alert Sliders
- BatteryService: Add SuperDart charging support 
- Essence: Add network traffic indicator
- Essence: SystemUI: Port brightness slider changes
- base: Add support for window ignore secure 
- display: Add simple RGB color balance transform 
- SystemUI: Improve the QS tile styles
- Essence: Add Transparent QS customization 
- AutoBrightness: Add support for one shot auto-brightness
- SystemUI: Updates to various icons
- fw/b: Add capability to allow tethering to use VPN upstreams
- frameworks: Add unlinked ringtone and notification volumes
- Settings: Forward port CM Screen Security settings 
- Settings: Expose radio info (*#*#4636#*#*)
- Essence: Alert Slider: Add toggle to disable notifications 
- kernel: Changes for LLVM binutils
- Allow to suppress notifications sound/vibration if screen is ON
- kernel: Allow to set custom user and host strings 
- ven/aosp: rro_overlays: Update for Android 13
- Misc changes & improvements
- Much More - Try by yourself

### v3.0 (29.08.2022)
- Initial Android 13 BETA build with August Security patch
- CTS Passes by default and banking apps are working fine
- Settings: Elixir: Redesign My Device Page
- Settings: Elixir : Redesign our Firmware information
- Settings: Elixir: Adapt our new layout in rest settings
- Essence: QS customization [Optional]
- Essence: Added Wifi Icon style [Optional]
- Essence: Hide power menu on secure lockscreen
- Essence: Hide Status bar on Lock screen
- Essence: Add Lockscreen album art filter
- VolumePanel: Redesign Volume pannel
- Package installer: show current and new version on apk installation
- Essence: Make LS media filter blur radius configurable
- Essence: Global Actions with Advanced Reboot
- Essence: Double tap to sleep on lockscreen
- Essence: Double tap to sleep on statusbar
- Base: Add Maybe Rectangle QS Style
- QS Tiles: Introduce Outline Shapes
- SystemUI: Implement lockscreen quick unlock 
- base: allow disable of screenshot shutter sound
- Keyguard: Add option to scramble pin layout when unlocking
- SystemUI: Add auto brightness button to QS brightness slider
- Base: Add custom signal style support
- Privacy Indicators: Follow light/dark theme settings
- SystemUI: Use Monet colors for power menu
- SystemUI: Allow to enable Lockscreen Media Art
- base: Add three-fingers-swipe to screenshot 
- SystemUI: Display a toast when a screenshot is deleted
- SettingsLib: Update LTE+/4G+ icon as per new Silk design 
- SettingLib: Add deep sleep info to uptime preference 
- BatteryStatsImpl: Reset stats only above 95%
- SystemUI: Add delete action to screen recorder notification 
- SystemUI: Update BT battery level from OOS
- SystemUI: Forward-port smartspace to Android 13 
- SystemUI: Bring back separate wifi & data QS tiles 
- udfps: Implement framework dimming support
- base: allow hiding navbar
- SystemUI: allow changing the length of gesture navbar 
- base: Add navbar layout inversion tuning 
- udfps: Implement framework dimming support
- Settings: Introduce PUI iconpack
- Settings: Revamped Setting page
- Settings: Toast insulter: Add insults 
- Expose the notification log
- Misc changes
- Much More - Try by yourself

<br>
<br>

<h1 align="center"> Below changes are from Android 12.1 </h1> 

<br>
<br>

![Android 12.1 Changelog](https://i.imgur.com/N84YZja.png)


### v2.1 (06.09.2022) | EOL Update | Last Public Update
- CTS Passes and banking apps are working fine
- Essence: Switch to new UI 
- Implement A13 like seekbar animation
- Fixed some font were not working
- Updated the build status card logo 
- Fixed gaming mode crash on some devices
- Essence: Add Elixir Lock Screen Clock
- Essence: Add outline QS Style
- ven/aosp: Update the default wall for v2.1

### v2.0 (12.08.2022)
- Merged latest August Security patch 
- CTS passes by default and banking apps are working fine
- Settings: Elixir: Redesign My Device Page 
- Settings: Elixir : Redesign our Firmware information
- Settings: Elixir: Adapt our new layout in rest settings 
- Essence: Transparent QS customization [Optional]
- Essence: Add toggle to switch Fluid QS panel style [Optional]
- Essence: Add horizon light settings
- Essence: Adapt whole UI to match with settings
- GlobalActions: Redesign Power Menu
- base: Force fullscreen for Google Dialer
- ven/aosp: Update Default wall for v2.0 Release
- Use navigation handle dimens from Android 13 Beta 3
- SystemUI: Fix QS expand lag when VoLTE/VoWiFi icons are enabled
- CustomClocks: Cleanup some useless codes of ButterCupSyra clock 
- CustomClocks: Fixed padding for custom clocks
- VolumePanel: Show percentage 
- Package installer: show current and new version on apk installation 
- CustomUtils: Import restart systemui api 
- PixelPropsUtils: Update raven fingerprint
- SystemUI: Fix QS mobile icon disappearing on theme switch 
- vendor: Show Android version as 12L 
- ven/aosp: Import More Fonts Overlay 
- ven/aosp: Themes: Add lots of signal icons
- ven/aosp: Themes: Add W33d icon styles
- Essence: Fix crash with media art
- Improved stability and performance
- Misc changes and improvements
- Much More - Try by yourself

### NOTE: Don't report anything related to CTS or Banking apps if you do ROOT or modify anything in system or using MODs.

### v1.9 (07.07.2022)
* Merged latest July Security patch
* Essence: Add fade filter to the media artwork 
* Essence: Slide on Statusbar brightness control
* Essence: Add QS Tiles customization
* Essence: Add lockscreen clock options
* Essence: Add brand new lock screen clocks Waifu box style 
* Essence: Add brand new lock screen clock buttercup Syra style
* Essence: Toggle data usage view on QS footer 
* Essence: Allow hiding call strength icons 
* Essence: Add SystemUI Tuner Shortcut
* Essence: Re add Ripple effect toggle
* Essence: Disable QS battery estimates 
* Essence: Add github profiles of core devs
* Essence: Added hell lot of UDFPS icons
* base: EasterEgg: Implement Android 12L Easter Egg
* Implement Spark Ls Clock Style 
* Switch back to stock style seekbars to match UI consistency
* Redesigned permission grant dialog
* Settings: Fix ringtone selection for devices with e-SIM 
* Fix NPE on isUdfps
* Settings: Make NetworkScanHelper max search time customizable
* Add upstream fixes to ElectronBeam screen-off animation
* Updated PixelLauncher and Lawnchair (depends on maintainer which one to include)
* PixelPropsUtils: Disable spoof for recorder app 
* Limit SafetyNet workarounds to unstable GMS process
* Remove VoLTE icon padding
* Fix inaccuracy in biometric timeout 
* Make QS brightness slider animation more subtle
* SystemUI: media notification: Remove blur customizations
* SystemUI: Better QS detail clip animation
* PixelPropsUtils: Update fingerprints to July 2022 release
* vendor: Add overlay to fix app icon font on PixelLauncher
* ven/aosp: Bump to v1.9 & update default wall 
* Fix colors on DocumentsUI
* Improved stability and performance
* Misc changes and improvements 
* Much More - Try by yourself 

### v1.8 (09.06.2022)
* Merged latest June Security patch
* Essence: Allow changing monet settings
* Essence: Bring back Lockscreen media art & blur custs 
* Essence: Bring back icon shapes, icon packs, fonts Customisation
* Essence: Add signal and wifi icon style theming
* Essence: Allow doubletap/longpress power to toggle torch 
* Essence: Added Gamespace In Essence
* Essence: Ignore window secure flags 
* Essence: Introduce OOS style notification clear all button
* Essence: Added Media notification background customizations
* Essence: Bring back Udfps icons and Animations 
* Settings: Add option to launch statusbar tuner
* Settings: Add preference for one shot auto-brightness 
* SystemUI: Show daily data usage in QS footer
* fonts: Import more font overlays
* SystemUI: Integrate Google Lens into Screenshot UI
* BatteryService: add Turbo power charging support
* BatteryService: Add VOOC charging support
* BatteryService: Add Warp charging support
* BatteryService: add dash charging support
* BatteryService: Add SuperDart charging support 
* MediaControlPanel: Get color from album art and apply to qs media player
* Screenrecord: Allow to reduce 3 second screen record timer 
* Privacy Indicators: Follow light/dark theme settings 
* PixelPropUtils: Add GamesProps (fps unlocked)
* Scramble pin: fix scrambling after 12L
* Fixed location indicator popin frequently
* Added Lawnchair and Teamfiles PixelLauncher MOD (OPTIONAL- Ask your maintainer)
* Improved stability and performance
* Misc changes and improvements 
* Much More - Try by yourself 

### v1.7 (11.05.2022)
* Merged latest May 5 Security patch
* Introduce high touch polling rate feature control 
* Add support for per-app volume 
* Add back increasing ring feature 
* Configurable 0, 90, 180 and 270 degree rotation
* SystemUI: Make the volume dialog expandable
* SystemUI: Add AOD QS tile 
* Settings: Revamped Setting page 
* SystemUI: Add USB Tether tile 
* Fixed Gesture Setting Crash
* PixelPropsUtils: Update fingerprints to May 2022
* SystemUI: Add AmbientDisplay tile
* Settings: Introduce PUI iconpack
* SystemUI: Add Sync tile 
* SystemUI: Bringup statusbar icons tuner 
* SystemUI: Add heads up tile
* BatteryHealth: Add Battery Capacity info 
* SystemUI: Add caffeine QS tile
* Settings: PowerUsageSummary: open advanced usage on header click 
* SystemUI: Add VPN to the icon blacklist in tuner
* Settings: import illustrations from raven SP2A.220305.013.A3
* Settings: Completely nuke Screen Saver function
* Settings: Move Extra Dim feature to Display 
* prebuilt: fix APN for Vodafone NL
* Bump to v1.7 and Update wall

### v1.6 (06.04.2022)
* Full Rebase our repos on Android 12.1 
* Merged latest April Security patch  
* Added support for call recorder 
* CTS Passes by default and banking apps are working fine
* Switch back to stock settings like pixel 
* Essence: Cleanup and fixes 
* Faceunlock and Applock Added on 12.1 Rebase Source 
* Port changes from SystemUIGoogle 
* SystemUIGoogle: Import dagger dependencies 
* vendor: Bump to v1.6 and Update wall  
* gapps: Update from SP2A.220305.013.A3 
* Much faster overall system response and animations processing
* Hell lot of changes and optimization 
* Improved performance and stability

### v1.5 (08.03.2022)
* Added Face Unlock into System
* Added Applocker into System
* Settings: Revamped Setting page
* Essence: Add navbar layout inversion tuning 
* Essence: Allow changing monet settings
* Essence: Toggle for Black theme
* Essence: bring back old style mobile data indicators
* Essence: Add Qs & Themes Section
* Essence: Allow disabling ripple effect on unlock 
* SystemUI: Android 13 inspired Media Output Picker
* SystemUI: Use same background color for Internet and Screen record
* SystemUI: Android 12L style Internet and Screenrecord dialogs 
* Settings: Implement cutout force full screen 
* Settings: allow changing the length of gesture navbar
* Settings: Add preference for one shot auto-brightness 
* Seekbars: Redesign seekbar
* SystemUI: Integrate Google Lens into Screenshot UI
* SystemUI: Adapt screenrecord dialog switches UI to 12
* Settings: Move blur toggle to Display options.
* Settings: Enable blur on Bluetooth and Media control panel
* Settings: Added missing icons in network and internet menu
* Settings: Add hotspot setting to allow VPN upstreams
* PixelProps: Set Pixel 5 as spoof for more Google apps 
* SystemUI: Use AndroidSystemBlur styled Blurs
* Screenrecord: Add an option to record for longer 
* Screenrecord: Make low quality bitrate scalable per device
* Screenrecord: add blinking stop dot and low quality options
* Screenrecord: add blinking stop dot and low quality options
* PixelPropsUtils: Bypass hw attestation on newer pixel devices
* Fix edit button in screenshot share activity 
* Settings: Restore AOSP fingerprint enrolling layouts
* Restore AOSP PeakRefreshRatePreferenceController
* Import some UI sounds from Samsung S21 FE
* Remove navbar inset for UDFPS BiometricPrompt 
* zygote: Enable USAP by default for S.
* base: Show USB icon in ADB notification
* panels: Add Wifi panel
* panels: Add Mobile Data panel
* panels: Add Bluetooth panel 
* Settings: Improve code for time spent in app
* Settings: Move Extra Dim feature to Display 
* Essence: UI minor Improvement and adjustments
* vendor: Disable blur on app-launch
* vendor: Disable Async MTE on System Server
* vendor: Fix NFC animation background 
* ven/aosp: Bump to v1.5 and Update wall 
* vendor: tasks: Support copying kernel modules out to /vendor_dlkm.
* apns: Add Unifi
* vendor: Enable blur by default.
* vendor: soong: Add camera_needs_client_info_lib
* overlay: core: Use accent color for progress bar background 
* Add config for Repainter integration service 
* Much faster overall system response and animations processing
* Hell lot of changes and optimization 
* Improved performance and stability

### v1.4 (10.02.2022)
* Merged latest February Security patch Release 29
* CTS Passes by default and banking apps are working fine
* Switch back to stock QS style like pixel 
* Essence: Add HeadsUp, timeout, blacklist & snooze function  
* Essence: Allow forcing small keyguard clock 
* Essence: Less boring heads up option 
* Essence: Add volume panel on left toggle 
* Essence: Screen off animations 
* Settings: Add back theming into display settings 
* Bring back Udfps icons and Animations   
* Settings: UI minnor Improvement and adjustments
* Essence: Team: Update Teams and links
* Settings: align user avatar with homepage title
* Settings: Make ROM banner clickable 
* Settings: Implement button settings 
* vendor: Add more drawable XMLs for themed icons
* vendor: Build TouchGestures 
* kernel: Implement build time LTO choice 
* Revert "Revert "kernel: fix KERNEL_TOOLCHAIN_PATH_gcc and usage""
* Changed protocol from IPV6 to IP for Telus
* overlay: core: Disable OtaSuggestionSummaryProvider from GMS
* overlay: core: Use accent color for progress bar background 
* PixelPropsUtils: Avoid spoofing props for gcam and mods
* Skip screen on animation when wake and unlock via biometrics
* SystemUI: Update icon for Heads up tile. 
* Redesign Action Chip
* Fix deadlock issue.
* fw/b: Button backlight brightness 
* SystemUI: Allow using tuner API for custom settings
* fwb: Re-introduce keyboard backlight brightness control
* base: Add Touch HIDL support
* SystemUI: Implement burn-in protection for status/navbar
* overlays: oos: Add statusbar bluetooth icons
* overlays: Add an OxygenOS icon pack
* SystemUIGoogle: Import Reverse Charging and Battery Saver tiles
* SystemUIGoogle: Import proto deps for columbus CHRE impl
* PixelPropUtils: remove spoofing for currently supported Pixels
* SystemUI: Introduce ColumbusCompatibilityHelper
* Much faster overall system response and animations processing
* Hell lot of changes and optimization 
* Improved performance and stability

### v1.3 (15.01.2022)
* Latest January Patch r27 Merged
* CTS Passes by default and banking apps are working fine
* Unlimited Google photos in original quality available
* Elixir : Introduce OTA Updater
* AboutPhone: Update Elixir Logo (Monet Based)
* Added network traffic indicator
* Essence: Added Elixir Team Section and some Adjustments 
* Essence: Add lockscreen media artwork options 
* Essence: Media notification background customisations
* Essence: Make "Require unlocking to use sensitive QS tiles" optional
* Redesign Quicksettings (Big Thanks to OctaviOS)
* SystemUI: BrighntessSlider: use OOS icons 
* Fixed: Port Statusbar brightness control not working
* SystemUI: allow devices override audio panel location
* Add custom pref for devices with custom doze packages
* Settings: Updated Essence icon 
* device_Config: Update Now Playing database to 2021-12-12
* Elixir: UI minnor Improvement and adjustments 
* Add platform and RAM to Model & Hardware 
* Create new preview for dark theme
* SystemNavigationGestureSettings: fix back gesture edge insets resetting back when fullscreen gestures is enabled
* vendor/aosp: Bump to v1.3 
* Settings: Rearrange about section 
* SystemUI: Make Privacy Indicators better
* Always show APN settings on CDMA carriers
* Make QS brightness slider animation more subtle 
* Apply monet to fingerprint authentication ripple animation
* Fixed: SystemUi restart issues when earphones plugged in
* PowerManager: Add proximity check on wake 
* BatteryService: Add SuperDart charging support 
* BatteryService: Add VOOC charging support 
* BatteryService: Add Warp charging support 
* BatteryService: add dash charging support
* Full rebased few repos to clean android-12.0.0_r27 tag
* Disabled huge amount of unnecessary debug stuffs
* Much faster overall system response and animations processing
* Hell lot of changes and optimization 
* Improved performance and stability

### v1.2 (11.12.2021)
* Latest December Patch Merged 
* Added statusbar clock & battery customisation
* Allow to suppress notifications sound/vibration if screen is ON
* Allow doubletap/longpress power to toggle torch
* Added Lockscreen Charging info
* Added volume Long Press Skip Tracks
* Haptic feedback on back gesture
* Introduce pocket lock mode
* Add option to enable AOD on charging only
* Added many QS Tiles
* Incall vibration options
* Add VOLTE icon toggle and volte/vowifi customisations
* Allow using 4G icon instead of LTE
* Add Haptic Feedback to tiles
* Added Elixir Bootanimations
* allow hiding navbar 
* Hell lot of changes and optimization 
* Improved performance and stability

### v1.1 (23.11.2021)
* Latest November Patch Merged
* CTS passes by default
* Added back missed prefs animations
* Updated props, ringtone,overlays from SD1A.210817.015.A4
* Update 4G+ icon to Silk design as well 
* Fixed an issue where notification drawer becomes transparent
* Fixed half black wallpaper after rotating quickly 
* Settings: Bring in missing lottie animations
* Settings: Show all available SIMs in provider model 
* Improved Performance and Stability
* Misc changes and fixes

### v1.0 [Part 1 and 2] (21.10.2021)
* Initial Android 12 Build
* CTS Passes by Default
* Add back SELinux info in about page
* Add option to scramble pin layout when unlocking 
* Show Bluetooth battery level when available
* Enabled 2-button navigation bar
* Enable LTE+ icon by default
* Allow user to add/remove QS with one click
* Introduced three-fingers-swipe to screenshot
* Introduced wallpaper based system colors
* Introduced PixelPropUtils
* Added Double tap to sleep on lockscreen 
* Added Double tap to sleep on statusbar
* Fingerprints: Increase MAX_FAILED_ATTEMPTS
* Powermenu: advanced reboot toggle - android 12 
* Add unlinked ringtone and notification volumes
* udfps: Implement UdfpsHbmProvider 
* Add button to AppErrorDialog to upload crash information to katbin
* Update LTE+ icon as per new Silk design
* Update keyguard clock metrics for Inter font
* Add rounded corners to activity open/close animation 
* Screenshot: Add delete action chip intent 
* PixelPropsUtils: Invite streaming apps to the party 
* Notifications: Make USB-Debugging notification less important 
* Added preference for maximum screen refresh rate 
* Added preference for KEY_MIN_REFRESH_RATE 
* Settings: About: Update Elixir Logo
* Change dividers from Holo Blue to Pixel Blue 
* SystemUI: Follow light/dark theme in power menu 
* SystemUI: Use Monet colors for power menu 
* Increase rounded corner radii to match Pixel style 
* Add dual-tone light and dark themes for QS
* Make QS panel follow the light system theme
* Reduce screenshot dismiss delay to 2 seconds 
* Fixed Charging Indication not showing on some devices
* Fixed FOD not showing issues
* Improved Performance & stability
