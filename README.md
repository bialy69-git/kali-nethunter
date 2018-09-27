### Note:

This is a forked version from Official Kali Nethuner repo, some modification are made since Official Image are not updated for a long time. The purpose of this modification is to ensure compatibility with [Magisk Kali Nethunter](https://github.com/atarii/Magisk_Kali_Nethunter).

## How to use:

> git clone git://github.com/exalab999/kali-nethunter

> cd kali-nethunter/nethunter-fs

> sudo ./build.sh --full --arch armhf

## IMPORTANT:

1. This script is currently configure to build armhf image only, other architecture are not tested but it may work too.

2. VNC function does not work, trying to start VNC Server will result in a device force reboot.

3. The script include most of the tools I needed, also including a terminal based browser and terminal based email client since VNC is not working.

4. Apt problem: running apt-get update or apt update will result in error.

5. I currently don't have time to solve these issue, if you found a solution please open an issue, thanks.


# NetHunter - Mobile Penetration Testing Platform
![Kali NetHunter](https://raw.githubusercontent.com/offensive-security/kali-nethunter/master/images/nethunter-git-logo.png)
## A project by Offensive Security
**The Kali NetHunter** is an Android penetration testing platform targeted towards Nexus and OnePlus devices built on top of Kali Linux, which includes some special and unique features. 
Of course, you have all the usual Kali tools in NetHunter as well as the ability to get a full VNC session from your phone to a graphical Kali chroot, however the strength of NetHunter does not end there. 
We've incorporated some amazing features into the NetHunter OS which are both powerful and unique. From pre-programmed HID Keyboard (Teensy) attacks, to BadUSB Man In The Middle attacks, to one-click MANA Evil Access Point setups, access to the Offensive Security Exploit Database... 
And yes, NetHunter natively supports wireless 802.11 frame injection with a variety of supported USB NICs.

## Documentation and Attack Descriptions
Attack descriptions as well as some documentation to get you started with the installation and setup of Kali NetHunter can be found at https://github.com/offensive-security/kali-nethunter/wiki.

## Is Kali NetHunter an Android ROM?

Kali Linux NetHunter is **not** a ROM but is meant to be installed over an existing stock/factory image of Android. It can also be installed over some Cyanogenmod based ROMs depending on device support. It is heavily based on using custom kernels and only supports a select number of devices.
We're relying on you, the community, to port your devices for the full Kali NetHunter experience.

## Frequently Asked Questions
**Q** - Does NetHunter support Marshmallow, or Nexus 9 devices?

**A** - Yes, check our wiki for more information on supported devices and ROMs https://github.com/offensive-security/kali-nethunter/wiki#10-supported-devices-and-roms
<hr>

**Q** - What kind of attacks does NetHunter support?

**A** - Our wiki has a list of included attack tools https://github.com/offensive-security/kali-nethunter/wiki#60-kali-nethunter-attacks-and-features
<hr>

**Q** - NetHunter is awesome! How do I install it?

**A** - Follow the instructions on the wiki https://github.com/offensive-security/kali-nethunter/wiki#40-installing-nethunter-on-top-of-android
<hr>

**Q** - What is the best wireless card for NetHunter?

**A** - A list of supported devices and chipsets is on the wiki https://github.com/offensive-security/kali-nethunter/wiki/Wireless-Cards

Fri Jan  15 02:09:40 EST 2016

