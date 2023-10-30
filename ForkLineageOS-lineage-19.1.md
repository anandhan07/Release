![Lines of code](https://img.shields.io/badge/Update%20Status-Discontinued-C61A09)

# Build Date: 05-Oct-2022

## Device Changelog
- Unitrix Kernel 4.9.330
- Updated GrapheneOSCamera to v.51
- Switched Audio Hal to V7
- Added Smart Charging
- Switched to AOSP Health.
- Wifi scan improvements.
- Dropped redundant zram writeback.
- Set 50% zram of the total RAM.
- Set swappiness to 60.
- Tweaked dalvik props for 3GB & 4GB variants properly and moved it into libinit.
- GPS accuracy improvements.
- Perfd blob fixes.
- Reduced UI lag while screenrecording.
- Tuned surfaceflinger duration props for better performance.
- Optimized system performance and improved stability.

## Source Changelog
- September Security Patch merged
- Lineage upstream

# Build Date: 23-July-2022

## Device Changelog
- Unitrix Kernel 4.9.324.
- Bump to July raven fp.
- Updated GrapheneOSCamera to v.44
- Updated audio configs from LA.UM.9.6.2.r1-04800-89xx.0 and adapted vince changes.
- Removed obsolete mixer_paths.xml.
- Improved loudspeaker & headphones volume.
- Imported missing ACDB's from tissot.
- Fixed mic related issues for some social media apps.
- Fixed battery drain and overheating due to gms service.
- Fixed thermal-engine regression on certain cases.
- Updated CarrierConfig from LA.UM.10.6.2.r1-02200-89xx.0.
- Fixed the issue that removing 'zero' from mcc and mnc values in CarrierConfig.
- Optimized dalvik for smooth app operations.
- Moved surfaceflinger props to system/build.prop
- Dropped triple frame buffers.
- Removed IORapd, trim & bservice properties.
- Improved RAM management.
- Added a temporary workaround for Dual SIM VoLTE configuration switch (ie you no longer need to reboot, just toggle Airplane Mode on and off after 'switch data card' tile in qs).
- Updated CNE, DPM, QMI, Telephony stack, WiFi, Time services, Power-off alarm, Peripheral manager blobs from LA.UM.9.6.3.r1-06200-89xx.0.
- Updated FMRadio blobs from LA.UM.9.6.3.r1-04400-89xx.0.
- Updated DRM + Widevine from Coral.
- Dropped redundant blobs.
- Lots of init fixes.
- Optimized system performance and improved stability.

## Source Changelog
- July Security Patch merged
- Updated smartspace from qpr3
- Lineage upstream

# Build Date: 27-May-2022

- Hotfix Update.
- Fixed an issue that LOS recovery replacing currently installed recovery for some users.
- Removed "Update Lineage Recovery" Option from SetupWizard.
- Fixed high battery drain in some cases.
- Build with Grapheneos camera.

# Build Date: 23-May-2022

## Device Changelog
- Initial android 12.1 release.
- Unitrix 4.9.315 by default.
- Synced with latest fork lineage source.

## Source Changelog
- May Security Patch merged
- Fixed laggy Quick settings
- Fixed location indicator glitch in QS
- Removed VoLTE and VoWIfi icons
- Added launcher3 from crdroid in vanilla build
- Added back smart charging
- Hotspot client manager and hidden ssid settings
- Added settings to block annoying signal strength icon
- Implement cutout force full screen
- Added back Dash Charging/VOOC/Warp/Turbo Charging support
- Lineage upstream
