# ROM Installation Instructions for vince

## Clean flash (Coming from a different ROM)
- Download ROM.
- Download Gapps Package if ROM is Vanilla (Recommend to use either Nikgapps core/basic or Mindthegapps).
- `Note: On GApps ROM variant Google Apps are included, don't flash separately.`
- Reboot to Recovery (**You must use any of the recommended recovery. See Useful Links section**).
- Wipe System, Data, Vendor, Cache, Dalvik/ART cache.
- **Make sure you are on the latest firmware or just flash latest stable firmware (v11.0.3.0) before flashing ROM (See Useful Links section)**
- Flash ROM zip.
- Flash Gapps Package if ROM is Vanilla.
- Reboot to system.
- `Note: If you are coming from MIUI or any ROM which had ENCRYPTION, FORMAT DATA to remove encryption. Otherwise new ROM won't boot (See useful links section to know about Formatting data via recovery).`
- **To get root access, Reboot to recovery after ROM setup and flash Magisk.zip**

## Dirty flash (Updating to a newer build)
- Do not wipe anything.
- Flash new/update ROM zip.
- **Flash the same GApps Package again you flashed before (for vanilla users).**
- Flash Magisk again if you are rooted before.
- **Wipe Cache and Dalvik/ART cache.**
- Reboot to system.

## Useful Links
- **Recommended Recoveries:**
  * <a href="https://github.com/starlight5234/android_device_xiaomi_vince-twrp/releases/download/r1/recovery.img" target="blank">**TWRP by starlight5234**</a>
  * <a href="https://archive.orangefox.download/OrangeFox-Beta/vince/OrangeFox-R11.0_0-Beta-vince.zip" target="blank">**Orangefox R11.0 Beta**</a>

- **Recommended Custom GApps Packages:**
  * <a href="https://nikgapps.com/" target="blank">**Nikgapps**</a>
  * <a href="http://downloads.codefi.re/jdcteam/javelinanddart/gapps" target="blank">**Mindthegapps**</a> (Use arm64 only)

- **About FORMAT DATA:**
  * **Things to keep in mind before format:** Formatting your phone will wipe all the data. This data includes photos, videos, documents, applications, games, call logs etc. That's why you should make sure to have a backup before format. You can copy your necessary files on a pendrive, sdcard, PC and also can save large media files on cloud storage like Google Drive or OneDrive. Restoring your data from this backup is easy.
  * <a href="https://youtu.be/tkdmKkAhgAs" target="blank">**How to Format Data using TWRP Recovery?**</a>
  * <a href="https://youtu.be/aEehSo3ZcZ0" target="blank">**How to Format Data using Orangefox Recovery?**</a>
  * <a href="https://youtube.com/shorts/2MruTGWgj_I?feature=share" target="blank">**What is the difference between WIPE DATA and FORMAT DATA?**</a>

- **Other Links:**
  * <a href="https://xiaomifirmwareupdater.com/firmware/vince/" target="blank">**Latest Stable Firmware**</a>
  * <a href="https://github.com/topjohnwu/Magisk/releases" target="blank">**Magisk Releases**</a>
