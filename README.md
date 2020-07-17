# goportal

(Work in progress)

Goportal is a complete Linux Build bootable on USB Stick with LAMP Servers / phpMyAdmin / dnsmasq / Joomla / Humhub.

USB Bootable Image
Live USB Installer (Created by SystemBack 1.9.4)

- Sparkylinux 5.xx  (Debian Buster) - Openbox filemanger
- Apache2 Webserver
- MariaDB 10.x
- Php 7.3
- dnsmasq
- Joomla 3.9.x
- Humhub 1.5.x

Apache2 Webserver is configured as:
1 Virtual Domain - goportal.us

dnsmasq is configured as: 
- redirect all requests to localhost / 192.168.1.4 Joomla Login Portal Page
- DHCP Server - enabled
- DNS Server - enabled
- Can be combined with Access Point
  All Clients are given an IP address: 192.168.1.* (1-50)
  
Joomla addons:
- JCE Editor
- JCE Mediabox
- AdsManager

Humhub 1.5.x
- All Free Modules are installed
- Includes extra Free Themes

/
