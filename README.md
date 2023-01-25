# Basic Wireless Intrusion Detection System  

BWIDS is a simple WiFi network monitoring system.  

It allows monitoring of connected hosts and detection of the following attacks:
+ Man In The Middle
+ Deauthentication Attack
+ Fake Access Point  

It is recommended to use the script on the interface with monitoring mode enabled, in order to detect more vulnerabilities.  

Sudo privileges are required.

# Installation  
```
git clone https://github.com/AlpenGod/bwids  
cd bwids  
sudo pip3 install -r requirements.txt
```

# Usage  
```
sudo python3 bwids.py --iface IFACE --router_mac ROUTER_MAC
```
