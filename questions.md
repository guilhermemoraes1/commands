When planning a partition scheme, which of the following directories could be considered for separate partitions? (Choose three.)
- [ ] /etc
- [x] /home
- [x] /var
- [ ] /lib
- [x] /opt

##

LPI101 The system is having trouble and the engineer wants to bypass the usual /sbin/init start up and run /bin/sh. What is the usual way to pass this change to the kernel from your boot loader?
   - [ ] Start in runlevel 1.
   - [x] Pass init=/bin/sh on the kernel parameter line.
   - [ ] Pass /bin/sh on the kernel parameter line.
   - [ ] Pass start=/bin/sh on the kernel parameter line.

##

LPI101(3#1) Which of the following options for the kernel's command line changes the systemd boot target to rescue.target instead of the default target?
   - [ ] systemd.target=rescue.target
   - [ ] systemd.runlevel=rescue.target
   - [ ] systemd.service=rescue.target
   - [ ] systemd.default=rescue.target
   - [x] systemd.unit=rescue.target.

##

LPI101(8#1) During a system boot cycle, what is the program that is run after the BIOS completes its tasks?
   - [ ] The bootloader
   - [ ] The inetd program
   - [ ] The init program
   - [x] The kernel

##

LPI101(12#1) Which of the following kernel parameters instructs the kernel to suppress most boot messages?
   - [ ] silent
   - [ ] verbose=0
   - [ ] nomesg
   - [x] quiet

##

LPI101(17#1) Which of the following commands reboots the system when using SysV init? (Choose TWO Answers.)
   - [x] shutdown -r now
   - [ ] shutdown -r "rebooting"
   - [x] telinit 6
   - [ ] telinit 0
   - [ ] shutdown -k now "rebooting"

##

LPI101(39#1) Which of the following environment variables overrides or extends the list of directories holding shared libraries?
   - [ ] LD_LOAD_PATH
   - [ ] LD_LIB_PATH
   - [x] LD_LIBRARY_PATH
   - [ ] LD_SHARE_PATH
   - [ ] LD_RUN_PATH

##

LPI101(44#1) Which file should be edited to select the network locations from which Debian installation package files are loaded?
   - [ ] /etc/dpkg/dpkg.cfg
   - [ ] /etc/apt/apt.conf
   - [ ] /etc/apt/apt.conf.d
   - [x] /etc/apt/sources.list
   - [ ] /etc/dpkg/dselect.cfg

##

LPI101(46#1) Which of the following commands overwrites the bootloader located on /dev/sda without overwriting the partition table or any data following it?
   - [ ] dd if=/dev/zero of=/dev/sda bs=512
   - [ ] dd if=/dev/zero of=/dev/sda bs=512 count=1
   - [x] dd if=/dev/zero of=/dev/sda bs=440 count=1
   - [ ] dd if=/dev/zero of=/dev/sda bs=440

##

LPI101(51#1) Which of the following commands can be used to download the RPM package kernel without installing it?
   - [ ] yum download --no-install kernel
   - [x] yumdownloader kernel
   - [ ] rpm --download --package kernel
   - [ ] rpmdownload kernel

##

LPI101(52#1) Which function key is used to start Safe Mode in Windows NT?
   - [ ] F10
   - [ ] F8
   - [ ] F6
   - [x] Windows NT does not support Safe Mode

##

LPI101(58#1) What is the maximum niceness value that a regular user can assign to a process with the nice command when executing a new process?
   - [ ] 9
   - [x] 19
   - [ ] 49
   - [ ] 99

##

LPI101(60#1) Which of the following commands can be used to create a USB storage media from a disk image?
   - [ ] gdisk
   - [x] dd
   - [ ] cc
   - [ ] fdisk
   - [ ] mount

##

LPI101(67#1) Which of the following files, located in the user home directory, is used to store the Bash history?
   - [x] .bash_history
   - [ ] .bash_histfile
   - [ ] .history
   - [ ] .bashrc_history
   - [ ] .history_bash

##

LPI101(69#1) Which of the following statements is correct regarding the command foo 1> bar?
   - [ ] The stdout from the command foo is appended to the file bar.
   - [x] The stdout from the command foo overwrites the file bar.
   - [ ] The command foo receives its stdin from the file bar.
   - [ ] The command foo receives its stdin from the stdout of the command bar.
   - [ ] The stderr from the command foo is saved to the file bar.

##

LPI101(70#1) Which of the following commands displays the contents of a gzip compressed tar archive?
   - [ ] gzip archive.tgz | tar xvf
   - [ ] tar ztf archive.tgz
   - [ ] gzip -d archive.tgz | tar tvf
   - [ ] tar cf archive.tgz.

##

LPI101(78#1) Which of the following commands is used to change options and positional parameters for a running Bash?
   - [ ] history
   - [x] set
   - [ ] bashconf
   - [ ] setsh
   - [ ] envsetup

##

LPI101(80#1) Which of the following command sets the Bash variable named TEST with the content FOO?
   - [ ] set TEST="FOO"
   - [ ] TEST = "FOO"
   - [ ] var TEST="FOO"
   - [x] TEST="FOO"

##

LPI101(81#1) Which of the following commands will send output from the program myapp to both standard output (stdout) and the file file1.log?
   - [ ] cat < myapp | cat > file1.log
   - [ ] myapp 0>&1 | cat > file1.log
   - [ ] myapp | cat > file1.log
   - [x] myapp | tee file1.log.

##

LPI101(84#1) Which of the following commands can be used to determine how long the system has been running? (Choose TWO Answers.)
   - [x] uptime
   - [ ] up
   - [x] top
   - [ ] uname -u
   - [ ] time –up

##

LPI101(85#1) Which of the following commands will reduce all consecutive spaces down to a single space?
   - [ ] tr '\s' ' ' < a.txt > b.txt
   - [ ] tr -c ' ' < a.txt > b.txt
   - [ ] tr -d ' ' < a.txt > b.txt
   - [ ] tr -r ' ' '\n' < a.txt > b.txt
   - [x] tr -s ' ' < a.txt > b.txt.

##

LPI101(86#1) From a Bash shell, which of the following commands directly executes the instruction from the file /usr/local/bin/runme.sh without starting a subshell? (Please select TWO answers.)
   - [ ] source /usr/local/bin/runme.sh
   - [ ] ./usr/local/bin/runme.sh
   - [ ] /bin/bash /usr/local/bin/runme.sh
   - [x] /usr/local/bin/runme.sh
   - [ ] run /usr/local/bin/runme.sh

##

LPI101(88#1) When running the command sed -e "s/a/b/" /tmp/file >/tmp/file While /tmp/file contains data, why is /tmp/file empty afterwards?
   - [ ] The file order is incorrect. The destination file must be mentioned before the command to ensure redirection.
   - [ ] The command sed did not match anything in that file therefore the output is empty.
   - [x] When the shell establishes the redirection it overwrites the target file before the redirected command starts and opens it for reading.
   - [ ] Redirection for shell commands do not work using the > character. It only works using the | character instead.

##

LPI101(89#1) Which of the following explanations are valid reasons to run a command in the background of your shell?
   - [ ] The command does not need to execute immediately.
   - [ ] The command has to run immediately but the user needs to log out.
   - [x] The system is being shut down and the command needs to restart execution immediately after the reboot.
   - [ ] The command can run at a lower priority than normal commands run on the command line.

##

LPI101(91#1) What is the purpose of the Bash built-in export command?
   - [ ] It allows disks to be mounted remotely.
   - [ ] It runs a command as a process in a subshell.
   - [ ] It makes the command history available to subshells.
   - [x] It sets up environment variables for applications.
   - [ ] It shares NFS partitions for use by other systems on the network.

##

LPI101(92#1) What is the effect of the egrep command when the -v option is used?
   - [ ] It enables color to highlight matching parts.
   - [x] It only outputs non-matching lines.
   - [ ] It shows the command's version information.
   - [ ] It changes the output order showing the last matching line first.

##

LPI101(94#1) Which character, added to the end of a command, runs that command in the background as a child process of the current shell?
   - [ ] !
   - [ ] +
   - [x] &
   - [ ] %
   - [ ] #

##

LPI101(95#1) In Bash, inserting 1>&2 after a command redirects
   - [ ] standard error to standard input.
   - [ ] standard input to standard error.
   - [ ] standard output to standard error.
   - [x] standard error to standard output.
   - [ ] standard output to standard input.

##

LPI101(99#1) Which shell command is used to continue background execution of a suspended command?
   - [ ] &
   - [x] bg
   - [ ] cont
   - [ ] exec
   - [ ] :&

##

LPI101(101#1) When given the following command line. echo "foo bar" | tee bar | cat Which of the following output is created?
   - [ ] cat
   - [x] foo bar
   - [ ] tee bar
   - [ ] bar
   - [ ] foo.

##

LPI101(104#1) Which of the following signals is sent to a process when the key combination CTRL+C is pressed on the keyboard?
   - [ ] SIGTERM
   - [ ] SIGCONT
   - [ ] SIGSTOP
   - [ ] SIGKILL
   - [x] SIGINT

##

LPI101(106#1) Immediately after deleting 3 lines of text in vi and moving the cursor to a different line, which single character command will insert the deleted content below the current line?
   - [ ] i (lowercase)
   - [ ] P (uppercase)
   - [ ] p (lowercase)
   - [ ] U (uppercase)
   - [x] u (lowercase)

##

LPI101(117#1) Which of the following settings for umask ensures that new files have the default permissions -rw-r--- -- ?
   - [ ] 0017
   - [ ] 0640
   - [ ] 0038
   - [ ] 0027
   - [x] 0227

##

LPI101(122#1) Which of the following commands creates an ext3 filesystem on /dev/sdb1? (Choose TWO Answers.)
   - [x] /sbin/mke2fs -j /dev/sdb1
   - [x] /sbin/mkfs -t ext3 /dev/sdb1
   - [ ] /sbin/mkfs -c ext3 /dev/sdb1
   - [ ] /sbin/mke3fs -j /dev/sdb1

##

LPI101(123#1) Which of the following Linux filesystems preallocates a fixed number of inodes at the filesystem's make/creation time and does NOT generate them as needed? (Choose TWO Answers.)
   - [ ] ext3
   - [x] JFS
   - [x] ext2
   - [ ] XFS
   - [ ] procfs.

##

LPI101(125#1) Which of the following commands updates the already installed RPM package rpmname?
   - [ ] rpm --update rpmname
   - [x] rpm –U rpmname
   - [ ] rpm –q rpmname
   - [ ] rpm --force rpmname
   - [ ] rpm –i rpmname

##

LPI101(130#1) In order to display all currently mounted filesystems, which of the following commands could be used? (Choose TWO Answers.)
   - [x] cat /proc/self/mounts
   - [ ] free
   - [ ] mount
   - [x] lsmounts
   - [ ] cat /proc/filesystems

##

LPI101(133#1) Which of the following statements is correct for a command ending with an & character?
   - [ ] The command's output is redirected to /dev/null.
   - [x] The command is run in the background of the current shell.
   - [ ] The command's output is executed by the shell.
   - [ ] The command is run as a direct child of the init process.
   - [ ] The command's input is read from /dev/null.

##

LPI101(136#1) Which of the following examples for Bash file globbing matches a file named root-can-dothis.txt when used in the directory holding that file? (Choose three Answers.)
   - [x] root*can?do-this.{txt,odt}
   - [ ] r[oOoO]t-can-do*.txt
   - [x] {root,user,admin}-can-??-this.txt
   - [ ] root*can*do??this.txt
   - [x] root***{can,may}-do-this.[tT][xX][tT]

##

LPI101(137#1) Which of the following commands print the current working directory when using a Bash shell? (Choose two.)
   - [x] echo “${PWD}”
   - [ ] echo “${WD}”
   - [x] pwd
   - [ ] printwd
   - [ ] echo '${pwd}'

##

LPI101(142#1) Which signal is sent by the kill command by default?
   - [ ] SIGHUP(1)
   - [ ] SIGQUIT(3)
   - [ ] SIGKILL(9)
   - [x] SIGTERM(15)

##

LPI101(143#1) Creating a hard link to an ordinary file returns an error. What could be the reason for this?
   - [ ] The source file is hidden.
   - [ ] The source file is read-only.
   - [ ] The source file is a shell script.
   - [ ] The source file is already a hard link.
   - [x] The source and the target are on different filesystems.

##

LPI101(145#1) Instead of supplying an explicit device in /etc/fstab for mounting, what other options may be used to identify the intended partition? (Choose TWO Answers.)
   - [ ] FIND
   - [ ] ID
   - [x] LABEL
   - [ ] NAME
   - [x] UUID

##

LPI101(146#1) When using regular expressions, which of the following characters match the beginning of a line?
   - [x] ^
   - [ ] ?
   - [ ] *
   - [ ] +
   - [ ] $

##

LPI101(150#1) Which of the following commands changes the ownership of file.txt to the user dan and the group staff?
   - [ ] chown dan/staff file.txt
   - [x] chown dan:staff file.txt
   - [ ] chown -u dan -g staff file.txt
   - [ ] chown dan -g staff file.txt

##

LPI101(154#1) In Bash, inserting 2>&1 after a command redirects:
   - [ ] standard error to standard input.
   - [ ] standard input to standard error.
   - [ ] standard output to standard error.
   - [x] standard error to standard output.
   - [ ] standard output to standard input.

##

LPI101(164#1) Which of the following is true for hard linked files? (Choose three.)
   - [ ] The output of stat will report hard instead of regular file.
   - [x] The hard linked files have the same permissions and owner.
   - [x] The hard linked files share the same inode.
   - [ ] The hard linked files are indicated by a -> when listed with ls -l.
   - [ ] The hard linked files must be on the same filesystem.

##

LPI101(173#1) Which of the following commands makes /bin/foo executable by everyone but writable only by its owner?
   - [x] chmod u=rwx,go=rx /bin/foo
   - [ ] chmod o+rwx,a+rx /bin/foo
   - [ ] chmod 577 /bin/foo
   - [ ] chmod 775 /bin/foo.

##

LPI101(174#1) Which of the following commands can be used to create a new file that is 100kB in size?
   - [x] dd
   - [ ] file
   - [ ] mkfile
   - [ ] touch

##

LPI101(181#1) Which of the following commands will produce the following output?
   - [ ] jobs
   - [ ] proclist
   - [ ] netstat
   - [x] ps

##

LPI101(184#1) Where does the BIOS search for a bootloader?
   - [ ] On all connected storage media regardless of the boot device order.
   - [x] On all connected storage media in the defined boot device order.
   - [ ] Only on hard disk drives in the defined boot device order.
   - [ ] Only on the last added storage media.
   - [ ] The BIOS is not responsible to search for a valid bootloader.

##

LPI101(188#1) Which of the following commands enables the setuid (suid) permission on the executable /bin/foo?
   - [ ] chmod 1755 /bin/foo
   - [x] chmod 4755 /bin/foo
   - [ ] chmod u-s /bin/foo
   - [ ] chmod 755+s /bin/foo.

##

LPI101(192#1) Which of the following commands will change all CR-LF pairs in an imported text file, userlist.txt, to Linux standard LF characters and store it as newlist.txt?
   - [x] tr ‘\r\n’ ‘’ < userlist.txt > newlist.txt
   - [ ] tr –c ‘\n\r’ ‘’ < newlist.txt > userlist.txt
   - [ ] tr –d ‘\r’ < userlist.txt > newlist.txt
   - [ ] tr ‘\r’ ‘\n’ userlist.txt newlist.txt
   - [ ] tr –s ‘^M’ ‘^J’ userlist.txt newlist.txt

##

LPI101(197#1) Which of the following are filesystems which can be used on Linux root partitions? (Choose two.)
   - [ ] NTFS
   - [x] ext3
   - [ ] XFS
   - [ ] VFAT
   - [ ] swap

##

LPI101(199#1) Which of the following commands set the sticky bit for the directory /tmp? (Choose TWO Answers.)
   - [ ] chmod +s /tmp
   - [x] chmod +t /tmp
   - [x] chmod 1775 /tmp
   - [ ] chmod 4775 /tmp
   - [ ] chmod 2775 /tmp

##

LPI101(204#1) Which of the following commands installs all packages with a name ending with the string foo?
   - [ ] zypper get “*foo”
   - [ ] zypper update “foo?”
   - [ ] zypper force “foo*”
   - [ ] zypper install “*foo”
   - [x] zypper add “.*foo”

##

LPI101(208#1) What is contained on the EFI System Partition?
   - [ ] The Linux root file system
   - [x] The first stage boot loader 
   - [ ] The default swap space file
   - [ ] The Linux default shell binaries
   - [ ] The user home directories

##

LPI101(213#1) Which of the following vi commands deletes two lines, the current and the following line?
   - [ ] d2
   - [ ] 2d
   - [x] 2dd
   - [ ] dd2
   - [ ] de12

##

LPI101(216#1) Which of the following statements are true about the boot sequence of a PC using a BIOS? (Choose two.)
   - [ ] Some parts of the boot process can be configured from the BIOS
   - [ ] Linux does not require the assistance of the BIOS to boot a computer
   - [ ] The BIOS boot process starts only if secondary storage, such as the hard disk, is functional
   - [x] The BIOS initiates the boot process after turning the computer on
   - [ ] The BIOS is started by loading hardware drivers from secondary storage, such as the hard disk.

##

LPI101(223#1) Which of the following commands lists the dependencies of the RPM package file foo.rpm?
   - [x] rpm –qpR foo.rpm
   - [ ] rpm –dep foo
   - [ ] rpm –ld foo.rpm
   - [ ] rpm –R foo.rpm
   - [ ] rpm –pD foo.

##

LPI101(224#1) Which is the default percentage of reserved space for the root user on new ext4 filesystems?
   - [ ] 10%
   - [ ] 3%
   - [ ] 15%
   - [ ] 0%
   - [x] 5%

##

LPI101(225#1) What is true regarding the command ls > files if files does not exist?
   - [ ] The output of ls is printed to the terminal
   - [ ] files is created and contains the output of ls
   - [ ] An error message is shown and ls is not executed
   - [ ] The command files is executed and receives the output of ls
   - [x] Any output of ls is discarded

##

LPI101(228#1) Which of the following commands displays the path to the executable file that would be executed when the command foo is invoked?
   - [ ] lsattr foo
   - [ ] apropos foo
   - [ ] locate foo
   - [ ] whatis foo
   - [x] which foo

##

LPI101(231#1) Which of the following regular expressions represents a single upper-case letter?
   - [ ] :UPPER:
   - [x] [A-Z]
   - [ ] !a-z
   - [ ] %C
   - [ ] {AZ}

##

LPI101(232#1) Which of the following apt-get subcommands installs the newest versions of all currently installed packages?
   - [ ] auto-update
   - [x] dist-upgrade
   - [ ] full-upgrade
   - [ ] install
   - [ ] update

##

LPI101(233#1) Which daemon handles power management events on a Linux system?
   - [x] acpid
   - [ ] batteryd
   - [ ] pwrmgntd
   - [ ] psd
   - [ ] inetd

##

LPI101(239#1) Which of the following files exist in a standard GRUB 2 installation? (Choose two.)
   - [ ] /boot/grub/stages/stage0
   - [x] /boot/grub/i386-pc/1vm.mod
   - [ ] /boot/grub/fstab
   - [x] /boot/grub/grub.cfg
   - [ ] /boot/grub/linux/vmlinuz

##

LPI101(246#1) When in Normal mode in vi, which character can be used to begin a reverse search of the text?
   - [ ] ?
   - [ ] /
   - [ ] F
   - [x] r

##

LPI101(249#1) Which of the following commands installs the GRUB boot files into the currently active file systems and the boot loader into the first partition of the first disk?
   - [x] grub-install /dev/sda
   - [ ] grub-install /dev/sda1
   - [ ] grub-install current /dev/sda0
   - [ ] grub-install /dev/sda0
   - [ ] grub-install current /dev/sda1

##

LPI101(255#1) Which of the following commands lists all currently installed packages when using RPM package management?
   - [ ] yum --query --all
   - [ ] yum --list --installed
   - [ ] rpm --query --list
   - [ ] rpm --list --installed
   - [x] rpm --query --all

##

LPI101(256#1) Which of the following commands are valid in the GRUB 2 configuration file? (Choose two.)
   - [x] menuentry
   - [ ] uefi
   - [ ] pxe-ifconfig
   - [x] insmod
   - [ ] kpartx.

##

LPI101(261#1) Running chmod 640 filea.txt as a regular user doesn't update filea.txt's permission. What might be a reason why chmod cannot modify the permissions? (Choose two.)
   - [ ] filea.txt is owned by another user and a regular user cannot change the permissions of another user's file.
   - [ ] filea.txt is a symbolic link whose permissions are a fixed value which cannot be changed.
   - [ ] filea.txt has the sticky bit set and a regular user cannot remove this permission.
   - [ ] filea.txt is a hard link whose permissions are inherited from the target and cannot be set directly.
   - [x] filea.txt has the SetUID bit set which imposes the restriction that only the root user can make changes to the file.

##

LPI101(268#1) Which of the following commands display the IDs of all processes owned by root? (Choose two.)
   - [ ] pgrep -c root
   - [x] pgrep -u root
   - [ ] pgrep -f root
   - [ ] pgrep -U 0
   - [ ] pgrep -c 

##

LPI101(262#1) Which of the following commands sets the SetUID permission on the executable /bin/foo?
   - [x] chmod 4755 /bin/foo
   - [ ] chmod 1755 /bin/foo
   - [ ] chmod u-s /bin/foo
   - [ ] chmod 755+s /bin/foo
   - [ ] chmod 2755 /bin/foo

##

LPI101(274#1) If the gzip compressed tar archive texts.tgz contains the files a.txt and b.txt, which files will be present in the current directory after running gunzip texts.tgz?
   - [ ] Only a.txt, b.txt, and texts.tgz
   - [ ] Only texts.tar and texts.tgz
   - [ ] Only a.txt.gz and b.txt.gz
   - [x] Only a.txt and b.txt.

##
