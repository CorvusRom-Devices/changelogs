# CorvusOS Changelog                                                                   
                                                                                       
## v12.0 (2020.12.15)

- Bump to Beta v12.0-Athrill
- Merged Tag r21 i.e December Security Patch

** Additions to the features

- Raven Themes brings some colors to the family as the themes are back :)
- Added Accent Picker to themes
- Added Icon Shapes
- Added Statusbar/QS Icons
- Added QS Header Style
- Added Switch Styles
- Added System Themes (Corvus clear, Material Ocean, Choco x, etc)
- Added Navbar Styles
- BringBack our Raven Launcher with app lock and various features
- Added New Gaming Macro Mode
- Added Media Art Blur Level
- Added Visualizer Feature
- Added Lockscreen Media Art Filter
- Added Toggle to disable charging animations
- Added KG Charging Animations
- Added Incall Vibrations Options
- Added Haptic Feedback to QS Tiles
- Added Fingerprint Vibration Authentication
- Added Battery Style Customizations (Solid, Circle, Dotted Circle, etc)
- Added various VoLTE Icons
- Added VoWifi Icons
- Added Battery Light Customizations
- Added option to enable/disable screenshot sounds
- Added options for QS Brightness Slider Positions
- Added toggle to hide auto brightness button from QS slider
- Added showing bottom brightness slider above QS footer
- Added toggle for QS Media Player
- Added Statusbar Clock n Date customizations
- Added StatusbarClock date right/left position options
- Added QS Header data usage info
- Added ability to show daily/monthly data usage
- Added hiding notification headers options
- Added Center Notification headers
- Added Theme settings dashboard icons
- Enabled dark theme by default
- Added and Updated various APNs from LineageOS
- Added CM Screen Security settings
- Added a new Ginto Font
- Added Corvus version and build date in Settings
- Added vector icons to battery preference screen
- Added Developer options toast insulter
- Added simple maintainer string
- Added Reset battery stats options
- Added Add drawable for Private DNS
- Added vendor.qti.hardware.capabilityconfigstore@1.0 HAL

** Some Fixes and Improvements
- Fixed FOD completely
- FODCircleView: Enabled hardware acceleration
- Fod: Aod content should move only in Y
- Granted Permissions to various apps
- Fixed volume rocker skip a track on Ambient Display and Lift to Wake
- Enabled smart replies for apps that target APIs lower than 28
- Added support for lc3 codec
- Improvements for swipe to screenshot
- SwipeToScreenshot: Imported MIUI implementation
- Added options to show app icon on system text toasts as well
- Fixed screenshot not showing in power menu after r15 merge
- Toast: Set default activity icon if app not found
- Added method for getting estimated battery time
- Added delete action chip intent
- Reduced System Icon paddings
- Added method to check for both wifi and mobile connections
- Flashlight toggle api improvements
- Added a switch for vpn, data saver, and roaming icons
- Added options to allow devices to specify their own pickup sensor type
- Disabled 3 columns in landscape
- Added Signature Spoofing
- Upreved Wifi HAL to 1.4
- Wifi: Added 802.11ax support to RTT
- Wifi: Added 6GHz bands to WifiBand
- Wifi: Added 6GHz band to NAN structures and methods
- Added IWifiApIface@1.4 (configurable MAC address)
- wifi: Added provision to create/delete dynamic interface(s)
- Wifi: Added support for mapping DSCP to Wifi AC
- Added new lazy wifi HAL target
- Added IWifi 1.3 and 1.4 as interfaces provided by vendor.wifi_hal_legacy.
- Added vintf_fragments to android.hardware.usb@1.0-service.basic
- Converted corvus product variables to soong config variables
- Removed aosp battery percentage option
More detailed optimizations and fixes check here

Please note:-
- Official builds will be signed zips from now so some specific instructions will be granted from next release if dirty flashing from this build.
- The features and updates from v12.0 will be specifically for official devices.
- We are in Beta Stage so please expect some minor bugs and report to the maintainer accordingly..