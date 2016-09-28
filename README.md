# Spoofer 
##### Wifi hack to auto spoof your mac address for public wifi that enforces time limits based on mac address, aka: Panera Bread's public wifi. 
* Ensure you've commented #HWADDR in /etc/sysconfig/network-scripts/ifcfg-<wifi>
* requires sudo/root perms for /dev/urandom and ifconfig

**Usage: sh /path/2/spoofer/spoofer <NIC> <TIME-INTERVAL>**
