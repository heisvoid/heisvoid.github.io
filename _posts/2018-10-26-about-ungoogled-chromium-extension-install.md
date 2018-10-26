---
published: true
date: '2018-10-26 23:01 +0900'
title: About ungoogled-chromium extension install
---
A CRX file is installed directly into ~/.config/chromium/Default/Extensions/ID/VERSION. ID is extension's ID. VERSION is its version. When a newer version CRX is installed(it means that the extension is updated), it is installed into ~/.config/chromium/Default/Extensions/ID/NEWER_VERSION. So there are severals directories.

But when 'Load unpacked' is used, there is no new directory creation. It means that ~/.config/chromium/Default/Extensions/ID/VERSION is not made. It is just 'load', not 'install'. CRX can be unpacked with unzip. Also you can use tool 'inoxunpack'.

- <https://chrome-extension-downloader.com/>
- <https://robwu.nl/crxviewer/>
- <https://archive.is/4YBQd>
- <https://archive.is/7CTvh>
- <https://archive.is/FKic0>
- <https://archive.is/HZ4tt>
- <https://archive.is/BqRXp>
