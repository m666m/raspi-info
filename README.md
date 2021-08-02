# raspi-info

* [Overview](#overview)
* [Installation](#installation)
* [Screenshot](#screenshot)
* [Changelog](#changelog)
* [License](#license)

## Overview
<b>RASPI-INFO is a tool to get a lot of infomation about your Raspberry Pi.</b><br>
Direct use from shell: raspi-info or raspi-info-light.<br>
Automatic use: when you login through SSH (only raspi-info-light).<br>
<b>RASPI-INFO provides too more than 100 "shell tips" that can be useful to help you in bash!</b><br>

<img src="https://github.com/mapi68/raspi-info/raw/master/images/raspi-info-logo.png"><br>

## Installation
```bash
if [[ `uname -m` = aarch64 ]]; then
	wget -P /tmp/ https://github.com/mapi68/raspi-info/raw/master/raspi-info_latest-64.deb; else
	wget -P /tmp/ https://github.com/mapi68/raspi-info/raw/master/raspi-info_latest-32.deb; fi
sudo dpkg -i /tmp/raspi-info_latest-*.deb; sudo apt install -f -y; rm /tmp/raspi-info_latest-*
```

## Screenshot
#### raspi-info-light
<img src="https://github.com/mapi68/raspi-info/raw/master/images/raspi-info-light.png"><br>
#### general-info
<img src="https://github.com/mapi68/raspi-info/raw/master/images/general-info.png"><br>
#### partition-info
<img src="https://github.com/mapi68/raspi-info/raw/master/images/partition-info.png"><br>
#### folder-info
<img src="https://github.com/mapi68/raspi-info/raw/master/images/folder-info.png"><br>
#### wireguard-info
<img src="https://github.com/mapi68/raspi-info/raw/master/images/wireguard-info.png"><br>
#### raspi-info
<img src="https://github.com/mapi68/raspi-info/raw/master/images/raspi-info.png"><br>


## Changelog

<b>raspi-info (20210802); urgency=high</b>
  * Now version is based upon date
  * Check for automatic update in raspi-info-light
  * Added raspi-info-update

<b>raspi-info (1.5-3); urgency=medium</b>
  * Added bash version only in raspi-info

<b>raspi-info (1.5-2); urgency=low</b>
  * Some cosmetic changes

<b>raspi-info (1.5-1); urgency=medium</b>
  * Show Bitcoin price
  * Added support for Pi-hole

<b>raspi-info (1.4-1); urgency=high</b>
  * raspi-info now requires elevated privileges to run
  * Added info about installed packages

<b>raspi-info (1.3-4); urgency=low</b>
  * Some cosmetic changes
  
<b>raspi-info (1.3-3); urgency=medium</b>
  * Fixed memory detection for Pi 4
  * Some cosmetic changes
  
<b>raspi-info (1.3-2); urgency=low</b>
  * Added info about Raspberry bootloader for Pi 4

<b>raspi-info (1.3-1); urgency=high</b>
  * Move files from /usr/local to /usr
  * Added Raspberry model

<b>raspi-info (1.2-5); urgency=medium</b>
  * Added WLAN info in raspi-info and raspi-info-light

<b>raspi-info (1.2-4); urgency=medium</b>
  * Added check for MPG2 and WVC1 codec license

<b>raspi-info (1.2-3); urgency=medium</b>
  * Added IP country detection in raspi-info-light

<b>raspi-info (1.2-2); urgency=high</b>
  * Missing dependencies for OSMC mediacenter
  
<b>raspi-info (1.2-1); urgency=medium</b>
  * Added arm64 version

<b>raspi-info (1.1-7); urgency=medium</b>
  * Added Kernel IP routing table

<b>raspi-info (1.1-6); urgency=medium</b>
  * Added support for apcupsd

<b>raspi-info (1.1-5); urgency=medium</b>
  * Added Hardware, Revision and Serial number

<b>raspi-info (1.1-4); urgency=low</b>
  * Added more info in WHOIS
  
<b>raspi-info (1.1-3); urgency=low</b>
  * Added support to ping multiple DNS
  
<b>raspi-info (1.1-2); urgency=medium</b>
  * Added info from tune2fs

<b>raspi-info (1.1-1); urgency=high</b>
  * Added support for Debian 10
  * Added new logo

<b>raspi-info (1.0-19); urgency=medium</b>
  * Added wireguard support

<b>raspi-info (1.0-18); urgency=low</b>
  * Fixed cosmetic error

<b>raspi-info (1.0-17); urgency=medium</b>
  * Added interfaces speed
  * Fixed cosmetic error

<b>raspi-info (1.0-16); urgency=high</b>
  * Now raspi-info removes useless files in /etc/update-motd.d and /etc/motd

<b>raspi-info (1.0-15); urgency=medium</b>
  * Added Filesystem info check and lifetime writes

<b>raspi-info (1.0-14); urgency=medium</b>
  * Fixed DNS ping

<b>raspi-info (1.0-13); urgency=high</b>
  * Fixed file backup in preinst and postrm
  * Added md5 file

<b>raspi-info (1.0-12); urgency=low</b>
  * Updated Shell tips

<b>raspi-info (1.0-11); urgency=medium</b>
  * Added DNS ping

<b>raspi-info (1.0-10); urgency=medium</b>
  * Added list of USB devices

<b>raspi-info (1.0-9); urgency=high</b>
  * Fixed many bugs

<b>raspi-info (1.0-8); urgency=medium</b>
  * Added shell tips

<b>raspi-info (1.0-7); urgency=medium</b>
  * Added beautiful calendar

<b>raspi-info (1.0-6); urgency=medium</b>
  * Added min-max CPU frequency

<b>raspi-info (1.0-5); urgency=medium</b>
  * Added MAC address for all interfaces

<b>raspi-info (1.0-4); urgency=medium</b>
  * Added traceroute

<b>raspi-info (1.0-3); urgency=high</b>
  * Fixed bug in folder /etc/update-motd.d

<b>raspi-info (1.0-2); urgency=medium</b>
  * Added number of core in CPU info

<b>raspi-info (1.0-1); urgency=medium</b>
  * FIRST RELEASE
  
  
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md)
