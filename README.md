# raspi-info

* [Overview](#overview)
* [Installation](#installation)
* [Screenshot](#screenshot)
* [Changelog](#changelog)
* [License](#license)

## Overview
**RASPI-INFO is a tool to get a lot of infomation about your Raspberry Pi.**

Direct use from shell: raspi-info or raspi-info-light. Automatic use: when you login through SSH (only raspi-info-light).
RASPI-INFO provides too more than 100 "shell tips" that can be useful to help you in bash!
When a new update will be released you'll receive a message at the end of program.

![logo](https://github.com/mapi68/raspi-info/raw/master/images/raspi-info-logo.png)

## Installation
```bash
curl -sSfL https://raw.githubusercontent.com/mapi68/raspi-info/master/raspi-info-install | bash
```

## Screenshot
### raspi-info-light
![raspi-info-light](https://github.com/mapi68/raspi-info/raw/master/images/raspi-info-light.png)

### general-info
![general-info](https://github.com/mapi68/raspi-info/raw/master/images/general-info.png)

### partition-info
![partition-info](https://github.com/mapi68/raspi-info/raw/master/images/partition-info.png)

### folder-info
![folder-info](https://github.com/mapi68/raspi-info/raw/master/images/folder-info.png)

### wireguard-info
![logo](https://github.com/mapi68/raspi-info/raw/master/images/wireguard-info.png)

### raspi-info
![raspi-info](https://github.com/mapi68/raspi-info/raw/master/images/raspi-info.png)

## Changelog

**raspi-info (20210802); urgency=high**
  * Now version is based upon date
  * Check for automatic update in raspi-info-light
  * Added raspi-info-update

**raspi-info (1.5-3); urgency=medium**
  * Added bash version only in raspi-info

**raspi-info (1.5-2); urgency=low**
  * Some cosmetic changes

**raspi-info (1.5-1); urgency=medium**
  * Show Bitcoin price
  * Added support for Pi-hole

**raspi-info (1.4-1); urgency=high**
  * raspi-info now requires elevated privileges to run
  * Added info about installed packages

**raspi-info (1.3-4); urgency=low**
  * Some cosmetic changes
  
**raspi-info (1.3-3); urgency=medium**
  * Fixed memory detection for Pi 4
  * Some cosmetic changes
  
**raspi-info (1.3-2); urgency=low**
  * Added info about Raspberry bootloader for Pi 4

**raspi-info (1.3-1); urgency=high**
  * Move files from /usr/local to /usr
  * Added Raspberry model

**raspi-info (1.2-5); urgency=medium**
  * Added WLAN info in raspi-info and raspi-info-light

**raspi-info (1.2-4); urgency=medium**
  * Added check for MPG2 and WVC1 codec license

**raspi-info (1.2-3); urgency=medium**
  * Added IP country detection in raspi-info-light

**raspi-info (1.2-2); urgency=high**
  * Missing dependencies for OSMC mediacenter
  
**raspi-info (1.2-1); urgency=medium**
  * Added arm64 version

**raspi-info (1.1-7); urgency=medium**
  * Added Kernel IP routing table

**raspi-info (1.1-6); urgency=medium**
  * Added support for apcupsd

**raspi-info (1.1-5); urgency=medium**
  * Added Hardware, Revision and Serial number

**raspi-info (1.1-4); urgency=low**
  * Added more info in WHOIS
  
**raspi-info (1.1-3); urgency=low**
  * Added support to ping multiple DNS
  
**raspi-info (1.1-2); urgency=medium**
  * Added info from tune2fs

**raspi-info (1.1-1); urgency=high**
  * Added support for Debian 10
  * Added new logo

**raspi-info (1.0-19); urgency=medium**
  * Added wireguard support

**raspi-info (1.0-18); urgency=low**
  * Fixed cosmetic error

**raspi-info (1.0-17); urgency=medium**
  * Added interfaces speed
  * Fixed cosmetic error

**raspi-info (1.0-16); urgency=high**
  * Now raspi-info removes useless files in /etc/update-motd.d and /etc/motd

**raspi-info (1.0-15); urgency=medium**
  * Added Filesystem info check and lifetime writes

**raspi-info (1.0-14); urgency=medium**
  * Fixed DNS ping

**raspi-info (1.0-13); urgency=high**
  * Fixed file backup in preinst and postrm
  * Added md5 file

**raspi-info (1.0-12); urgency=low**
  * Updated Shell tips

**raspi-info (1.0-11); urgency=medium**
  * Added DNS ping

**raspi-info (1.0-10); urgency=medium**
  * Added list of USB devices

**raspi-info (1.0-9); urgency=high**
  * Fixed many bugs

**raspi-info (1.0-8); urgency=medium**
  * Added shell tips

**raspi-info (1.0-7); urgency=medium**
  * Added beautiful calendar

**raspi-info (1.0-6); urgency=medium**
  * Added min-max CPU frequency

**raspi-info (1.0-5); urgency=medium**
  * Added MAC address for all interfaces

**raspi-info (1.0-4); urgency=medium**
  * Added traceroute

**raspi-info (1.0-3); urgency=high**
  * Fixed bug in folder /etc/update-motd.d

**raspi-info (1.0-2); urgency=medium**
  * Added number of core in CPU info

**raspi-info (1.0-1); urgency=medium**
  * FIRST RELEASE
  
  
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md)
