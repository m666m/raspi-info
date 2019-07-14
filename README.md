# raspi-info

* [Overview](#overview)
* [Installation](#installation)
* [Screenshot](#screenshot)
* [Changelog](#changelog)
* [License](#license)

## Overview
<b>RASPI-INFO is a tool to get a lot of infomation about your RaspberryPi.</b><br>
Direct use from shell: raspi-info or raspi-info-light.<br>
Automatic use: when you login through SSH (only raspi-info-light).<br>
<b>RASPI-INFO provides too more than 100 "shell tips" that can be useful to help you in bash!</b><br>

## Installation
```bash
git clone https://github.com/mapi68/raspi-info.git
dpkg -i raspi-info/raspi-info*.deb
apt install -f -y
# rm -rf raspi-info ### ONLY if you want remove installation folder!
```

## Screenshot
#### raspi-info-light
<img src="https://i.postimg.cc/N0KmrGhT/raspi-info-light.png" alt="raspi-info-light"><br>
#### partition-info
<img src="https://i.postimg.cc/NGZHWvHf/partition-info.png" alt="partition-info"><br>
#### general-info
<img src="https://i.postimg.cc/28FSTsdt/general-info.png" alt="general-info"><br>
#### folder-info
<img src="https://i.postimg.cc/jSx2VkVZ/folder-info.png" alt="folder-info"><br>
#### wireguard-info
<img src="https://i.postimg.cc/SN8M416L/wireguard-info.png" alt="wireguard-info"><br>
#### raspi-info
<img src="https://i.postimg.cc/G2j56pHV/raspi-info.png" alt="raspi-info"><br>


## Changelog

<b>raspi-info (1.1-2) ; urgency=medium</b>
  * Added info from tune2fs

<b>raspi-info (1.1-1) ; urgency=high</b>
  * Added support for Debian 10
  * Added new logo
  * Removed DNS ping

<b>raspi-info (1.0-19) ; urgency=medium</b>
  * Added wireguard support

<b>raspi-info (1.0-18) ; urgency=low</b>
  * Fixed cosmetic error

<b>raspi-info (1.0-17) ; urgency=medium</b>
  * Added interfaces speed
  * Fixed cosmetic error

<b>raspi-info (1.0-16) ; urgency=high</b>
  * Now raspi-info removes useless files in /etc/update-motd.d and /etc/motd

<b>raspi-info (1.0-15) ; urgency=medium</b>
  * Added Filesystem info check and lifetime writes

<b>raspi-info (1.0-14) ; urgency=medium</b>
  * Fixed DNS ping

<b>raspi-info (1.0-13) ; urgency=high</b>
  * Fixed file backup in preinst and postrm
  * Added md5 file

<b>raspi-info (1.0-12) ; urgency=low</b>
  * Updated Shell tips

<b>raspi-info (1.0-11) ; urgency=medium</b>
  * Added DNS ping

<b>raspi-info (1.0-10) ; urgency=medium</b>
  * Added list of USB devices

<b>raspi-info (1.0-9) ; urgency=high</b>
  * Fixed many bugs

<b>raspi-info (1.0-8) ; urgency=medium</b>
  * Added shell tips

<b>raspi-info (1.0-7) ; urgency=medium</b>
  * Added beautiful calendar

<b>raspi-info (1.0-6) ; urgency=medium</b>
  * Added min-max CPU frequency

<b>raspi-info (1.0-5) ; urgency=medium</b>
  * Added MAC address for all interfaces

<b>raspi-info (1.0-4) ; urgency=medium</b>
  * Added traceroute

<b>raspi-info (1.0-3) ; urgency=high</b>
  * Fixed bug in folder /etc/update-motd.d

<b>raspi-info (1.0-2) ; urgency=medium</b>
  * Added number of core in CPU info

<b>raspi-info (1.0-1) ; urgency=medium</b>
  * FIRST RELEASE
  
  
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md)