# Welcome to CommandPi

<p align="center">
  <img alt="this is a logo I created for this repo. it's a raspberry with two icons underneath - a shell and a red pin" width="400" height="400" src="/assets/v2c.png">
</p>

This project documents every commands I've used on my Pi. I dont make it a habit to remember any commands or flags. I just google it when I'm looking for something. I thought maybe it's a good idea to list some good ones here so I do not have to go hunting them. Yes, sometimes you get different search results - the Internet is constantly evolving. I'll sure try to keep this as updated as possible but no guarantees. 

:sparkles: What RPi do I have? :sparkles:

```
cat /proc/cpuinfo
```
Output:
```
model name      : ARMv7 Processor rev 4 (v7l)
Features        : half thumb fastmult vfp edsp neon vfpv3 tls vfpv4 idiva idivt vfpd32 lpae evtstrm crc32
CPU implementer : 0x41
CPU architecture: 7
CPU variant     : 0x0
CPU part        : 0xd03
CPU revision    : 4
Hardware        : BCM2835
Model           : Raspberry Pi 3 Model B Rev 1.2
```

## OS Installation
So this time I've installed Ubuntu Server LTS 20.04 on the Raspberry Pi. 
To get it connected to my WiFi network I had to edit the network-config file after flashing the SD Card with the OS. This was 'wpa-supplicant' when I wanted to do the same after burning Raspbian OS. 

## Software updates/upgrades
Refresh your local package index using the following command,
```
sudo apt update
apt list --upgradable
```
The commands above should get you up and running. You can find specific commands below:
# :ledger: Contents 
1. <a href="https://github.com/jaitjacob/CommandPi/blob/master/system_commands.md" target="_blank">System level</a>
2. Rarely used commands
3. Custom
4. Know your commands better
5. **work in progress**
