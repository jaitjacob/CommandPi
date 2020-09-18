# CommandPi
Just documenting every commands I've used on my Pi. I normally dont remember any commands or flags. I just google when I'm looking for something that's when it struck me that I should maybe just create a listicle like this.

:sparkles: What RPi do I have? :sparkles:

```
cat /proc/cpuinfo
```
Output:
```
processor       : 0
model name      : ARMv7 Processor rev 4 (v7l)
BogoMIPS        : 51.20
Features        : half thumb fastmult vfp edsp neon vfpv3 tls vfpv4 idiva idivt vfpd32 lpae evtstrm crc32
CPU implementer : 0x41
CPU architecture: 7
CPU variant     : 0x0
CPU part        : 0xd03
CPU revision    : 4
Hardware        : BCM2835
Revision        : a2
Serial          : ####
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
2. rarely used commands
3. custom
4. know your commands better
5.
6.
