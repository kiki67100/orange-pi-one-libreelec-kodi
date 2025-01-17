# OrangePI One with Hardware Acceleration

This repository contains an image for the OrangePI One with hardware acceleration enabled. I found this image online a while back and needed it for a friend to display a looping video in his store. The OrangePI One was lying around at my place, so I decided to put it to use.

## Background

I initially tried using an Armbian image, but it did not support hardware acceleration. I attempted to compile Cedrus and the Linux kernel myself, but I wasn't successful. Eventually, I found this image, which works perfectly for my needs. It provides video acceleration for the AllWinner H3 and works very well.

I've configured it to run with autoexec, and it works great. I created this Git repo in case anyone else needs it :)

## Instructions

1. **Download the image**: You will need to extract the image files using 7-zip due to the 100MB storage limitation on GitLab.
2. **Flash the image** to your OrangePI One.
3. **Run with autoexec**: The setup is configured to start automatically.

## Enjoy!

Feel free to use this image and share it. If you encounter any issues or have any improvements, contributions are welcome.

Have fun :)
