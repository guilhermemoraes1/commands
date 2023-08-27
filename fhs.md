## Filesystem Hierarchy Standard (FHS)

It is a set of guidelines and specifications for organizing the file system structure of a Linux-based operating system. 

``` console
[root@localhost /]# ls /
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
```

- **/bin**: Essential system binaries (commands) that are required for the system's basic operation.

```console
[root@localhost /]# ls /bin
[                                   elfedit                isosize             nisdomainname             readelf                         tac
addr2line                           env                    jobs                nl                        readlink                        tail
alias                               envsubst               join                nl-addr-add               realpath                        tailf
apropos                             eqn                    journalctl          nl-addr-delete            recode-sr-latin                 tar
ar                                  ex                     kbdinfo             nl-addr-list              rename                          taskset
arch                                expand                 kbd_mode            nl-class-add              renice                          tbl
as                                  expr                   kbdrate             nl-class-delete           reset                           teamd
aserver                             factor                 kdumpctl            nl-classid-lookup         resizecons                      teamdctl
aulast                              fallocate              kernel-install      nl-class-list             rev                             teamnl
aulastlog                           false                  kill                nl-cls-add                rm                              tee
ausyscall                           fc                     kmod                nl-cls-delete             rmail                           test
auvirt                              fg                     last                nl-cls-list               rmail.postfix                   testgdbm
awk                                 fgconsole              lastb               nl-fib-lookup             rmdir                           tic
base64                              fgrep                  lastlog             nl-link-enslave           rpcgen                          timedatectl
basename                            file                   lchfn               nl-link-ifindex2name      rpm                             timeout
bash                                find                   lchsh               nl-link-list              rpm2cpio                        tload
bashbug                             findmnt                ld                  nl-link-name2ifindex      rpmdb                           tmon
bashbug-64                          fipscheck              ld.bfd              nl-link-release           rpmkeys                         toe
bc                                  fipshmac               ldd                 nl-link-set               rpmquery                        top
bg                                  firewall-cmd           ld.gold             nl-link-stats             rpmverify                       touch
bond2team                           firewall-offline-cmd   less                nl-list-caches            rsyslog-recover-qi.pl           tput
bootctl                             flock                  lessecho            nl-list-sockets           runcon                          tr
busctl                              fmt                    lesskey             nl-monitor                run-parts                       tracepath
cal                                 fold                   lesspipe.sh         nl-neigh-add              rvi                             tracepath6
ca-legacy                           free                   lexgrog             nl-neigh-delete           rview                           troff
captoinfo                           gapplication           link                nl-neigh-list             scp                             true
cat                                 gawk                   linux32             nl-neightbl-list          script                          truncate
catchsegv                           gdbus                  linux64             nl-pktloc-lookup          scriptreplay                    trust
catman                              gencat                 linux-boot-prober   nl-qdisc-add              sdiff                           tset
cd                                  genl-ctrl-list         ln                  nl-qdisc-delete           secon                           tsort
centrino-decode                     geqn                   loadkeys            nl-qdisc-list             sed                             tty
certutil                            getconf                loadunimap          nl-route-add              seq                             turbostat
c++filt                             getent                 locale              nl-route-delete           setarch                         tzselect
chacl                               getfacl                localectl           nl-route-get              setfacl                         udevadm
chage                               getkeycodes            localedef           nl-route-list             setfont                         ul
chattr                              getopt                 logger              nl-rule-list              setkeycodes                     umask
chcon                               getopts                login               nl-tctree-list            setleds                         umount
chfn                                gettext                loginctl            nl-util-addr              setmetamode                     unalias
chgrp                               gettext.sh             logname             nm                        setpriv                         uname
chmem                               gio                    look                nmcli                     setsid                          unexpand
chmod                               gio-querymodules-64    ls                  nm-online                 setterm                         unicode_start
chown                               glib-compile-schemas   lsattr              nmtui                     setup-nsssysinit                unicode_stop
chronyc                             gmake                  lsblk               nmtui-connect             setup-nsssysinit.sh             uniq
chrt                                gneqn                  lscpu               nmtui-edit                setvtrgb                        unlink
chsh                                gnroff                 lsinitrd            nmtui-hostname            sftp                            unlz4
chvt                                gpasswd                lsipc               nohup                     sg                              unshare
cksum                               gpg                    lslocks             nproc                     sh                              unxz
clear                               gpg2                   lslogins            nroff                     sha1sum                         update-ca-trust
cmp                                 gpg-agent              lsmem               nsenter                   sha224sum                       update-mime-database
cmsutil                             gpgconf                lsns                nss-policy-check          sha256sum                       uptime
col                                 gpg-connect-agent      lsscsi              numfmt                    sha384sum                       urlgrabber
colcrt                              gpg-error              lua                 objcopy                   sha512sum                       users
colrm                               gpgparsemail           luac                objdump                   showconsolefont                 usleep
column                              gpgsplit               lz4                 od                        showkey                         usx2yloader
comm                                gpgv                   lz4c                oldfind                   shred                           utmpdump
command                             gpgv2                  lz4cat              open                      shuf                            uuidgen
coredumpctl                         gpg-zip                machinectl          openssl                   signver                         vdir
cp                                  gpic                   mailq               openvt                    size                            vi
cpio                                gprof                  mailq.postfix       os-prober                 skill                           view
cpupower                            grep                   make                p11-kit                   slabinfo                        vlock
crlutil                             groff                  makedb              page_owner_sort           slabtop                         vmstat
crontab                             grops                  man                 passwd                    sleep                           vxloader
csplit                              grotty                 mandb               paste                     slogin                          w
csslint-0.6                         groups                 manpath             pathchk                   snice                           wait
curl                                grub2-editenv          mapscrn             pchrt                     soelim                          wall
cut                                 grub2-file             mcookie             pflags                    sort                            watch
cvtsudoers                          grub2-fstest           md5sum              pgawk                     sotruss                         watchgnupg
date                                grub2-glue-efi         mesg                pgrep                     split                           wc
db_archive                          grub2-kbdcomp          mixartloader        pic                       sprof                           wdctl
db_checkpoint                       grub2-menulst2cfg      mkdir               pinentry                  sqlite3                         whatis
db_deadlock                         grub2-mkfont           mkfifo              pinentry-curses           ssh                             whereis
db_dump                             grub2-mkimage          mkinitrd            ping                      ssh-add                         which
db_dump185                          grub2-mklayout         mknod               ping6                     ssh-agent                       whiptail
db_hotbackup                        grub2-mknetdir         mktemp              pinky                     ssh-copy-id                     who
db_load                             grub2-mkpasswd-pbkdf2  modutil             pk12util                  ssh-keygen                      whoami
db_log_verify                       grub2-mkrelpath        more                pkaction                  ssh-keyscan                     write
db_printlog                         grub2-mkrescue         mount               pkcheck                   ssltap                          x86_64
db_recover                          grub2-mkstandalone     mountpoint          pkexec                    stat                            x86_energy_perf_policy
db_replicate                        grub2-render-label     msgattrib           pkg-config                stdbuf                          xargs
db_stat                             grub2-script-check     msgcat              pkill                     strings                         xgettext
db_tuner                            grub2-syslinux2cfg     msgcmp              pkla-admin-identities     strip                           xmlcatalog
db_upgrade                          gsettings              msgcomm             pkla-check-authorization  stty                            xmllint
dbus-binding-tool                   gsoelim                msgconv             pkttyagent                su                              xmlwf
dbus-cleanup-sockets                gtar                   msgen               pldd                      sudo                            xz
dbus-daemon                         gtbl                   msgexec             plymouth                  sudoedit                        xzcat
dbus-monitor                        gtroff                 msgfilter           pmap                      sudoreplay                      xzcmp
dbus-run-session                    gunzip                 msgfmt              post-grohtml              sum                             xzdec
dbus-send                           gzexe                  msggrep             powernow-k8-decode        sync                            xzdiff
dbus-test-tool                      gzip                   msghack             pr                        systemctl                       xzegrep
dbus-update-activation-environment  hdsploader             msginit             preconv                   systemd-analyze                 xzfgrep
dbus-uuidgen                        head                   msgmerge            pre-grohtml               systemd-ask-password            xzgrep
db_verify                           hexdump                msgunfmt            printenv                  systemd-cat                     xzless
dc                                  hostid                 msguniq             printf                    systemd-cgls                    xzmore
dd                                  hostname               mv                  prlimit                   systemd-cgtop                   yes
deallocvt                           hostnamectl            namei               ps                        systemd-coredumpctl             ypdomainname
df                                  i386                   ndptool             psfaddtable               systemd-delta                   yum
dgawk                               iconv                  neqn                psfgettable               systemd-detect-virt             zcat
diff                                id                     newaliases          psfstriptable             systemd-escape                  zcmp
diff3                               idiag-socket-details   newaliases.postfix  psfxtable                 systemd-firstboot               zdiff
dir                                 idn                    newgidmap           ptaskset                  systemd-hwdb                    zegrep
dircolors                           igawk                  newgrp              ptx                       systemd-inhibit                 zfgrep
dirname                             info                   newuidmap           pwd                       systemd-loginctl                zforce
dmesg                               infocmp                nf-ct-add           pwdx                      systemd-machine-id-setup        zgrep
dnsdomainname                       infokey                nf-ct-list          pwmake                    systemd-notify                  zless
domainname                          infotocap              nf-exp-add          pwscore                   systemd-nspawn                  zmore
dracut                              install                nf-exp-delete       pydoc                     systemd-path                    znew
du                                  ionice                 nf-exp-list         python                    systemd-run                     zsoelim
dumpkeys                            ipcalc                 nf-log              python2                   systemd-stdio-bridge
dwp                                 ipcmk                  nf-monitor          python2.7                 systemd-sysv-convert
echo                                ipcrm                  nf-queue            ranlib                    systemd-tmpfiles
egrep                               ipcs                   ngettext            raw                       systemd-tty-ask-password-agent
eject                               iptables-xml           nice                read                      tabs
```
- **/sbin**: System binaries (commands) for system administration.

``` console
[root@localhost /]# ls /usr/sbin
accessdb              cracklib-unpacker          groupadd                   lnstat             nl-qdisc-add                rtstat                     userdel
addgnupghome          create-cracklib-dict       groupdel                   load_policy        nl-qdisc-delete             runlevel                   usermod
addpart               crond                      groupmems                  logrotate          nl-qdisc-list               runuser                    usernetctl
adduser               ctrlaltdel                 groupmod                   logsave            nologin                     sasldblistusers2           vgcfgbackup
agetty                ctstat                     grpck                      losetup            nstat                       saslpasswd2                vgcfgrestore
alternatives          debugfs                    grpconv                    lpasswd            ownership                   sefcontext_compile         vgchange
anacron               delpart                    grpunconv                  lsmod              packer                      selabel_digest             vgck
applygnupgdefaults    depmod                     grub2-bios-setup           luseradd           pam_console_apply           selabel_lookup             vgconvert
arpd                  devlink                    grub2-get-kernel-settings  luserdel           pam_tally2                  selabel_lookup_best_match  vgcreate
arping                dhclient                   grub2-install              lusermod           pam_timestamp_check         selabel_partial_match      vgdisplay
audispd               dhclient-script            grub2-macbless             lvchange           parted                      selinuxconlist             vgexport
auditctl              dmeventd                   grub2-mkconfig             lvconvert          partprobe                   selinuxdefcon              vgextend
auditd                dmfilemapd                 grub2-ofpathname           lvcreate           partx                       selinuxenabled             vgimport
augenrules            dmidecode                  grub2-probe                lvdisplay          pdata_tools                 selinuxexeccon             vgimportclone
aureport              dmsetup                    grub2-reboot               lvextend           pidof                       selinux_restorecon         vgmerge
ausearch              dmstats                    grub2-rpm-sort             lvm                ping6                       semodule                   vgmknodes
authconfig            dracut                     grub2-set-default          lvmconf            pivot_root                  sendmail                   vgreduce
authconfig-tui        dumpe2fs                   grub2-setpassword          lvmconfig          plymouthd                   sendmail.postfix           vgremove
autrace               e2freefrag                 grub2-sparc64-setup        lvmdiskscan        plymouth-set-default-theme  service                    vgrename
avcstat               e2fsck                     grubby                     lvmdump            postalias                   sestatus                   vgs
badblocks             e2image                    halt                       lvmetad            postcat                     setcap                     vgscan
biosdecode            e2label                    hardlink                   lvmpolld           postconf                    setenforce                 vgsplit
biosdevname           e2undo                     hwclock                    lvmsadc            postdrop                    setfiles                   vigr
blkdeactivate         e4defrag                   iconvconfig                lvmsar             postfix                     setsebool                  vipw
blkdiscard            eapol_test                 iconvconfig.x86_64         lvreduce           postkick                    sfdisk                     virt-what
blkid                 ebtables                   ifcfg                      lvremove           postlock                    shutdown                   visudo
blockdev              ebtables-restore           ifdown                     lvrename           postlog                     sln                        vmcore-dmesg
bridge                ebtables-save              ifenslave                  lvresize           postmap                     smtp-sink                  vpddecode
btrfs                 era_check                  ifstat                     lvs                postmulti                   smtp-source                weak-modules
btrfsck               era_dump                   ifup                       lvscan             postqueue                   ss                         wipefs
btrfs-convert         era_invalidate             init                       makedumpfile       postsuper                   sshd                       wpa_cli
btrfs-debug-tree      era_restore                insmod                     matchpathcon       poweroff                    sshd-keygen                wpa_passphrase
btrfs-find-root       ethtool                    install-info               mkdict             ppp-watch                   sulogin                    wpa_supplicant
btrfs-image           faillock                   installkernel              mkdumprd           pvchange                    sushell                    xfs_admin
btrfs-map-logical     fdformat                   intel-microcode2ucode      mke2fs             pvck                        swaplabel                  xfs_bmap
btrfs-select-super    fdisk                      ip                         mkfs               pvcreate                    swapoff                    xfs_copy
btrfstune             filefrag                   ip6tables                  mkfs.btrfs         pvdisplay                   swapon                     xfs_db
btrfs-zero-log        findfs                     ip6tables-restore          mkfs.cramfs        pvmove                      switch_root                xfs_estimate
build-locale-archive  firewalld                  ip6tables-save             mkfs.ext2          pvremove                    sysctl                     xfs_freeze
cacertdir_rehash      fixfiles                   iprconfig                  mkfs.ext3          pvresize                    sys-unconfig               xfs_fsr
cache_check           fsadm                      iprdbg                     mkfs.ext4          pvs                         tc                         xfs_growfs
cache_dump            fsck                       iprdump                    mkfs.minix         pvscan                      telinit                    xfs_info
cache_metadata_size   fsck.btrfs                 iprinit                    mkfs.xfs           pwck                        thin_check                 xfs_io
cache_repair          fsck.cramfs                iprsos                     mkhomedir_helper   pwconv                      thin_delta                 xfs_logprint
cache_restore         fsck.ext2                  iprupdate                  mklost+found       pwhistory_helper            thin_dump                  xfs_mdrestore
cache_writeback       fsck.ext3                  ipset                      mkswap             pwunconv                    thin_ls                    xfs_metadump
capsh                 fsck.ext4                  iptables                   modinfo            rdisc                       thin_metadata_size         xfs_mkfile
cbq                   fsck.minix                 iptables-restore           modprobe           rdma                        thin_repair                xfs_ncheck
cfdisk                fsck.xfs                   iptables-save              netreport          readprofile                 thin_restore               xfs_quota
chcpu                 fsfreeze                   irqbalance                 NetworkManager     reboot                      thin_rmap                  xfs_repair
chgpasswd             fstrim                     kexec                      new-kernel-pkg     resize2fs                   thin_trim                  xfs_rtcp
chkconfig             fxload                     killall5                   newusers           resizepart                  tracepath                  xtables-multi
chpasswd              genhomedircon              kpartx                     nl-class-add       restorecon                  tracepath6                 zdump
chronyd               genhostid                  lchage                     nl-class-delete    rmmod                       tune2fs                    zic
chroot                genl                       ldattach                   nl-classid-lookup  routef                      tuned                      zramctl
clock                 genl-ctrl-list             ldconfig                   nl-class-list      routel                      tuned-adm
clockdiff             getcap                     lgroupadd                  nl-cls-add         rsyslogd                    udevadm
consoletype           getenforce                 lgroupdel                  nl-cls-delete      rtacct                      unix_chkpwd
cracklib-check        getpcaps                   lgroupmod                  nl-cls-list        rtcwake                     unix_update
cracklib-format       getsebool                  lid                        nl-link-list       rtmon                       update-alternatives
cracklib-packer       glibc_post_upgrade.x86_64  lnewusers                  nl-pktloc-lookup   rtpr                        useradd
```

- **/boot**: essential files needed for the initial boot process of the Linux operating system.
``` console
[root@localhost /]# ls /boot
config-3.10.0-1160.el7.x86_64  initramfs-0-rescue-668865503faa314f87516a6b7659ff5b.img  vmlinuz-0-rescue-668865503faa314f87516a6b7659ff5b
efi                            initramfs-3.10.0-1160.el7.x86_64.img                     vmlinuz-3.10.0-1160.el7.x86_64
grub                           symvers-3.10.0-1160.el7.x86_64.gz
grub2                          System.map-3.10.0-1160.el7.x86_64
```

- **
``` console

```
