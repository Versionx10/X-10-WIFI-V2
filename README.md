### X-10-WIFI-V2

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=35F700&background=3C8BFF00&random=false&width=435&lines=Thanks+for+use+my+command+;place+don't+forged+start+;Im+ARIF+hi;Facebook%3A+Arifmoodz" alt="Typing SVG" /></a>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&random=false&width=435&lines=im-ARIF-thanks-for-my-cmd-use)](https://git.io/typing-svg)

### Hello, Welcome .. 
Hack Wifi ..Using  *X-10-WIFI-V2* by Termux/Android, ARIF-😫!!
<br><br>
![termuxICO](https://user-images.githubusercontent.com/80227002/112893051-6feceb00-90da-11eb-856d-1fac8f6d169a.png)![devoleper](https://i.postimg.cc/6Q0XPjdt/IMG-20240404-202439-804.jpg)
<br><br>
 

### HACK WIFI
<p align="center"><img src="https://user-images.githubusercontent.com/75953873/115979290-66309900-a55b-11eb-8259-4b125efc42bb.png"></p>

[![Python 3.5](https://img.shields.io/badge/Python-3.5-yellow.svg)](http://www.python.org/download/)
[![python](https://img.shields.io/badge/python-2.7-brightgreen.svg)](https://www.python.org/downloads/release/python-2714/)
[![OS](https://img.shields.io/badge/Tested%20On-Linux%20%7C%20Android-yellowgreen.svg)](https://termux.com/)


#### Manually
**Installing requirements**
```console
pkg update && pkg upgrade && pkg install -y root-repo && pkg install -y git tsu python wpa-supplicant pixiewps iw openssl && termux-setup-storage
 ```
**run farhan hack py**
 ```console
git clone --depth 1 https://github.com/Versionx10/X-10-WIFI-V2
 ```

#### Running fast command 😪?
 ```console
sudo X-10-WIFI-V2/X-10-WIFI-V2.py -i wlan0 -K 
 ```


 #### copy to past bro 
 <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=FF0202&background=000000&multiline=true&random=false&width=435&lines=2Nd+command+%F0%9F%98%81%3F" alt="Typing SVG" /></a>
 ```console
 sudo python X-10-WIFI-V2/X-10-WIFI-V2.py -i wlan0 -K 
 ```



# Overview
**X-10-WIFI-V2** performs [Pixie Dust attack](https://forums.kali.org/showthread.php?24286-WPS-Pixie-Dust-Attack-Offline-WPS-Attack) without having to switch to monitor mode.
# Features
 - [Pixie Dust attack](https://forums.kali.org/showthread.php?24286-WPS-Pixie-Dust-Attack-Offline-WPS-Attack);
 - integrated [3WiFi offline WPS PIN generator](https://3wifi.stascorp.com/wpspin);
 - [online WPS bruteforce](https://sviehb.files.wordpress.com/2011/12/viehboeck_wps.pdf);
 - Wi-Fi scanner with highlighting based on iw;
# Requirements
 - Python 3.6 and above;
 - [Wpa supplicant](https://www.w1.fi/wpa_supplicant/);
 - [Pixiewps](https://github.com/wiire-a/pixiewps);
 - [iw](https://wireless.wiki.kernel.org/en/users/documentation/iw).


## [Termux](https://termux.com/)
Please note that root access is required.  


### Hack WIfi Using Termux! (Requires Root)

# Usage
```
 X-10-WIFI-V2.py <arguments>
 Required arguments:
     -i, --interface=<wlan0>  : Name of the interface to use

 Optional arguments:
     -b, --bssid=<mac>        : BSSID of the target AP
     -p, --pin=<wps pin>      : Use the specified pin (arbitrary string or 4/8 digit pin)
     -K, --pixie-dust         : Run Pixie Dust attack
     -B, --bruteforce         : Run online bruteforce attack
     --push-button-connect    : Run WPS push button connection

 Advanced arguments:
     -d, --delay=<n>          : Set the delay between pin attempts [0]
     -w, --write              : Write AP credentials to the file on success
     -F, --pixie-force        : Run Pixiewps with --force option (bruteforce full range)
     -X, --show-pixie-cmd     : Alway print Pixiewps command
     --vuln-list=<filename>   : Use custom file with vulnerable devices list ['vulnwsc.txt']
     --iface-down             : Down network interface when the work is finished
     -l, --loop               : Run in a loop
     -r, --reverse-scan       : Reverse order of networks in the list of networks. Useful on small displays
     --mtk-wifi               : Activate MediaTek Wi-Fi interface driver on startup and deactivate it on exit
                                (for internal Wi-Fi adapters implemented in MediaTek SoCs). Turn off Wi-Fi in the system settings before using this.
     -v, --verbose            : Verbose output
 ```
#### Note: 
+ **First turn off your Wifi.**
+ **Turn on Hotspot.**
+ **Turn on Location.**


## Usage examples
Start Pixie Dust attack on a specified BSSID:
 ```
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 -b 00:90:4C:C1:AC:21 -K
 ```
Show avaliable networks and start Pixie Dust attack on a specified network:
 ```
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 -K
 ```
Launch online WPS bruteforce with the specified first half of the PIN:
 ```
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
 ```
 Start WPS push button connection:s
 ```
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 --pbc
 ```
## Troubleshooting
#### "RTNETLINK answers: Operation not possible due to RF-kill"
 Just run:
```sudo rfkill unblock wifi```
#### "Device or resource busy (-16)"
 Try disabling Wi-Fi in the system settings and kill the Network manager. Alternatively, you can try running X-10-WIFI-V2 with ```--iface-down``` argument.
#### The wlan0 interface disappears when Wi-Fi is disabled on Android devices with MediaTek SoC
 Try running X-10-WIFI-V2 with the `--mtk-wifi` flag to initialize Wi-Fi device driver.

## CONNECT WITH US :


<a href="https://github.com/Versionx10"><img title="Github" src="https://img.shields.io/badge/VERSION X-10-brightgreen?style=for-the-badge&logo=github"></a>

[![Instagram](https://img.shields.io/badge/FACEBOOK-FOLLOW-red?style=for-the-badge&logo=facebook)](https://www.facebook.com/Arifmoodz)
[![Instagram](https://img.shields.io/badge/WHATSAPP-CHAT-red?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801666666666)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-FOLLOW-red?style=for-the-badge&logo=instagram)](https://www.instagram.com/nai)
[![Instagram](https://img.shields.io/badge/WEBSITE-VISIT-yellow?style=for-the-badge&logo=blogger)](https://versionx10.co)
[![Instagram](https://img.shields.io/badge/TELEGRAM-CHANNEL-red?style=for-the-badge&logo=telegram)](https://t.me/Versionx10)

