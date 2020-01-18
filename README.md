# reddpi
ReddPi - Raspberry Pi ready-to-use images and update scripts for rPi single board computers
https://sourceforge.net/projects/reddpi/ Thanks to @CryptoBUZE
https://reddpi.sourceforge.io/

ReddPi - ready to use images for Raspberry Pi single board computers
=======================
Raspbian Buster recommended for Raspberry Pi 2, Raspberry Pi 3(+) and Raspberry Pi 4 (1G or more memory).
https://sourceforge.net/projects/reddpi/files/raspbian_buster/reddpi_raspbian_buster.zip/download
https://sourceforge.net/projects/reddpi/files/raspbian_buster/

Raspbian Buster lite (non desktop environment) recommended for Raspberry Pi 1 or Raspberry Pi Zero (512MB memory) but can also be used with all other Raspberry Pi's.
https://sourceforge.net/projects/reddpi/files/raspbian_buster-lite/reddpi_raspbian_buster-lite.zip/download
https://sourceforge.net/projects/reddpi/files/raspbian_buster-lite/

Image has no blockchain data attached. Download latest blockchain data with script placed on desktop or run download_blockchain.sh script from user home directory (/home/pi).

Login with user pi and password rddstaking. Autologin for desktop environment is activated. Please be sure to change the password after first login.

Original photography used for desktop wallpaper: created by Greg Rakozy (https://unsplash.com/photos/oMpAz-DN-9I)

----------------------------
Please be aware that these images are only for Raspberry Pi's and not tested on any other single board computers.
----------------------------

Features
Latest Raspbian Buster for older Raspberry Pi's and also for the newest Raspberry Pi 4
Desktop environment with pre installed and latest Reddcoin Core Wallet (v3)
Raspbian Buster lite (non desktop ) for running in headless mode for Raspberry Pi's with less resources
Script for downloading blockchain data for fast synchronization

https://sourceforge.net/projects/reddpi/

README.md:
# --- ReddPi ---

## Image raspbian_buster-lite
https://sourceforge.net/projects/reddpi/files/raspbian_buster-lite/reddpi_raspbian_buster-lite.zip/download
* Raspbian Buster lite (non desktop environment) for Raspberry Pi 1 or Raspberry Pi Zero (512MB memory)
* Can also be used with all other Raspberry Pi's

## Image raspbian_buster
https://sourceforge.net/projects/reddpi/files/raspbian_buster/reddpi_raspbian_buster.zip/download
* Raspbian Buster (with desktop environment) for Raspberry Pi 2, Raspberry Pi 3(+) and Raspberry Pi 4 (1G or more memory)
* Can also be used with Raspberry Pi 1 or Raspberry Pi Zero in headless/non desktop mode

## Image raspbian_jessie
https://sourceforge.net/projects/reddpi/files/raspbian_jessie/reddpi_raspbian_jessie.zip/download
* Raspbian Jessie based on Reddcoin Stakebox image (with desktop environment) for Raspberry Pi 2, Raspberry Pi 3(+) and Raspberry Pi 4 (1G or more memory)
* Can also be used with Raspberry Pi 1 or Raspberry Pi Zero in headless/non desktop mode

## Writing images to sdcard:
* Windows: Win32DiskImager -> https://sourceforge.net/projects/win32diskimager/
* macOS: Etcher -> https://www.balena.io/etcher/

## Update script for existing Raspbian installations
* Update script which downloads/installs pre compiled binaries: https://raw.githubusercontent.com/cryptoBUZE/reddcoin/v3.0.x/contrib/reddcoin_core_download_raspbian.sh
* See also release on github: https://github.com/cryptoBUZE/reddcoin/releases/tag/rpi_raspbian_buster_v3.0.0
