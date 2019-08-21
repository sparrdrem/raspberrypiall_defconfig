# raspberrypiall_defconfig
Defconfig file for Buildroot to build RPi image for all boards

Note: Until Raspberry Pi 4 is added to the LTS releases this builder will not be building bcm rpi4 images.

### How to Install

To install the custom defconfig, copy all files in the root directory of this repo to the same location as the makefile for buildroot. That should place all the scripts for this in the place it needs to go.

After the files are copied you just run

```
make raspberrypiall_defconfig
```

and proceed to build an image like normal.
