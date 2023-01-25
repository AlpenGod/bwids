# Basic Wireless Intrusion Detection System  

BWIDS is a simple WiFi network monitoring system.  
It allows monitoring of connected hosts and detection of the following attacks:
+ Man In The Middle
+ Deauthentication Attack
+ Fake Access Point


# Installation  
git clone https://github.com/AlpenGod/bwids
cd bwids
sudo pip3 install -r requirements.txt

# Usage  
sudo python3 bwids.py --iface=IFACE --router_mac=ROUTER_MAC
