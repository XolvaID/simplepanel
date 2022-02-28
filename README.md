# Free Open Source Simple XolPanel
Copas code ke VPS:
```
apt update && apt upgrade
apt install python3 python3-pip git
git clone https://github.com/xolvaid/simplepanel.git
unzip simplepanel/xolpanel.zip
nano xolpanel/var.txt # Isi bot token, ID telegram, & domain VPS
pip3 install -r xolpanel/requirements.txt
pip3 install pillow
mv xolpanel/xolpanel.service /etc/systemd/system/
systemctl start xolpanel && systemctl enable xolpanel
```
- Buka Bot, ketik .menu
- kendala / emror?, Lapor di <a href="https://t.me/XolPanelDC">sini</a>
