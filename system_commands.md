# System Commands

1. **df**

df (display filesystem) command displays information about the disk space usage of all mounted filesystems.
```
ubuntu@ubuntu:/$ df
Filesystem     1K-blocks    Used Available Use% Mounted on
udev              389968       0    389968   0% /dev
tmpfs              87336    3956     83380   5% /run
/dev/mmcblk0p2  61065904 2199280  56340228   4% /
tmpfs             436668       0    436668   0% /dev/shm
/dev/loop0         46592   46592         0 100% /snap/core18/1882
/dev/mmcblk0p1    258095   91643    166452  36% /boot/firmware
tmpfs              87332       0     87332   0% /run/user/1000
/dev/loop3         46848   46848         0 100% /snap/core18/1889
```
2. **Kill a process associated with a port**

Sometimes when I run a webserver it happens ever so that the port it was listening on does not get released. I have to manually kill the process to free the port. 

```sudo kill -9 `sudo lsof -t -i: <insert port number her> ```

3. **Display CPU information**
```cat /proc/cpuinfo```
```Output:
MemTotal:         873336 kB
MemFree:          494668 kB
MemAvailable:     712460 kB
Buffers:           33728 kB
Cached:           176244 kB
SwapCached:            0 kB
```

# Display memory information
```cat /proc/meminfo```
```Output:
processor       : 0
model name      : ARMv7 Processor rev 4 (v7l)
BogoMIPS        : 38.40
Features        : half thumb fastmult vfp edsp neon vfpv3 tls vfpv4 idiva idivt vfpd32 lpae evtstrm crc32
CPU implementer : 0x41
CPU architecture: 7
CPU variant     : 0x0
CPU part        : 0xd03
CPU revision    : 4
```
