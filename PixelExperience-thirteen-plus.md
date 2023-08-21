![Lines of code](https://img.shields.io/badge/Update%20Status-Active-orange)

# Changelog

## 21-Aug-2023
- Merged August security patch (<a href="https://blog.pixelexperience.org/2023/08/august-awakens-security-updates-optimization-fixes-and-sneak-peeks/" target="blank">**Read PixelExperience Blog**</a>)
- Adress UI lags
- Some minor fixes and improvements

## 06-Aug-2023
- Merged July security patch (<a href="https://blog.pixelexperience.org/2023/07/july-update-is-there/" target="blank">**Read PixelExperience Blog**</a>)
- Some minor fixes and improvements

## 13-May-2023
- Merged May security patch (<a href="https://blog.pixelexperience.org/2023/05/quick-may-update/" target="blank">**Read PixelExperience Blog**</a>)
- Fixed annoying beep sound in earpiece while incall-handset mode
- Optimized dalvik heap configs (Don't forget to wipe Dalvik/ART Cache after flashing the update)
- Disabled combined quicksettings headers (<a href="https://t.me/anandhansprojects_chat/22687?single" target="blank">**Reason**</a>)
- Added back libllvm-qcom graphics blobs for vulkan API
- Added option to Ignore window secure flags (Settings > Privacy)

#### Kernel changes:
- Removed CPU Boost in some events due to excessive battery drain
- Overclocked GPU to 725MHz like darkages kernel (CPU speed remains same)
- Fixed issues with magisk 26.1 compatibility

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
