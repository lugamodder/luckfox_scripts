***update_mac*** - A simple script that generates a persistent MAC address based on the board's serial number and adds it to /etc/networking/interfaces. For Alpine Linux 3.18.
```
cp update_mac /etc/network/if-pre-up.d/update_mac
chmod +x /etc/network/if-pre-up.d/update_mac
```
