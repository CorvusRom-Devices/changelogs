## LG V50 ThinQ

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
