---
published: true
date: '2018-08-01 18:09 +0900'
title: 라즈베리파이 아치리눅스 설정
---
- <http://archive.is/y82vy>
- <http://archive.is/aym6T>
- <http://archive.is/5iz8E>
- <http://archive.is/GHUJZ>

Pi-hole setup
Currently, the pi-hole-server package is in AUR. The package architecture is 'any'. So it can be installed on Archlinux ARM. Install an AUR helper. I've installed the aurman. The aurman package architecture is 'any'. It can be installed on Archlinux ARM. After install the aurman, setup pi-hole. Follow the ArchWiki guide.
- <http://archive.is/8sUhH>
- <http://archive.is/X4Ui5>

I do not want log. So I've commented out 'log-queries' and 'log-facility' in /etc/dnsmasq.d/01-pihole.conf.

- <http://archive.is/7zzJR>
- <http://archive.is/ZYdAE>

OpenVPN setup
- <http://archive.is/EMPzy>
- <https://goo.gl/mFgxRg>
- <https://goo.gl/DwnXo4>
