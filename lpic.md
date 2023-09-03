## Topic 101: System Architecture
### 101.1 Determine and configure hardware settings

- /sys/
  - Sysfs is usually mounted in the /sys directory.
  - Sysfs is a pseudo filesystem provided by the Linux kernel that exports information about various kernel subsystems, hardware devices, and associated device drivers.
``` console
jadi@funlife:~$ ls /sys
block  bus  class  dev  devices  firmware  fs  hypervisor  kernel  module  power
```
- [/proc/](https://github.com/guilhermemoraes1/commands/blob/main/fhs.md#proc): **Process**
  - In /proc there are several folders with names that are just numbers. They represent every process open on the computer in user space! Folders that are not numbered are system processes.
``` console
root@localhost:~# ls /proc/
1     1302  2    285  378  4    509  624  808        cmdline      fs          kpageflags    partitions     sysvipc
10    14    20   286  390  40   59   647  9          consoles     interrupts  loadavg       sched_debug    timer_list
11    15    21   288  391  400  590  651  95         cpuinfo      iomem       locks         schedstat      timer_stats
1233  16    22   289  392  41   592  657  986        crypto       ioports     mdstat        scsi           tty
1234  17    23   30   393  42   594  665  987        devices      irq         meminfo       self           uptime
1235  1733  24   31   394  43   596  674  990        diskstats    kallsyms    misc          slabinfo       version
1241  18    278  32   395  44   597  677  acpi       dma          kcore       modules       softirqs       vmallocinfo
1249  1809  280  325  396  45   598  681  asound     driver       keys        mounts        stat           vmstat
1250  1837  281  366  397  479  599  683  buddyinfo  execdomains  key-users   mtrr          swaps          zoneinfo
1298  1852  282  367  398  496  6    7    bus        fb           kmsg        net           sys
13    19    283  377  399  5    600  8    cgroups    filesystems  kpagecount  pagetypeinfo  sysrq-trigger
```
- /dev/: **Directory containing links representing devices**
  - udev (userspace /dev) => udev controls the /dev/ directory
- modprobe
- lsmod
- lspci: **Shows [PCI devices](#pci) that are connected to the computer**
``` console
guilherme@machine:~$ lspci
00:00.0 Host bridge: ALi Corporation M1541 (rev 04)
00:01.0 PCI bridge: ALi Corporation M1541 PCI to AGP Controller (rev 04)
00:02.0 USB Controller: ALi Corporation USB 1.1 Controller (rev 03)
00:03.0 Bridge: ALi Corporation M7101 PMU
00:07.0 ISA bridge: ALi Corporation M1533 PCI to ISA Bridge [Aladdin IV] 
00:09.0 Ethernet controller: Realtek Semiconductor Co., Ltd. RTL-8139/8139C/8139C+ (rev 10)
00:0b.0 SCSI storage controller: Adaptec AHA-2940/2940W / AIC-7871
00:0f.0 IDE interface: ALi Corporation M5229 IDE (rev c1)
01:00.0 VGA compatible controller: NVidia / SGS Thomson (Joint Venture) Riva128 (rev 10)
```
- lsusb: **Displays informations about USB devices**
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

### 101.2 Boot the system

- dmesg
- journalctl
- BIOS
- UEFI
- bootloader
- kernel
- initramfs
- init
- SysVinit
- systemd

### 101.3 Change runlevels / boot targets and shutdown or reboot system

##

### Glossary

- <a name="pci"></a> PCI device: means any device that can connect into the motherboard by utilizing the PCI slot.

##

- [Playlist](https://www.youtube.com/playlist?list=PLFOYXCPEqdNUU55Xvgst8wGTWnz_sd-cj)
- [Material](https://github.com/guilhermemoraes1/all-courses/blob/main/huawei/cloud-computing/course.md)
- [Objetivos: Exame 101](https://wiki.lpi.org/wiki/LPIC-1_Objectives_V5.0(PT-BR)#Objetivos:_Exame_101)
- [LPIC-1 Exam 101](https://www.lpi.org/our-certifications/exam-101-objectives/)
