Device Changes 

# Project Elixir v2.1 

 - No device changelogs for this release 

# Project Elixir v2.0 

 - Revert back to default paddings and margins 
 - Rebase to aLn kernel 
 - Upstream Pixel Launcher MOD to v10.8
 - Import full set of audio configs from MIUI EU 13.0.5

# Project Elixir v1.9 

 - Removed Pixel Launcher MODs app, as it requires root 
 - Fixed greyed out USB actions in notifications when connected to PC 
 - Revert "Set Recommended Night Display Color Temperature as default" 

# Project Elixir v1.8 [2nd Release]

 - Fixed heating issue and battery drain issues 
 - Fixed Fast Charging
 - Upstreamed Pixel Launcher MOD to v9.5 | [Changelogs](https://telegra.ph/Changelog-Of-Pixel-Launcher-MOD-05-28)

# Project Elixir v1.8 

 - Upstreamed Pixel Launcher MOD to v9.3 | [Changelogs](https://telegra.ph/Changelog-Of-Pixel-Launcher-MOD-05-28)
 - Upstream GCam to MGC_8.1.101_A9_GV2b | [Source](https://www.celsoazevedo.com/files/android/google-camera/dev-bsg/f/dl88/3/)
 - Added Moto Dolby by ReiRyuki - [Source Code](https://github.com/reiryuki/Moto-Dolby-G-Pro-Magisk-Module)
 - Add per-app refresh rate settings

# Project Elixir v1.7 

- Reduce time taken to boot into system (Faster boot times, usually took 10 seconds to move from splash screen to boot animation, reduced that delay to half)
 - Added modded Pixel Launcher as prebuilt home app
   - Double Tap to Sleep
   - More Grids Options [Available 6x9, 6x8, 6x7, 6x6, 5x8, 5x7, 5x6, 5x5, 4x7, 4x6, 4x5, 4x4, 3x3, 2x2]
   - The appearance of app-drawer in-device search bar colour in light/dark theme is correct(which is buggy in original pixel launcher on all aosp based roms, only works fine in pixel devices)
   - Search Results Highlight Colour shows in material you colour. When you press enter while highlighting search results, that app/settings opens. Subtle Changes in Group Highlights & Search Box Highlight
   - Smoothness better than original launcher. Added Tweaks which makes the launcher more smoother.
   - Added themed icons from the module
   - [Bug] Weather widget in 'At a Glance' widget (below calendar/date) not launching google weather app (Weather data is working fine tho)
   - [More Changelogs here](https://telegra.ph/Changelog-Of-Pixel-Launcher-MOD-03-31-2)
 - Make the UI smoother on top of smoothness provided by Android 12.1
 - Enable haptics when swiping text cursor
 - Remove mobile plan from Settings -> Network & Internet
 - Set Recommended Night Display Color Temperature as default. [Reference](https://www.google.com/search?q=recommended+display+temperature+for+night+mode&rlz=1C1ONGR_enIN974IN974&oq=recommended+display+temperature+for+night+mode+&aqs=chrome..69i57j33i160l2.15403j0j7&sourceid=chrome&ie=UTF-8#:~:text=During%20the%20daylight%20hours%2C%20it%27s%20best%20to%20keep%20your%20monitor%20relatively%20cool%20with%20a%20default%20color%20temperature%20of%206%2C500K.%20At%20night%2C%20the%20color%20temperature%20should%20be%20warmer%2C%20and%20around%203%2C400K.)
 - Add Haptics level customisations
 - Add G Cam by BSG as default 
   - Bug: Camera crashing when system's camera API is requested
   - Updated GCam to latest version (MGC_8.1.101_A9_GV1zfix). [Source](https://www.celsoazevedo.com/files/android/google-camera/dev-bsg/f/dl75/1/) 
   - [Recommended config](https://t.me/chandeler_s_chat/13930) 
 - Increase SWAP (zRAM) memory to improve system smoothness
 - Add QS tile to launch Thermal Profiles
 - Add FPS info QS tile
 - Add Ambient Display settings
   - Pick-up to wake device
   - Hand Wave to wake device
   - Wake device when out of pocket

# Project Elixir v1.6 HotFix 

 - Adapt fingerprint overalys for Android 12.1 
 - Fix Double Tap to Wake 
 - Add Device specific settings AKA Xiaomi parts 

# Project Elixir v1.6 

 - Nuke Adaptive charging  - Add call recording to Google Phone app
 - Add back Camera2 
 - Show **Turbo Charging** when using the proprietary charger, like MIUI
 - Video captured in ScrenRecorder is capped to 120 FPS
 - Some network and GPS improvemnts 
 - Reintroduce `Device parts` with
   - Dirac Sound Enhancer
   - Clear Speaker
   - Thermal Settings
 - Dirac Sound Enhancer (AKA) Mi Sound Enhancer 
   - New Presets Added: Live, Balanced, Bass Reduction, Treble Reduction, Soft Bass, Soft Treble 
   - Ported MiSound scenes 
 - Revert "combined signal icons in status bar" 

# Project Elixir v1.5 

 - No device changes

# Project Elixir v1.4 

 - Add support for AUX camers in Open Camera App
 - Nuke default camera app
 - VILTE calls working
 - Enable combined signal icons in status bar
 - Increase handset speaker and mic volume
 - Enable quick tap
 - Enable adaptive charging
 - Add 'Saturated' color mode
 - Dropped Xiaomi Parts
