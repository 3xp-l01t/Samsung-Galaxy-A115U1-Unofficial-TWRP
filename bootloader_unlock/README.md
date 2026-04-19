# Flashing Stock ROM on SM-A115U1

> **Note:** These steps are adapted from an XDA forum post. I mostly copied and pasted them for convenience.  
> Source: [XDA Thread Link](https://xdaforums.com/t/the-right-way-to-show-oem-unlocking-in-galaxy-a11-sm-a115u.4375791/)

## Steps

1. **Download and install Samsung USB drivers** from [this link](https://developer.samsung.com/android-usb-driver).

2. **Download the latest stock ROM** for SM-A115U1 from [SamFW](https://samfw.com/firmware/SM-A115U1/XAA/A115U1UESACWL1) or another trusted website.

3. **Download a patched Odin** from [this github link](https://github.com/3xp-l01t/Samsung-Galaxy-A115U1-Unofficial-TWRP/tree/main/other_files/software/odin) – I used `Odin3 v3.14.1_3B_PatcheD`.

4. **Extract the ROM files** and load them into Odin:
   - BL → `BL_...tar.md5`
   - AP → `AP_...tar.md5`
   - CP → `CP_...tar.md5`
   - CSC → `CSC_...tar.md5` (not HOME_CSC)

5. **Boot your phone into Download Mode:**
   - Power off completely.
   - Press and hold **Power + Volume Up + Volume Down**.
   - When the phone vibrates, release **Power** but keep holding both Volume buttons.
   - At the warning screen, press **Volume Up** to enter Download Mode.

6. **Plug your phone into the PC** – Odin should show `Added!` with a blue COM port.

7. **Click Start** in Odin. The process will take a few minutes. Once finished, the phone will reboot automatically.

8. After reboot, go to **Settings → Developer Options** and verify that **OEM Unlocking** is visible (it may be greyed out or already unlocked).

---

> ⚠️ Flashing stock ROM will wipe your data. Back up everything first.
