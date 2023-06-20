<h1 align="center">ROM Flashing instructions for vince</h1>

:warning: **WARNING**: This is a general flashing instructions for all android versions. But for Android 13; if you are coming from a stock/custom MIUI or any custom ROM on android version 9, 10, 11, 12 do a **FORMAT DATA** after clean flashing any Android 13 ROM to avoid bootloop, stuck at MI logo & Recovery logo (Refer Useful links section to know more about how to format data via recovery).</br>
Read the guide carefully and follow all instructions. Happy flashing... 😉

## :star: Clean flash (Coming from another ROM or If you want a fresh start)
1. Download ROM
2. Download Custom Google Apps Package (Like Nikgapps core/basic or Mindthegapps) if the ROM is Vanilla variant

- **NOTE: On GApps ROM variant Google Apps are included, don't flash a separate Custom Google Apps package.**

3. Reboot to Recovery **(You must use any of the recommended recovery. Refer Useful Links section)**
4. Wipe System, Data, Vendor, Cache, Dalvik/ART cache partitions
5. **Flash latest stable firmware v11.0.2.0 or v11.0.3.0 before flashing ROM** (Refer Useful Links section)
6. Flash ROM zip
7. Flash Custom Google Apps Package if the ROM is Vanilla variant
8. Reboot to system

:hammer_and_wrench: To get root access, Reboot to recovery after ROM setup and flash Magisk.zip

## :star: Dirty flash (Updating to a newer build)
1. Download the new update ROM zip
2. Reboot to recovery
3. Do not wipe anything
4. Flash the new update ROM zip

- Flash the same Custom Google Apps Package again you flashed before **(For vanilla users)**
- Flash Magisk again if you are rooted before **(For rooted users)**

5. Wipe Cache and Dalvik/ART cache
6. Reboot to system

## :globe_with_meridians: Useful Links
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
