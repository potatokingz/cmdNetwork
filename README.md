# POTATO KING Network HUD

A simple always-on-top floating network status HUD built with Python and Tkinter.
It displays your current Wi-Fi details, ping, and network usage in a compact window labeled POTATO KING.

Features
Shows current Wi-Fi SSID, network interface card (NIC) name, connection state, and signal strength.

Displays ping latency to Google's DNS (8.8.8.8).

Monitors total data received and sent (in MB).

Always stays on top of other windows.

Minimalist black-themed UI with a small floating window.

Close button to easily exit the HUD.

Auto-updates every 3 seconds.

Requirements
Python 3.x

psutil

Windows OS (uses netsh and ping commands specific to Windows)

Install dependencies via pip:

pip install psutil

Usage
Clone or download this repository.

Run the script with Python:

python potato_hud.py

The HUD window will appear in the top-right corner of your screen.

To close, click the ❌ button.

Notes
This script uses Windows command line utilities (netsh wlan show interfaces and ping) and will only work properly on Windows.

Packet loss is hardcoded as 0 currently.

The HUD refreshes its data every 3 seconds.

License
This project is provided as-is, feel free to use and modify it for your own purposes.

Links
Potato King Website
