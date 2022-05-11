![Changelog](https://i.imgur.com/HkvVB5q.jpg)

# Project Elixir All Version Update Changelogs

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
