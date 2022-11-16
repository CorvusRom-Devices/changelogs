## LG V50 ThinQ

## Corvus v5.1-DejaVu Changelog
- Initial A13 build
- Change to use Aperture instead of gcam. Aux cams are supported
- Switch to AOSP bt stack
- Fix AOD screen not updated
- Dragon kernel upstream to 4.14.299

--Notes--
- Vanilla build is dropped from now on.
- Screen Resolution setting doesn't work. Please don't use it. This will be hidden in next build.

## Corvus v4.1-Eclipse Changelog
- Drop Screen Resolution Changer (This feature is not stable. We will re-add it in A13 builds)
- Add config for Battery Stats
- Move volume panel to left side by default
- Fix screen on / off animation to correct power button position
- Fix Youtube shorts issue
- Use WeebX clang 15 for kernel instead off GCC
- Dragon kernel upstream to 4.14.295
- Switch back to zram and disable Simple LMK due to bad memory management in 4.0

--Notes--
- Vanilla build may have some issues: Current app is closed due to coming message, phone call (AOSP dialer, messages), App info crashing. I don't recommend to use vanilla build.
- 

## Corvus v4.0-Leviathan Changelog
- Include BSG Gcam v8.1
- Implement KProfiles to manage profiles in terms of battery backup and performance
- Implement Screen Resolution Changer
- Add Smart Charging support
- Dragon kernel upstream to 4.14.290
- Bunch of improvements in kernel, e.g. overclock GPU, replace zram with swap, add kcal, wakelock control ...
- Update Adreno driver to 530.
- Some improvements in device trees

--Notes--
- Don't flash other Adreno driver like v614 or v615. It may make your phone not boot
- There maybe video call issues. This happens on our rom and other roms as well. Please provide the logs if you encounter it.

## Corvus v3.2-Vindicate Changelog
- Very first official Corvus A12 build for LG V50 ThinQ
- June security patch merged
- Dragon kernel upstream to 4.14.287
- Update A12 blobs
- Some improvements in device trees and kernel

--Notes--
- I recommend to flash LGE A12 firmware first (optional)
- Flash TWRP if you need to flash Gapps or Magisk (optional)
- You may encounter Youtube video stuttered due to sound_trigger crashing issue. If so, disable Hey Google and the issue will be fixed.
