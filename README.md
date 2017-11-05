# configurattion.plist-for-iMac-14.2

configuration settings for imac if you are using clover or unibeast
this is the post installation settings.

Intel core i5-6600K 
Z270x - Ultra Gaming rev 1.0
Kingston Hyperx Fury 16gb 3200mHz


Now added full support for MacOSHigh sierra with all needed kexts and fixses for nvda_drv=1. Voodohda sound and intelmausiethernet kexts. All included in folder 

Added new config.plist file for MacOSHighSierra.
Old from MacOS Sierra was renamed to configuration.plist

if you still use MacOSSIerra just download configuration.plist.
Mount your EFI partition with clover configurator and replace your config plist and rename it config.plist and of corse modify config.plist for your machine.

#Note:

Nvidia WebDriver is just for MacOSHighSierra 10.13.1 bulid 17B48. If you are using other build please find driver
for your build on tonymacx86.com  or on nvidia site. 

Before install nvidia web driver you need to Enable SIP 0x00 and inject nvidiawebdriver and in efi/clover/kexts/other put nvdia fix and lilu.
