# Redmi Note 7/7s Lavender 


# Version v16.8 kernel 4.4 (21-08-2021)

- Vilte support added 
- Clear up Xiaomi part.
- Added Hack's for unlimited photos backup on Google photos.
- lavender: overlay: Set fast charging indicator threshold to 10.8W
- lavender: overlay: Add Max visible notification icons overlay
- lavender: Show "Turbo charging" instead of "Charging rapidly"
- lavender: overlay: Force show network traffic on statusbar
- lavender: overlay: Disable UI touch sounds by default
- lavender: overlay: Disable wallpaper zooming
- lavender : properly set all corvus related overlays
- lavender: Force triple frame buffers
- lavender: wlan: Relax WiFi re-association RSSI
- lavender: Add overlay for masking the notch
- lavender: Add Notch Bar Killer overlay
- lavender : update coral build fingerprint
- CTS pass without magick
- Add support for 240FPS 1/8 slow-motion
- Fixed Offline charging animation.
- L1 working fully.
- Limit screen recorder's framerate to 60fps 

# Version v16.7 kernel 4.4 (31-07-2021)

- Initial Android 11 Release
- SELinux Status: enfocing + user 

# Version 15.0 kernel 4.19 (26-03-2021)
# General:
* Add Gboard in Vanilla build
* Adding XiaomiParts, XiaomiDoze and Dirac into the whitelist
* Add support for 240FPS 1/8 slow-motion
* Define ro.media.recorder-max-base-layer-fps
* Disable WLAN Firmware loggings
* Enable iorapd
* Introduce 'SafailNet'
* Improve ram management
* Switch to AIDL Power HAL Pixels
* Switch to AOSP surfaceflinger
* Use clang 12.0.3
* Update qti-telephony-common from nubia 
* Update GPS from LA.UM.9.1.r1-06700-SMxxx0.0
* Update rootdir from LA.UM.9.2.1.r1-06000-sdm660.0
* Update media codecs from LA.UM.9.2.1.r1-06000-sdm660.0 
* Update wifi configs from LA.UM.9.2.1.r1-06000-sdm660.0 
* Update fingerprint to Redfin - RQ2A.210305.006 (cts passed without magisk)
* Update Mystic Kernel to R2.6 4.19.182
* Permissive build

# Fix
* Fix Hostpot

# Bug
* WFD

# XiaomiParts:
* Updates XiaomiParts to version 5.0
* Drop Game turbo and Spectrum ( All those settings don't work well in SDM660, and it was causing poor performance).
* The main menu has been organized so that the order of the settings is cooler.
* Add XiaomiDoze and Tile launcher
* Add dynamic thermal profile implementation
* Updated some icons
* Increase BootReceiver priority (Settings will be restored faster at startup).
* Smart Charging: Nodes reverted to charging_enabled (input_suspend It wasn't working well)

# Credits:
* Thanks @Golpiista, for tests!
* Thanks @okta10 for kernel!

# Notes for 4.19:
* FDE build
* USE Ofox latest
* installation standard equal 4.4
* format data is necessary, of course

# Version 15.0 kernel 4.4 (26-03-2021)
# General:
* Adding XiaomiParts, XiaomiDoze and Dirac into the whitelist
* Add support for 240FPS 1/8 slow-motion
* Define ro.media.recorder-max-base-layer-fps
* Disable WLAN Firmware loggings
* Drop non-functional soundtrigger
* Enforcing build
* Enable iorapd
* Enable Seamless Transfer
* Loosen up charging thermal throttling thresholds
* Set permission for spidev7.1 IR node
* Switch to EAS
* Switch to AIDL Power HAL Pixels
* Switch to AOSP surfaceflinger
* Pixelize settings more
* Update Nexus Kernel to V3 4.4.262
* Update fingerprint to Redfin - RQ2A.210305.006 (cts passed without magisk)
* Use msm8998 hals R
* Netflix the back L3

# Fix
* Fix WFD Cast
* Fix double tap always wake

# Apps: 
* Add Gboard in Vanilla build

# Blobs: 
* import Hotword Enrollment blobs
* Add qrtr blobs
* Update blobs from LA.UM.8.2.r1-07400-sdm660.0
* Update perfd-client blobs from LA.UM.9.6.2.r1-03300-89xx.0
* Update WFD blobs from LA.UM.9.6.2.r1-03300-89xx.0
* Update libsdmcolor.so from LA.UM.8.2.r1-07500-sdm660.0
* Update permissions Vulkan 1.1.128 (5.5)
* Update mi sound from ginkgo MIUI V12.0.1.0.RCOCNXM
* Update thermal/widevine blobs from jasmine V11.0.19.0.QDIMIXM
* Downgrade LA.UM.9.6.2.r1 revision to 03300-89xx.0 to fix WFD "Cast"
* Downgrade GPS blobs and hals to LA.UM.9.6.2.r1-03300-89xx.0 to fix GPS navigation

# XiaomiParts: 
* Updates XiaomiParts to version 5.0
* Drop Game turbo and Spectrum ( All those settings don't work well in SDM660, and it was causing poor performance).
* The main menu has been organized so that the order of the settings is cooler.
* Add XiaomiDoze and Tile launcher
* Add dynamic thermal profile implementation
* Updated some icons
* Increase BootReceiver priority (Settings will be restored faster at startup).
* Smart Charging: Nodes reverted to charging_enabled (input_suspend It wasn't working well)

# Credits:
* Thanks @Golpiista, @ueeel for tests!
* Thanks @NotZeetaa for kernel!
