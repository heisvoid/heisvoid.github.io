---
published: true
date: '2018-08-02 17:05 +0900'
title: Raspbian installation
---
Currently, Pi-hole does not support Archlinux ARM. Pi-hole only supports Raspbian for RPi.

Headless Raspbian SD setup.
1. Create partitions/filesystems on the SD card.
2. ~~Manually extracting data from Raspbian image.~~ This way makes that the partition size is different from the filesystem size. So Download and extract boot.tar.xz and root.tar.xz.
3. Edit /boot/cmdline.txt and /etc/fstab.
4. Prevent rootfs partition to expand.
5. Create a file named ssh on the boot partition. When the Pi boots, it looks for the ssh file. If it is found, SSH is enabled and the file is deleted.

- <http://archive.is/EVHSf>
- ~~<http://archive.is/CaPbT>~~
- <http://archive.is/sIsWP>
- <http://archive.is/Fw79v>
- <http://archive.is/A3K2n>
- <http://archive.is/B6p24>
- <http://archive.is/1JKsq>
