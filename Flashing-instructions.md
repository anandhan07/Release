# ROM Flashing Instructions for vince

## Clean flash (Coming from a different ROM)
- Download ROM.
- Download Gapps Package if ROM is Vanilla (Recommend to use either Nikgapps core/basic or Mindthegapps).
> Note: On GApps ROM variant Google Apps are included, don't flash separately.
- Reboot to Recovery (**You must use any of the recommended recovery. See Recommended Recoveries in Useful Links section**).
- Wipe System, Data, Vendor, Cache, Dalvik/ART cache
- **Flash latest stable Firmware (Highly recommended to flash any of the latest stable firmware before flashing ROM. See Firmware in Useful Links section)**
- Flash ROM zip.
- Flash Gapps Package if ROM is Vanilla.
- Reboot to system.
- **To get root access, Reboot to recovery after ROM setup and flash Magisk.**

## Dirty flash (Updating to a newer build)
- Do not wipe anything.
- Flash new ROM zip.
- **Flash the same GApps Package you flashed before.**
- Flash Magisk if you are rooted before.
- Wipe Cache and Dalvik/ART cache only (optional)
- Reboot to system.

## Useful Links
- **Recommended Recoveries:**
  * TWRP (Official): https://dl.twrp.me/vince/twrp-3.7.0_12-0-vince.img.html
  * TWRP (Unofficial): https://github.com/starlight5234/android_device_xiaomi_vince-twrp/releases/download/r1/recovery.img
  * Orangefox: https://archive.orangefox.download/OrangeFox-Beta/vince/OrangeFox-R11.0_0-Beta-vince.zip

- **Latest Stable Firmware:** https://xiaomifirmwareupdater.com/firmware/vince/

- **Recommended GApps Package:**
  * Nikgapps: https://nikgapps.com/
  * Mindthegapps (Use arm64 only): http://downloads.codefi.re/jdcteam/javelinanddart/gapps

- **Magisk:** https://github.com/topjohnwu/Magisk/releases
