# Redmi Note 4x Mido

## Corvus v16.8
- Fixed Audio while calling & earphone stuff
- Fixed some apps detecting root/safteynet bug
- Fixed boot scripts [will improve boot speed]
- Fixed some permissions
- Fixed iorap [increases app launch speed]
- Added new audio flags from caf
- Added back calender provider [will fix calender app crashing]
- Added bromite browser
- Added exactcalculator [aosp calculator]
- Updated audio policy
- Updated powerhint
- Updated august redfin FP
- Decrease aod brightness to 0
- Reset back to stock thermals

## Corvus v16.7
- Fixed fps monitor
- Fixed crackling sound issue
- Fixed HW keys and Gestures both working at same time 
- Fixed some fpsmon and thermal engine sepolicy
- Added AOSP calculator
- Added july FP from redfin
- Added Latest sleepy kernel by shashank1436
- Added Latest sleepy thermals by shashank1436
- Added latest caf powerhint
- Added back clock [Unfortunately it was removed in last update]
- Dropped bogus tombstone dir at bootup [This are debug stuff]
- Dropped depreciated Bluetooth stuff
- Dropped default BFQ flag
- Dropped audio-app cpuset [Depreciated]
- Dropped/disabled vsync for cpu rendred apps
- Updated all propiertary blobs from caf
- Updated latest hals by smokey18
- Updated simplekeyboard to 5.3
- Updated Bromite webview
- Reduced screen off delay time to 0ms

## Corvus v8.5

- Removed dolby audio
- Fixed burn in issue in tianma and boe display with optimum value. (not 237, :-p )
  So no need to use any kcal things anymore :-) 
- Fixed smart charging finally
- Added prebuilt YMusic
- Xiaomiparts: Spectrum: Fixed gaming profile gpu lock, and ardenoboost mismatch
- Xiaomiparts: Spectrum: Removed performance profile and introduced stock profile. Enjoy less heating :-)
- Xiaomiparts: Spectrum: Made battery and ultra battery more effecient. 
- Import missing library (libspl.so)
- Removed some leftover 4.9 kernel stuffs
- Build sqlite3
- Rounder  corner in Gboard and no navbar spacing 
- Enable VOLTE for Bangladesh(All networks), Vietnam(Mobifone, Viettel), Indonesia(Telkomsel)
- Support ViLTE for carrier Smartfren (Indonesia)
- Added live display
- Advanced power menu = turned on and 
  Screenshot on power botton =turn off  by default (need to go once in ravens lair>powermenu to work :-p)
- Used Pixel 4 cpusets config
- Charging increased upto 7 degee celcious than stock one (extra 2'C than v8.0)
- Used more cores for faster app installation
- Blacklist google hotword service
- Add "Built-In (Back) Mic" to "primary input" sink
- XiaomiParts: fix Vibration strength reset to default after reboot
- Add HDR in HAL3
- Build missing camera library
- Shorten shutdown time
- Allow QfingerprintService to run in power save
- Allocate enough buffer for HDR snapshot
- Wifi Bonding For 2.4ghz band
- Smarter decisions on whether to use a 2GHz or 5Ghz AP
- Update qti-whitelist.xml from LA.UM.8.6.r1-04700-89xx.0
- Update privapp-permission-qti from LA.UM.8.6.r1-04700-89xx.0
- Made the UI smoother
- Update Vulkan hardware level supported to 1

Special thanks to Kingsman44 brother and all the devs,testers & users who helped me for these changelogs <3

## Corvus V8.0

- Changed default kernel to PureCAFx (3.18.140), thanks to  Rafi brother. 
- Xiaomiparts: Aded MSM thermal control,cpu and VDD control
- Updated thremal throttle
- Fixed default sms SIM reset after reboot
- Initial tuning for EAS
- Enable fluence for audio/voice recording
- Fixed display wake up
- Opt-out ringtone audio focus for Wired/BT headset
- Aded Dolby Audio
- Added call recording overlay
- Changed default screen recorder to kimci recorder
- Improved scrolling responsiveness
- Added back AOD
- Tweak for better memory management
- Update auto/screen brightness overlay from Daisy
- Update factory version to v2.1
- Build libvulkan
- Enable API override for mm-qcamera-daemon
- Update Dalvik heap configuration from AOSP 10
- Drop snap overlay and support for bokeh mode
- Allow all apps to use smart replies
- XiaomiParts: TouchBoost Improvements
- XiaomiParts: Separate Yellow and White Torch Brightness
- Compile HWUI for Better Performance
- Adding Google AR Support
- XiaomiParts: Removed all non working stuff
- wifi: Reduce battery drain
- Used Pixel Charging Animation
- Enable config_hspa_data_distinguishable and max visible
 notification 6
- Pin critical system apps that always need 
- Increase JPEG Quality
- Set virtual displays to 0
- Fix lockscreen charging stats
- Allow 120fps video recording
- Fast charging limit by 5°C than stock one
- Xiaomiparts: Optimized spectrum balance, gaming, performance and Ultra Battery profile for PureCAFx.
- Update GPU driver to  OpenGL-V@474.0 and Vulkan 1.1.128 drivers
- Update Charger, qti-telephony, IMS, Performance stack and many more
- Probably dirty flash will not remove retro music player
- Fixed Dirac, added in both xiamiparts and sound section. :-D

## Corvus v7.5

- Initial build
- Clean Flash Recommended 
- Changed default kernel to Notkernel (thanks to @dracarys_18)
- Kcal now working out of the box
- 3.18 based Kernel so enjoy your IR blaster LMAO
- Added ultra battery saving option in qs tiles
- Fixed Battery capacity unavailable
- Added face unlock cause its now official
- Fixed smart charging
- Corvus parts nuked from rom source so added XiaomiParts
- Use Custom Cernel i.e. Ethereal or your fav one if spectrum seems not working
