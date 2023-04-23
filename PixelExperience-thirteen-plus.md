![Lines of code](https://img.shields.io/badge/Update%20Status-Active-orange)

# Changelog

## 23-April-2023
- Merged April security patch (<a href="https://blog.pixelexperience.org/2023/04/april-update/" target="blank">**Read PixelExperience Blog**</a>)
- Update perf stack from LA.VENDOR.1.0.r1-16000-WAIPIO.QSSI13.0
- Fixed ViLTE or Carrier video calling
- Camera improvements
- Fixed Chrome remote debugging
- Switch to pixel offline charging animation
- Switch to zstd for zram compression algorithm
- Addressed some denials
- Replaced Always On Display by Ambient Mode
- Rollback to vince acdbdata and fixed in-call noise cancellation

#### Kernel changes:
- Using modified Unitrix kernel 4.9.337 (EOL) named as aospa-vince-inline, which includes some Nito kernel changes. Thanks to @SlightlyLookAround & @GhostMaster69-dev.
- Enhanced charging speed
- Improved unlock speed with Fingerprint and Double tap to wake
- Scheduler improvements
- Kernel-specific zstd API
- Improved memory management
- And overall performance improvement

## 23-Feb-2023
- Unitrix kernel 4.9.337 (EOL)
- Added Root-less ViPER4Android FX audio equalizer (it means works without root).
- Switched to Revamped FMRadio (credits: iusmac).
- Switched to Aperture Camera app.
- Addressed some camera sepolicy denials.
- Fixed 5GHz Hotspot.
- Fixed mic in discord and other voip apps.
- Fixed Vulkan API/Extension support.
- Fixed Bootanimation lag.
- Fixed no 2G/GSM option in Preferred Network Types.
- Fixed Android Auto.
- Fixed Personal Safety & Emergency.
- Removed unwanted graphics props.
- Fixed Privacy indicator dot spacing.
- Improved wifi connection stability.
- Improved cpulimit thermal-mitigation thresholds.
- Improved headset and earpiece volume a lil bit.
- Increased call volume steps to 15.
- Disabled FP unlock ripple animation.
- Improved overall smootheness.

## 15-Nov-2022
- Initial A13 Release
