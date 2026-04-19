# Samsung-Galaxy-A115U1-Unofficial-TWRP
### Requirements

  * Phone with A115U1UESACWL1 [firmware](https://samfw.com/firmware/SM-A115U1/XAA/A115U1UESACWL1)
  * [Samsung USB drivers](https://developer.samsung.com/android-usb-driver) installed.
  * Latest [Odin](https://odindownload.com/)
  * Unlocked bootloader
  * [Vbmeta_disabler.tar](link) and [TWRP_A11.tar](link)
  * USB cable


## Step 1

* Boot into download mode and plug your **phone** into your PC.

* **Volume down and power button**

* Launch Odin and disable Auto Reboot in the Options tab.

![Download Mode](https://github.com/user-attachments/assets/83d6bc1d-ad80-45d6-9039-6059616b5b39)


* Load Vbmeta_disabler.tar into the AP slot and click **Start**.
  

## Step 2

* Reboot into **Factory recovery** by holding **Volume Up + Power** after Odin finishes and factory reset the phone, then power it off.

* Boot into download mode and plug into the computer.

* Go to Odin, load the twrp image into the AP slot, disable auto reboot.

* Click Start.

## Step 3

* Reboot into **Factory recovery** by holding **Volume Up + Power**. 

* Once in TWRP, go to **Advanced → Terminal**, type `multidisabler`, press Enter. go back and select **Reboot → System**.
![twrp_advanced](https://raw.githubusercontent.com/3xp-l01t/Samsung-Galaxy-A115U1-Unofficial-TWRP/refs/heads/main/images/images.png?token=GHSAT0AAAAAAD23OBEMOETCPWHQWUEOC6O22PEORJQ)

