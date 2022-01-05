# Firmware Update

Keeping the firmware on the Passport is important as this is how new features are introduced, quality of life improvements are made, security issues are resolved, and bugs are fixed. Foundation regularly releases firmware updates so be sure to stay up to date with these as they occur. Navigate to the official [Foundation firmware page](https://docs.foundationdevices.com/en/firmware-update) to see more details. 

In this section updating the firmware will be demonstrated in two ways. The first way involves fewer steps but foregoes independant verification, the second way demonstrates using the developer's PGP public keys and signatures to cryptographically verify the integrity of the firmware file. 

The Passport will only allow firmware to be installed if it has been signed by at least two out of four possible Foundation developer PGP keys. This gives beginner or intermediate users the ability to update their firmware with a reasonable degree of confidence, while giving advanced users the ability to verify the integrity of the firmware themselves. 

## Simple Firmware Update
Navigate to the Foundation [Setup page](https://docs.foundationdevices.com/en/setup-guide) and click on the link to open the [firmware download](https://github.com/Foundation-Devices/passport-firmware/releases/download/v1.0.8/passport-fw-1.0.8.bin)
