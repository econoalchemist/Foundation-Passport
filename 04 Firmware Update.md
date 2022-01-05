# Firmware Update

For this section you will need an USB adaptor and your included microSD card. Keeping the firmware on the Passport is important as this is how new features are introduced, quality of life improvements are made, security issues are resolved, and bugs are fixed. Foundation regularly releases firmware updates so be sure to stay up to date with these as they occur. Navigate to the official [Foundation firmware page](https://docs.foundationdevices.com/en/firmware-update) to see more details. 

In this section updating the firmware will be demonstrated in two ways. The first way involves fewer steps but foregoes independant verification, the second way demonstrates using the developer's PGP public keys and signatures to cryptographically verify the integrity of the firmware file. 

The Passport will only allow firmware to be installed if it has been signed by at least two out of four possible Foundation developer PGP keys. This gives beginner or intermediate users the ability to update their firmware with a reasonable degree of confidence, while giving advanced users the ability to verify the integrity of the firmware themselves. 

Before getting started with either approach outlined below, first check your Passport to compare the currently installed firmware version with the currently available firmware version. 

Log into your Passport by powering it on, typing in the first 4-digits of your PIN, confirming your two anti-phing words, and entering the remainder of your PIN. From the main menu, navigate to `Settings > Firmware > Current Version`.

 <p align="center">
<img width="300" src="assets/passport36.jpg">
<img width="300" src="assets/passport37.jpg">
<img width="300" src="assets/passport38.jpg">
  </p>

There you will see the currently installed firmware version, the date of its release, and a boot counter. The boot counter tells you how many times the Passport has been powered on. Compare the currently installed firmware version to the displayed currently available version on the Foundation [firmware download page](https://docs.foundationdevices.com/en/firmware-update). If the installed version is lower than the available version, then you will want to update that. If you have the latest firmware installed then you can skip to the next section. Press the <kbd>back</kbd> button to return to the previous sub menu. 

 <p align="center">
<img width="300" src="assets/passport39.jpg">
<img width="300" src="assets/Firmware02.png">
<img width="300" src="assets/passport40.jpg">
  </p>

## Simple Firmware Update
Navigate to the Foundation [Setup page](https://docs.foundationdevices.com/en/setup-guide) and click on the link to open the [firmware download](https://github.com/Foundation-Devices/passport-firmware/releases/download/v1.0.8/passport-fw-1.0.8.bin)

 <p align="center">
<img width="900" src="assets/Firmware00.png">
  </p>

Clicking on that link will automatically initiate the Foundation firmware `.bin` file download to your computer. Using your own USB to microSD adaptor, insert your included microSD card into the USB adaptor and then insert that adaptor into a USB port on your computer. Once the computer recognizes your USB adaptor then simply open a file explorer and copy/paste the firmware `.bin` file to the microSD card. Then safely eject the microSD card.  

 <p align="center">
  <img width="450" src="assets/Adaptor00.jpg">
  <img width="450" src="assets/Firmware01.png">
  </p>

The microSD card inserts to the port on the top of the Passport. The microSD card does not fully insert to the device, it will be sticking out about half way. Ensure the pins on the microSD card are facing up, the same direction as the face of the device. 

 <p align="center">
  <img width="450" src="assets/passport34.jpg">
  <img width="450" src="assets/passport35.png">
  </p>

- From the same sub-menu where you checked the firmware version, select `Update Firmware` this time. 
- Then follow the prompt and press <kbd>continue</kbd>. 
- On the next screen scroll to the bottom of the message by pressing the <kbd>down arrow</kbd>. 
- Confirm you want to proceed by pressing <kbd>yes</kbd>. 

 <p align="center">
<img width="450" src="assets/passport41.jpg">
<img width="450" src="assets/passport42.jpg">
<img width="450" src="assets/passport43.jpg">
<img width="450" src="assets/passport44.jpg">
  </p>

On the next screen you will see a message warning you not to power off the Passport during the firmware update. Having fresh batteries installed is recommended. Press <kbd>OK</kbd> to continue. Then the passport will first prepare the update and then execute the update. After a moment the Passport will display the new currently installed firmware version. 

 <p align="center">
<img width="450" src="assets/passport45.jpg">
<img width="450" src="assets/passport46.jpg">
<img width="450" src="assets/passport47.jpg">
<img width="450" src="assets/passport48.jpg">
  </p>

After the firmware update is finished you can remove the microSD card and continue to setup your seed phrase. 
