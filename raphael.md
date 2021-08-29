** v16.8-Avalon OSS Vendor Changelogs **
- Completely swithced to New a11 FW tree
- Added missing WFD blobs
- Import mi_thermald missing permissions
- Enabled coral vibration configuration
- Added config to exclude haptics devices from input subsystem
- Synced power_profile.xml from V12.5.2.0.RFKMIXM
- enabled unspecialized app process pool
- Added zram config
- Updateed clear speaker audio from MIUI 12
- Added headphones warning for clear speaker
- Enable subtle tick vibration when revealing shelf
- Defaulted to full gesture navigation
- overlay: adjusted window rounded corners

** v16.8-Avalon Miui Vendor Changelogs **
- Updated power profile
- overlay: Hide unsupported color effects entry of Snap
- overlay: Added Snap overlay
- Enabled aux camera for Snap
- whitelisted ANX for size stream skip
- Updated clear speaker audio from MIUI 12
- Added headphones warning for clear speaker
- Enable subtle tick vibration when revealing shelf
- Defaulted to full gesture navigation
- overlay: adjusted window rounded corners

** v16.7-Obsidian Miui Vendor Changelogs **
- Updated and remove pinner services for R
- Updated path for pinner services
- Removes unneeded FodZOrder value - Fixes random flickering in different situations like when DC-Dimming on & using low brightness
- Enable fluence voice recording - Fixed google voice recorder
- Import qdcm_calib_data from Miui Q
- Restored old panel configuration - Fixes yellow tint on boot
- Tuned ime padding
- Restored the LED's previous state after popup cam
- Disabled hifi preference when toggling switchbar
- parts: Directly takeback the motor if it's not closed on create
- Added ability to Quickly takeback the motor in free fall
- Disabled popup camera sound by default
- Updated Hotword permissions & import necessary blobs
- Imported audio_policy_configuration.xml from Miui Q
- Disabled ULL mode
- Added hotword input for hotword mic concurrency
- Made FOD background completely transparent
- Used LOS like default FOD icon
- Updated fingerprint for Indian variant

** v16.7-Obsidian OSS Vendor Changelogs **
- Initial OSS Build
- Updated Blobs from latest raphael-user 11 RKQ1.200826.002 21.6.30
- Whitelisted ANX for size stream skip
- Imported lights HAL from Xiaomi msm8998-common
- Added new miui offline charging daemon from cmi R


** v16.5-Alpha-Centauri Miui Vendor Changelogs **
- Fixed all Bluetooth issues

** v16.0-Alpha-Centauri Miui Vendor Changelogs **
- Switched to Enforcing User build
- Added battery health support again (since last release)
- Fixed smart charging
- Added Pixel offline charging animation
- Disabled LiveDisplay
- rootdir: Allowed all filesystems for USB-OTG
- Updated fstab entry to auto mount USB storage devices for msmnile
- Added metadata mount command in recovery fstab since partition should be wiped during recovery process
- Added 'check' flag for metadata partition
- Enabled usage of dex2oat64
- Configured SQLite to operate in MEMORY mode
- bluetooth: Disable clean turn on
- Adjusted dex2oat thread count after setup wizard
- Improved values for lockscreen charging info
- Enabled Fast bss transition config
- Enable minimum confirmation duration for sending network score to connectivity service
- Wifi - Extend config_wifi_framework_recovery_timeout_delay to 3 seconds
- Wifi: Disabled WPA2 to WPA3 auto-upgrade in P18 and P19 devices
- Removed PRODUCT_AAPT config
- Added kpti=off to boot command line
- Fixed thermal/touchscreen profiles not getting restored after turning screen back on
- parts: Improved strings for game mode
- parts: Display icon beside thermal profiles
- Updated Thermal Profiles drawable icons
- disabled soundtrigger via vendor overlay
- WifiOverlay: Updated from CAF tag LA.UM.9.1.r1-09100-SMxxx0.0
- org.ifaa.android.manager: Access mlipay hal via a binder service
- overlay: Add regulatory info label
- FaceUnlockService: Define delay for our popup camera
- overlay: Improved face unlock for popup camera
- Dirac: Added bass booster preset
- parts: Implemented Clear Speaker
- parts: Increaseed BootCompletedReceiver priority
- Enabled Seamless Transfer
- set TARGET_INPUTDISPATCHER_SKIP_EVENT_KEY to 338
- fod: drop \n from logs
- Updated SELinux boot error
- Disabled WiFi Aware feature
- Enable freeform window management
- Bluetooth: Swithced to AOSP bluetooth

** v14.5-Mutate Miui Vendor Changelogs **
- Fixed FOD Flickers
- Moar FOD Improvements

** v14.0-Ruinous Miui Vendor Changelogs **
- Updated redfin build fingerprint to Feb 2021
- Removed ANX Prebuilt cam
Note:- Smart charging and Live Display is turned off untill its working properly

** v13.0-Exalted Miui Vendor Changelogs **
- Enforcing now
- Fixed keyguard bottom margin
- Disabled FOD icon dimming
- Enabled Proximity check on wake
- Fixed spacing between keyboard and navbar
- Bumped minimum vendor variant for IN
- Added telephony-ext to boot jars
- init: set device model for different variants
- Switched to standalone extract utils
- Updateed redfin fingerprint to Jan 2021
- Used CodeAurora ImsService implementation for RCS

** vAndroid-10 OSS and Miui Vendor Changelogs **
- Updated Build FP to Redfin December Security Patch
- Added Screen Off FOD in Miui Vendor Builds

** v12.0-Athrill Miui Vendor Changelogs **
- Update Fingerprint to Redfin December Security Patch
- Inlined ANX v185
- Added Battery Health Support
- Fixed Device Controls
- Added Maintainer name in Settings> About Section


** v11.0-Spooky Miui Vendor Changelogs **
- Update Fingerprint To Coral's November Security Patch
- Added perms of hotword blobs
- Updated signature of hotword apk
- Fixed CTS.. Safetynet passes without magisk
- Selinux is permissive


** v9.0-EndGame OSS Changelogs **
- bump to september coral build fp
- Updated graphics blobs to LA.UM.8.1.r1-15600-sm8150.0
- Granted rw permission to hgsl node
- Override config for platform number verification
- Added permissions for RCS service
- Added net_raw permissions for time_daemon service
- Filtered out the conference host in the CEP for some carriers
- Added new config overlay for call composer
- Imported headset jack layout
- Fixed mic issues in apps like WhatsApp

** v9.0-EndGame Miui Vendor Changelogs **
Same as v8.5

** V8.5-Sage Miui Vendor Changelogs **
- bluetooth: Enabled WBS
- Removed legacy firmware directories
- Disabled VSync for CPU rendered apps
- Disabled hifi preference when toggling switchbar
- Enabled back button on thermal activity
- Adjust window rounded corners
- Adjust statusbar height
- Added screen off FOD

** V8.5-Sage OSS Vendor Changelogs **
- Inlined Latest Immensity
- Added pixel walls
