# X-10-WIFI-V2 

> ⚠️ **Note:** Root access is **required**.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=35F700&background=3C8BFF00&random=false&width=435&lines=Thanks+for+use+my+command+;please+don't+forget+start+;Hi+I'm+ARIF_MODZ;Facebook%3A+Arifmoodz)](https://git.io/typing-svg)



---

### 👋 Hello, Welcome

**Hack WiFi** using **X-10-WIFI-V2** by Termux/Android, by `ARIF 😫`!

![Developer](https://i.postimg.cc/6Q0XPjdt/IMG-20240404-202439-804.jpg)

---

## 📶 HACK WIFI

<p align="center">
  <img src="https://user-images.githubusercontent.com/75953873/115979290-66309900-a55b-11eb-8259-4b125efc42bb.png">
</p>

[![Python 3.5](https://img.shields.io/badge/Python-3.5-yellow.svg)](http://www.python.org/download/)
[![Python 2.7](https://img.shields.io/badge/python-2.7-brightgreen.svg)](https://www.python.org/downloads/release/python-2714/)
[![OS](https://img.shields.io/badge/Tested%20On-Linux%20%7C%20Android-yellowgreen.svg)](https://termux.com/)

---

## 📥 Installation

### Step 1

```bash
pkg update && pkg upgrade && pkg install -y root-repo && pkg install -y git tsu python wpa-supplicant pixiewps iw openssl && termux-setup-storage
```

### Step 2

```bash
git clone --depth 1 https://github.com/Versionx10/X-10-WIFI-V2
```

### Step 3

```bash
sudo python X-10-WIFI-V2/X-10-WIFI-V2.py -i wlan0 -K
```

---

## 🧠 Overview

**X-10-WIFI-V2** performs a [Pixie Dust attack](https://forums.kali.org/showthread.php?24286-WPS-Pixie-Dust-Attack-Offline-WPS-Attack) without switching to monitor mode.

### Features
- Pixie Dust attack
- 3WiFi offline WPS PIN generator
- Online WPS bruteforce
- Wi-Fi scanner using `iw`

---

## 📦 Requirements

- Python 3.6+
- [wpa_supplicant](https://www.w1.fi/wpa_supplicant/)
- [pixiewps](https://github.com/wiire-a/pixiewps)
- [iw](https://wireless.wiki.kernel.org/en/users/documentation/iw)

> ⚠️ **Note:** Root access is **required**.

---

## 📲 Usage

```bash
X-10-WIFI-V2.py <arguments>
```

### Required
- `-i, --interface=<wlan0>`  : Interface to use

### Optional
- `-b, --bssid=<mac>`        : Target AP MAC address
- `-p, --pin=<wps pin>`      : Custom 4/8 digit WPS pin
- `-K, --pixie-dust`         : Pixie Dust attack
- `-B, --bruteforce`         : Online WPS bruteforce
- `--push-button-connect`    : WPS Push Button attack

### Advanced
- `-d, --delay=<n>`          : Delay between pin attempts
- `-w, --write`              : Save credentials
- `-F, --pixie-force`        : Bruteforce full PIN range
- `-X, --show-pixie-cmd`     : Show Pixiewps command
- `--vuln-list=<filename>`   : Use custom vulnerable device list
- `--iface-down`             : Disable interface after attack
- `-l, --loop`               : Run in loop
- `-r, --reverse-scan`       : Reverse network scan order
- `--mtk-wifi`               : Support MediaTek WiFi chips
- `-v, --verbose`            : Verbose output

---

## ⚠️ Pre-Usage Note

- Turn off **WiFi**
- Turn on **Hotspot**
- Turn on **Location**

---

## 💡 Examples

```bash
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 -b 00:90:4C:C1:AC:21 -K
```

```bash
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 -K
```

```bash
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
```

```bash
cd X-10-WIFI-V2 && sudo python3 X-10-WIFI-V2.py -i wlan0 --pbc
```

---

## 🛠️ Troubleshooting

**Problem:** `RTNETLINK answers: Operation not possible due to RF-kill`  
**Solution:**  
```bash
sudo rfkill unblock wifi
```

**Problem:** `Device or resource busy (-16)`  
**Solution:**  
Disable Wi-Fi and Network Manager, or run with `--iface-down`.

**Problem:** Interface disappears on MediaTek SoC  
**Solution:**  
Run with `--mtk-wifi` flag

---

## 🤝 Connect With Us

[![Github](https://img.shields.io/badge/VERSION X-10-brightgreen?style=for-the-badge&logo=github)](https://github.com/Versionx10)
[![Facebook](https://img.shields.io/badge/FACEBOOK-FOLLOW-red?style=for-the-badge&logo=facebook)](https://www.facebook.com/Arifmoodz)
[![WhatsApp](https://img.shields.io/badge/WHATSAPP-CHAT-red?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801666666666)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-FOLLOW-red?style=for-the-badge&logo=instagram)](https://www.instagram.com/nai)
[![Website](https://img.shields.io/badge/WEBSITE-VISIT-yellow?style=for-the-badge&logo=blogger)](https://versionx10.co)
[![Telegram](https://img.shields.io/badge/TELEGRAM-CHANNEL-red?style=for-the-badge&logo=telegram)](https://t.me/Versionx10)
