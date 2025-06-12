====================================================================
                      X-10-WIFI-V2 WiFi Penetration Tool
====================================================================

Developed by ARIF_MODZ | Version: 2.0 | License: MIT

[!] LEGAL DISCLAIMER: 
This tool is for educational and security testing purposes only. 
Unauthorized access to computer networks is illegal.

■ Features:
✔ Pixie Dust attack (offline WPS attack)
✔ Integrated 3WiFi offline WPS PIN generator
✔ Online WPS bruteforce capability
✔ Advanced WiFi network scanner
✔ Push button connection support

■ Requirements:
• Python 3.6+
• Termux (for Android)
• Root access
• Wpa supplicant
• Pixiewps
• iw

■ Installation (Termux):

1. Basic setup:
pkg update && pkg upgrade
pkg install -y root-repo git tsu python wpa-supplicant pixiewps iw openssl
termux-setup-storage

2. Clone repository:
git clone --depth 1 https://github.com/Versionx10/X-10-WIFI-V2
cd X-10-WIFI-V2

■ Usage Examples:

1. Scan and attack (interactive mode):
sudo python X-10-WIFI-V2.py -i wlan0 -K

2. Attack specific BSSID:
sudo python X-10-WIFI-V2.py -i wlan0 -b 00:90:4C:C1:AC:21 -K

3. Bruteforce with first PIN half:
sudo python X-10-WIFI-V2.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234

4. WPS push button mode:
sudo python X-10-WIFI-V2.py -i wlan0 --pbc

■ Troubleshooting:

1. "RTNETLINK answers: Operation not possible due to RF-kill"
   Solution: sudo rfkill unblock wifi

2. "Device or resource busy (-16)"
   Solution: Disable WiFi in system settings or use --iface-down flag

3. MediaTek chipset issues:
   Use --mtk-wifi flag to initialize driver

■ Contact:
• GitHub: github.com/Versionx10
• Facebook: fb.com/Arifmoodz
• Telegram: t.me/Versionx10

====================================================================
           Use responsibly! Unauthorized access is prohibited.
====================================================================
