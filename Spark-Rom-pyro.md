![Lines of code](https://img.shields.io/badge/Update%20Status-Active-2D8E00)

# Device Changelog

## 29-September-2023 (v13.8)
- Fixed occasional notification sync & internet connectivity issues on Google Play Store, Google Play Services and its components
- Misc. fixes and optimizations
- NB: Dirty flashable over 13.7 build otherwise Clean flash is mandatory

## 31-August-2023 (v13.7)
- Added lineage charging control
- Some minor fixes and improvements

## 30-May-2023 (v13.6)
- Fixed ViLTE or Carrier video calling
- Addressed several sepolicy denials
- Replaced Always On Display by Ambient Mode
- Rollback to acdbdata from vince-user-8.1.0-OPM1.171019.019-V11.0.2.0.OEGMIXM-release-keys
- Rollback to ADSP blobs & ADSP modules from daisy-user 10 QKQ1.191002.002 V11.0.21.0.QDLMIXM release-keys
- Removed useless audio blobs
- Optimized dalvik heap configs
- Disabled combined quicksettings headers due to lag while qs pulldown
- Added back libllvm-qcom graphics blobs for proper vulkan API support
- kernel: Enhanced charging speed
- kernel: Scheduler improvements
- kernel: Overclocked GPU to 725MHz like darkages kernel (CPU speed remains same)
- kernel: Fixed issues with magisk 26.1 compatibility

## 25-March-2023 (v13.5.5)
- Update perf stack from LA.VENDOR.1.0.r1-16000-WAIPIO.QSSI13.0
- Camera improvements
- Fixed Chrome remote debugging
- Added Pocket Mode support
- Back to skiaglthreaded
- Set ZRAM Size to 1GB
- Increase swappiness to 110

## 25-Feb-2023 (v13.5)
- Switched to Revamped FMRadio (credits: iusmac)
- Improved headset and earpiece volume a lil bit.
- Increased call volume steps to 15.
- And some miscellaneous fixes.

## 15-Jan-2023 (v13.4 Hotfix)
- Fixed keyguard statusbar overlapping on Quick settings.
- Fixed Privacy indicator dot spacing.
- Removed BATTERY_CHARGING_CTL from thermal-engine.conf

## 14-Jan-2023 (v13.4)
- Fixed no 2G/GSM option in Preferred Network Types.
- Fixed Android Auto in GApps builds.
- Removed unwanted graphics props.
- Improved overall smootheness.

## 05-Jan-2023 (v13.3)
- Added Non-Root ViPER4Android FX audio equalizer (means works without root).
- Addressed some camera denials.
- Improved wifi connection stability.
- Fixed 5GHz Hotspot.
- Fixed mic in discord and other voip apps.
- Fixed vulkan API support.
- Fixed Bootanimation lag.

## 16-Nov-2022 (v13.2 Hotfix)
- Fixed freezing issues in some cases.
- Tuned surfaceflinger props for smoothness and better response.
- Fixed notification delay in some apps.

## 15-Nov-2022 (v13.2)
- Unitrix kernel 4.9.333
- Updated Display/Graphics stack from LA.UM.10.6.2.r1-01600-89xx.0.
- Updated Audio, Display, Media HALs from LA.UM.10.6.2.r1-02500-89xx.0.
- Updated Carrier configuration from LA.UM.10.6.2.r1-02500-89xx.0.
- Switched to Stock MIUI v11.0.2.0 Build fingerprint.
- Fixed excessive battery drain.
- Fixed stuttering while app launch in launcher3.
- Fixed Bluetooth Device name space breakage.
- Disabled skia tracing record.
- Disabled GPU intensive UI effects for all.
- Enabled QS System info.
- Enabled Memory usage in App info.
- Switched to AIDL DRM services.
- Silenced several logspams.
- More display rounded corner.

## 12-Oct-2022 (v13.1)
- Unitrix 4.9.330.
- Fixed mobile data for Non-Indian Users.
- Fixed mobile data in sim2.
- Fixed no ringtone in BT headset.
- Fixed Display rounded corners.
- Switched Audio HAL to V7.
- Improved wifi scan.

## 13-Sep-2022 (v13.0)
- Initial A13 Release
