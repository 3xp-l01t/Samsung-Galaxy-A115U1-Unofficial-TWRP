# Samsung-Galaxy-A115U1-Unofficial-TWRP

> **⚠️ WARNING**  
> - Flashing custom recovery can brick your device or void your warranty.  

> - Back up all data before proceeding.  

> - You assume full responsibility.  

> - **Note:** This TWRP image is not my work. I just made simple, easy‑to‑understand instructions.



### Requirements

  * Phone with A115U1UESACWL1 [firmware](https://samfw.com/firmware/SM-A115U1/XAA/A115U1UESACWL1)
  * [Samsung USB drivers](https://developer.samsung.com/android-usb-driver) installed.
  * Latest [Odin](https://odindownload.com/)
  * Unlocked bootloader
  * [vbmeta_disabler.tar](https://github.com/3xp-l01t/Samsung-Galaxy-A115U1-Unofficial-TWRP/raw/refs/heads/main/other_files/vbmeta_disabled.tar) and [TWRP_A11.tar](https://github.com/3xp-l01t/Samsung-Galaxy-A115U1-Unofficial-TWRP/raw/refs/heads/main/twrp_images/twrp-3.6.0_afaneh92-a11q.tar)
  * USB cable


## Step 1

* Boot phone into **Download Mode** (Volume Down + Power → Volume Up)

* Launch Odin and disable Auto Reboot in the Options tab.

![Download Mode](https://github.com/user-attachments/assets/83d6bc1d-ad80-45d6-9039-6059616b5b39)

* Connect to PC – Odin shows `Added!` and a blue COM port

* Load [vbmeta_disabler.tar](https://github.com/3xp-l01t/Samsung-Galaxy-A115U1-Unofficial-TWRP/raw/refs/heads/main/other_files/vbmeta_disabled.tar) into the AP slot and click **Start**.
  

## Step 2

* Reboot into **Factory recovery** by holding **Volume Up + Power** after Odin finishes and factory reset the phone, then power it off.

* Boot into download mode and plug into the computer.

* Go to Odin, load the twrp image into the AP slot, disable auto reboot.

* Click Start.

## Step 3

* Reboot into **Factory recovery** by holding **Volume Up + Power**. 

* Once in TWRP, go to **Advanced → Terminal**, type `multidisabler`, press Enter. go back and select **Reboot → System**.
![twrp_advanced](https://raw.githubusercontent.com/3xp-l01t/Samsung-Galaxy-A115U1-Unofficial-TWRP/refs/heads/main/images/images.png?token=GHSAT0AAAAAAD23OBENCHLSGMJNZMFNVDQU2PEQSIQ)

![twrp_terminal](https://raw.githubusercontent.com/3xp-l01t/Samsung-Galaxy-A115U1-Unofficial-TWRP/refs/heads/main/images/images.jpeg?token=GHSAT0AAAAAAD23OBEMYL3GLQRLROOUPDHQ2PEQTSQ)

