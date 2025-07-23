
# 🔓 LEWRA_WPS — WiFi WPS Attack Tool by ARIF BROH

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=35F700&background=3C8BFF00&random=false&width=435&lines=Thanks+for+using+LEWRA_WPS;Don't+forget+to+star+the+repo!;Created+by+Arif+Broh+👨‍💻)](https://git.io/typing-svg)

<p align="center">
  <img src="https://i.postimg.cc/s2PTvxxG/wifihack4.jpg" width="600" />
</p>

## ⚠️ Disclaimer

> **LEWRA_WPS is a penetration testing tool. Use it only on networks you own or have explicit permission to test. Unauthorized use is illegal and unethical.**

---

## 🛠️ What is LEWRA_WPS?

**LEWRA_WPS** is a fast and aggressive WPS attack tool designed for Termux and Linux systems. It scans for WPS-enabled networks and automates PIN-based attacks using:

- ✅ Pixie Dust Attack
- ✅ Online WPS PIN Bruteforce
- ✅ Offline PIN logic using public algorithms

---

## 🚀 Features

- 📶 Scan nearby WPS-enabled access points
- 🔐 Brute-force WPS PIN using known techniques
- 🧠 Pixie Dust vulnerability exploitation
- 🧰 Supports various WiFi chipsets and interface options
- 🕵️ Anonymous attack logging (optional)

---

## 🧰 Requirements

- Termux / Linux with **root access**
- Python 3.6+
- `wpa_supplicant`, `pixiewps`, `iw`
- Compatible WiFi adapter (supporting monitor mode recommended)

---

## 📦 Installation

```bash
pkg update && pkg upgrade -y
pkg install git tsu python wpa-supplicant pixiewps iw -y
git clone https://github.com/arifbroh351/LEWRA_WPS
cd LEWRA_WPS
sudo python LEWRA_WPS.py -i wlan0 -K
```

---

## 🧪 Usage

```bash
python LEWRA_WPS.py [options]
```

### Basic Examples:
- Start Pixie Dust attack:
  ```bash
  sudo python LEWRA_WPS.py -i wlan0 -K
  ```
- Brute-force with known PIN:
  ```bash
  sudo python LEWRA_WPS.py -i wlan0 -p 12345670 -B
  ```
- Push-button WPS connect:
  ```bash
  sudo python LEWRA_WPS.py -i wlan0 --pbc
  ```

---

## 📸 Screenshots

<p align="center">
  <img width="45%" src=""/>
  <img width="45%" src=""/>
</p>

---

## 🔄 Update

```bash
cd LEWRA_WPS && git pull
```

---

## 🧼 Uninstall

```bash
rm -rf LEWRA_WPS
```

---

## 📡 Connect With Me

- 🌐 [GitHub: arifbroh351](https://github.com/arifbroh351)
- 📘 [Facebook](https://www.facebook.com/arifbroh351)
- 📱 [WhatsApp](https://wa.me/+8801612600351)
- 📷 [Instagram](https://www.instagram.com/arifbroh351)
- 🔗 [Telegram Channel](https://t.me/ARIF_MODZ)

---

## ❤️ Special Thanks

- `Wiire` for Pixiewps
- `DRYGDRYG` and `rofl0r` for WPS logic
- `Mohammad Al Amin` for contributions
- `Farhan Muh Tasim` for inspiration & codebase structure

---

## ☕ Support My Work

If this tool helped you, consider supporting:

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/arifbroh351)

---

> 💣 **LEWRA_WPS was made for professionals, pentesters, and enthusiasts. Always use responsibly.**
