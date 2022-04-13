## 1.6 Violet
- Clean Flash Compulsory & dont use OTA for this update
- Switched to Qcom sound effects
- Switched back to stock volume values (Fixes audio distortion)
- Apply a boost after fp is authenticated (Fingerprint)
- Added ANX Camera as default camera
- Improved performance and stability 
- Misc changes and fixes


## 1.5 Violet
- Updated Display & Graphics blobs to LA.UM.9.1.r1-11400.02-SMxxx0.QSSI12.0
- Updated System blobs to LA.QSSI.12.0.r1-05600-QSSI.0
- Updated Bluetooth blobs from davinci-user 11 RKQ1.200826.002 V12.5.2.0.RFJCNXM release-keys
- Updated stock blobs from VIOLETINGlobal_V12.5.1.0.QFHINXM
- Updated GPS blobs from LA.UM.9.1.r1-10900-SMxxx0.0
- Disabled VSync for CPU rendered apps 
- Disabled TTS force stop warning 
- Enabled haptic text cursor
- Removed renderscript from pinner services
- Removed mobile plan settings
- Updated QTI Data Factory version to v2.3 
- Switched to c2 media codecs (Updated from sunfish)
- Switched back to QTI BT Stack
- Tuned power hint
- Addressed various sepolicy denials
- Fixed carrier video calling
- Added Quick Tap
- Import Google changes on DEC7 Volume
- Fixed Encryption
- Fixed a distrubing sound at very low volume(Wired Earphones)
- Boost audio output a bit
- Disabled the force stop warning shown in setup wizard
- Fixed carrier video calling
- Updated several blobs
- Addressed some denials
- Disable blur on app launch
- Disable prevent Accidental Wake-up and pocket mode

## 1.2 Violet

- Updated Graphics blobs from LA.UM.9.1.r1-10900-SMxxx0.0
- Updated Radio blobs from LA.UM.9.1.r1-10900-SMxxx0.0
- Updated QMI blobs from LA.UM.9.1.r1-10900-SMxxx0.0
- Updated DSP Hal, ADSP, ADSP Modules and CDSP blobs from LA.UM.9.1.r1-10900-SMxxx0.0 (Fixed ADSP Path related logspam)
- Imported Neural Networks from LA.UM.9.1.r1-10600-SMxxx0.0
- Built Missing vendor variants of neural networks
- Checkout CarrierConfig to LA.UM.9.1.r1-10700-SMxxx0
- Updated ImsFactory to v1.1 
- Updated UimLpa hal to v1.1 
- Updated UceService HAL to 2.3 
- Updated Factory version to v2.2 
- Updated QtiRadio HAL to v2.6
- Updated ImsRadio version to v1.7. 
- Brought back datastatusnotification (Updated from coral)
- Cleaned debug properties for graphics layer
- Removed no-op display HDR & WCG 
- Disabled switching to s2idle 
- Disabled collect I/O statistics on runtime 
- Allowed all filesystems for USB-OTG 
- Enabled wallpaper zooming
- Enabled 64-bit inode version support for ext4 
- Powerhint: Added sched {up,down}migrate hint from QCOM perf boost
- Powerhint: Modified capacity margins for sm6150
- Power-libperfmgr: Initialize powerHAL when boot is completed
- Imported more vibration overlays
- Tuned vibration pattern (Better haptic feedback)
- Uprev fingerprint hal to v2.3
- Switched to caf thermal service
- Synced with stock audio properties
- Switched arch variant to armv8-2a-dotprod
- Parts: Added fps counter qs tile
- Parts: Synced dirac strings with A12
- Dirac: Added support for live refresh check when toggled (No need to pause and play)

## 1.1 Violet

- Enforcing Build
- Bankings apps are working fine
- Added Mi Dirac
- Switched to Azure Kernel
- Drop GoogleCameraGo
- sepolicy: Relabel drm hal denial 
- violet: Drop ignore neverallows flag
- violet: Don't Force triple frame buffers
- overlay: Add available Color Modes 
- rootdir: Add back thermal-engine definition 
- overlay: Improve padding and margins
- violet: Disable hwc vds
- overlay: Add physical button/sensor locations 
- Improved Haptics and Audio Quality

## 1.0 Violet

- Selinux is Enforcing now
- Fixed Voip Echo related issues in whatsapp
- Fixed HD playback in Amazon Prime
- Improved Sound Quality 
- Sepolicy: Address hal_drm & hidl_base denials
- CTS Pass by default
- Gapps Included ! 
