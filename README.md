# 📡 rasap
🍓 Raspberry Pi WiFi Access Point

## 🚀 Quick installer

Start with a clean install of Raspberry Pi OS (64-bit) Lite.

🔄 Update your OS:

```
sudo apt-get update
sudo apt-get full-upgrade
sudo reboot
```
🌍 Set WiFi country:
```
sudo raspi-config
```
📥 Install RaspAP:
```
curl -sL https://install.raspap.com | bash
```
The installer will complete setup automatically. Reboot when prompted. 🔄

## ⚙️ Default settings

📶 WiFi AP configuration:
```
IP address: 10.3.141.1
Username: admin
Password: secret
DHCP range: 10.3.141.50 — 10.3.141.254
SSID: RaspAP
Password: ChangeMe
```
🔗 Change these default credentials in RaspAP's Authentication and Hotspot > Security panels.