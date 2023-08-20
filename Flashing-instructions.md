<h2 align="center">DETAILED INSTRUCTIONS TO FLASH CUSTOM ROM ON VINCE</h1>

<p align="center">This guide is applicable for android versions including 10, 11, 12, & 13</p>
<p align="center">Read the guide carefully and follow all instructions</p>
<p align="center">Happy flashing... 😉</p>

---

### :star: Clean flash from MIUI to AOSP
> 💠 Process of installing a new ROM version by completely wiping the existing System, Data, Vendor, Cache and sometimes even the internal storage of the device
0. Download AOSP ROM package & Custom Google Apps Package if the ROM is Vanilla variant (Nikgapps core/basic or Mindthegapps)

- **NOTE: On GApps ROM variant Google Apps are included, don't flash a separate Custom Google Apps package.**

1. Reboot to Recovery **(You must use any of the recommended recoveries given below)**
2. Wipe System, Data, Vendor, Cache, Dalvik/ART cache partitions
3. Format Data (Scroll down to know more)
4. Reboot to Recovery
5. **Flash latest stable firmware v11.0.2.0 or v11.0.3.0 before flashing ROM (link given below)**
6. Flash AOSP ROM zip
7. Flash Custom Google Apps Package if the ROM is Vanilla variant
8. Reboot to system

:hammer_and_wrench: To get root access, Reboot to recovery after ROM setup and flash Magisk.zip

---

### :star: Clean flash from AOSP to AOSP
0. Download ROM package zip & Custom Google Apps Package if the ROM is Vanilla variant (Nikgapps core/basic or Mindthegapps)

- **NOTE: On GApps ROM variant Google Apps are included, don't flash a separate Custom Google Apps package.**

1. Reboot to Recovery **(You must use any of the recommended recoveries given below)**
2. Wipe System, Data, Vendor, Cache, Dalvik/ART cache partitions
3. **Flash latest stable firmware v11.0.2.0 or v11.0.3.0 before flashing ROM (link given below)**
4. Flash ROM zip
5. Flash Custom Google Apps Package if the ROM is Vanilla variant
6. Reboot to system

:hammer_and_wrench: To get root access, Reboot to recovery after ROM setup and flash Magisk.zip

---

### :star: Dirty flash
> 💠 Process of installing a new version of a custom ROM over an existing installation without performing a full wipe
0. Download the new update ROM zip
1. Reboot to recovery & Do not wipe anything
2. Flash the new update ROM zip

- Flash the same Custom Google Apps Package again you flashed before **(For vanilla users)**
- Flash Magisk again if you are rooted before **(For rooted users)**

3. Wipe Cache and Dalvik/ART cache
4. Reboot to system

---

### :warning: Read this before you ran into problems such as bootloop, stuck at MI logo or Recovery logo:
Formatting data is sometimes needed for Android 13 ROMs as well. If you're coming from a stock/custom MIUI ROM or any AOSP Custom ROM which showing **"PHONE IS ENCRYPTED"**; it needs to do **FORMAT DATA in recovery** right after flashing any Android 13 ROM, Then Reboot to system. You don't need to format again for flashing another Android 13 ROM, .

**To know whether your PHONE IS ENCRYPTED or NOT:** [Go to Settings > Security > Encryption & credentials] or [Search for "encryption" in settings search]

### 🧹About FORMAT DATA:
  * **Things to keep in mind before format:** Formatting your phone will wipe all the data. This data includes photos, videos, documents, applications, games, call logs etc. That's why you should make sure to have a backup before format. You can copy your necessary files on a pendrive, sdcard, PC and also can save large media files on cloud storage like Google Drive or OneDrive. Restoring your data from this backup is easy.
  * <a href="https://youtu.be/tkdmKkAhgAs" target="blank">**How to Format Data using TWRP Recovery?**</a>
  * <a href="https://youtu.be/aEehSo3ZcZ0" target="blank">**How to Format Data using Orangefox Recovery?**</a>
  * <a href="https://youtube.com/shorts/2MruTGWgj_I?feature=share" target="blank">**What is the difference between WIPE DATA and FORMAT DATA?**</a>
 
---

### :globe_with_meridians: Some useful links
- **Recommended Recoveries:**
  * <a href="https://github.com/starlight5234/android_device_xiaomi_vince-twrp/releases/download/r1/recovery.img" target="blank">**TWRP by starlight5234**</a>
  * <a href="https://archive.orangefox.download/OrangeFox-Beta/vince/OrangeFox-R11.0_0-Beta-vince.zip" target="blank">**Orangefox R11.0 Beta**</a>

- **Recommended custom GApps packages:**
  * <a href="https://nikgapps.com/" target="blank">**Nikgapps**</a>
  * <a href="http://downloads.codefi.re/jdcteam/javelinanddart/gapps" target="blank">**Mindthegapps**</a> (Use arm64 only)

- **Other downloads:**
  * <a href="https://xiaomifirmwareupdater.com/firmware/vince/" target="blank">**Latest Stable Firmware**</a>
  * <a href="https://github.com/topjohnwu/Magisk/releases" target="blank">**Magisk Releases**</a>
