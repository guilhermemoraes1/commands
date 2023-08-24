## Topic 101: System Architecture
### 101.1 Determine and configure hardware settings

- /sys/
  - Sysfs is usually mounted in the /sys directory.
  - Sysfs is a pseudo filesystem provided by the Linux kernel that exports information about various kernel subsystems, hardware devices, and associated device drivers.
``` console
jadi@funlife:~$ ls /sys
block  bus  class  dev  devices  firmware  fs  hypervisor  kernel  module  power
```
- /proc/: **process**
  - In /proc there are several folders with names that are just numbers. They represent every process open on the computer in user space! Folders that are not numbered are system processes.
``` console
guilherme@machine:~$ ls /proc
1      1439  1657   1927   20284  334   750   97             locks
10     1444  1661   1928   20307  3640  753   98             mdstat
101    1447  1662   19309  20338  374   755   988            meminfo
1030   1457  1665   1935   20363  3856  756   acpi           misc
1031   1461  1668   1938   20373  4     765   asound         modules
1032   1476  1671   19596  207    409   766   bootconfig     mounts
1033   1478  1677   1963   21     413   773   buddyinfo      mtrr
1034   1479  1678   1968   2142   425   8     bus            net
1035   1480  1707   1970   215    429   80    cgroups        pagetypeinfo
104    1483  1717   1972   2151   434   805   cmdline        partitions
105    1486  173    1976   216    435   81    consoles       pressure
106    1490  1736   19771  2161   5     818   cpuinfo        schedstat
11     1495  174    19810  2168   589   819   crypto         scsi
1125   1498  1741   1983   217    590   82    devices        self
115    15    1744   19854  2184   591   8220  diskstats      slabinfo
118    1503  1748   1987   22     592   8241  dma            softirqs
1193   1504  1749   19876  2282   593   8255  driver         spl
12     1505  175    19886  2283   594   83    dynamic_debug  stat
12430  1506  176    19998  2297   595   84    execdomains    swaps
12434  1514  1765   2      2306   596   85    fb             sys
1244   1544  177    20     24     597   86    filesystems    sysrq-trigger
1251   1552  1771   20004  2424   598   87    fs             sysvipc
1257   1557  1775   20087  25     599   88    interrupts     thread-self
126    1561  178    2009   2506   6     90    iomem          timer_list
13     1566  179    20094  26     600   910   ioports        tty
1302   1570  18     2011   27     644   92    irq            uptime
1315   1571  18179  20113  277    647   935   kallsyms       version
1344   1584  182    2012   278    709   936   kcore          version_signature
1345   1590  1859   20158  28     710   94    keys           vmallocinfo
1352   1591  19     20185  29     717   946   key-users      vmstat
1354   16    1901   20198  3      723   947   kmsg           zoneinfo
1356   1613  1906   20209  30     726   948   kpagecgroup
1359   1633  1907   20210  31     741   949   kpagecount
1360   1634  1919   20219  32     748   95    kpageflags
14     1642  1921   20269  33     749   951   loadavg
```
- /dev/: **directory containing links representing devices**
  - udev (userspace /dev) => udev controls the /dev/ directory
- modprobe
- lsmod
- lspci
- lsusb: displays informations about USB devices
``` console
guilherme@machine:~$ lsusb
Bus 002 Device 003: ID 1c4f:0026 SiGma Micro Keyboard
Bus 002 Device 002: ID 8087:0024 Intel Corp. Integrated Rate Matching Hub
Bus 002 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 001 Device 005: ID 04f2:b217 Chicony Electronics Co., Ltd Lenovo Integrated Camera (0.3MP)
Bus 001 Device 004: ID 0a5c:217f Broadcom Corp. BCM2045B (BDC-2.1)
Bus 001 Device 003: ID 192f:0916 Avago Technologies, Pte.
Bus 001 Device 002: ID 8087:0024 Intel Corp. Integrated Rate Matching Hub
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
```

##

- [Playlist](https://www.youtube.com/playlist?list=PLFOYXCPEqdNUU55Xvgst8wGTWnz_sd-cj)
- [Material](https://github.com/guilhermemoraes1/all-courses/blob/main/huawei/cloud-computing/course.md)
- [Objetivos: Exame 101](https://wiki.lpi.org/wiki/LPIC-1_Objectives_V5.0(PT-BR)#Objetivos:_Exame_101)
