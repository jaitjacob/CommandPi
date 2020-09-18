# CommandPi
Just documenting every commands I've used on my Pi. I normally dont remember any commands or flags. I just google when I'm looking for something that's when it struck me that I should maybe just create a listicle like this.

## OS Installation
So this time I've installed Ubuntu Server LTS 20.04 on the Raspberry Pi. 
To get it connected to my WiFi network I had to edit the network-config file after flashing the SD Card with the OS. This was 'wpa-supplicant' when I wanted to do the same after burning Raspbian OS. 

## Software updates/upgrades
Refresh your local package index using the following command,
```
sudo apt update
apt list --upgradable
```
