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
