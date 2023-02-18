# ROM Installation Instructions for vince

## Clean flash (Coming from a different ROM)
- Download ROM.
- Download Gapps Package if ROM is Vanilla (Recommend to use either Nikgapps core/basic or Mindthegapps).
- `Note: On GApps ROM variant Google Apps are included, don't flash separately.`
- Reboot to Recovery (**You must use any of the recommended recovery. See Useful Links section**).
- Wipe System, Data, Vendor, Cache, Dalvik/ART cache.
- `Note: If you are coming from MIUI or any encrypted ROM, Format data to remove encryption. Otherwise new ROM won't boot.`
- **Flash latest stable Firmware (Highly recommended to flash any of the latest stable firmware before flashing ROM. See Useful Links section)**
- Flash ROM zip.
- Flash Gapps Package if ROM is Vanilla.
- Reboot to system.
- **To get root access, Reboot to recovery after ROM setup and flash Magisk.**

## Dirty flash (Updating to a newer build)
- Do not wipe anything.
- Flash new ROM zip.
- **Flash the same GApps Package again you flashed before (for vanilla users).**
- Flash Magisk again if you are rooted before.
- **Wipe Cache and Dalvik/ART cache.**
- Reboot to system.

## Useful Links
- **Recommended Recoveries:**
  * <a href="https://github.com/starlight5234/android_device_xiaomi_vince-twrp/releases/download/r1/recovery.img" target="blank">TWRP by Starlight</a>
  * <a href="https://archive.orangefox.download/OrangeFox-Beta/vince/OrangeFox-R11.0_0-Beta-vince.zip" target="blank">Orangefox R11.0 Beta</a>

- **Recommended Custom GApps Packages:**
  * <a href="https://nikgapps.com/" target="blank">Nikgapps</a>
  * <a href="http://downloads.codefi.re/jdcteam/javelinanddart/gapps" target="blank">Mindthegapps</a> (Use arm64 only)

- <a href="https://andi34.github.io/faq/faq_twrp.html" target="blank">**How to Format Data using recovery?**</a>
- <a href="https://xiaomifirmwareupdater.com/firmware/vince/" target="blank">**Latest Stable Firmware**</a>
- <a href="https://github.com/topjohnwu/Magisk/releases" target="blank">**Magisk Releases**</a>
