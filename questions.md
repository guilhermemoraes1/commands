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

LPI101(14#1) Which of the following commands will write a message to the terminals of all logged in users?
   - [ ] bcast
   - [ ] mesg
   - [ ] print
   - [x] wall
   - [ ] yell

##

LPI101(17#1) Which of the following commands reboots the system when using SysV init? (Choose TWO Answers.)
   - [x] shutdown -r now
   - [ ] shutdown -r "rebooting"
   - [x] telinit 6
   - [ ] telinit 0
   - [ ] shutdown -k now "rebooting"

##

LPI101(21#1) Which of the following commands brings a system running SysV init into a state in which it is safe to perform maintenance tasks? (Choose TWO Answers.)
   - [ ] shutdown -R 1 now
   - [ ] shutdown -single now
   - [x] init 1
   - [x] telinit 1
   - [ ] runlevel 1

##

LPI101(36#1) Which of the following commands updates the linker cache of shared libraries?
   - [ ] mkcache
   - [ ] soconfig
   - [ ] mkldconfig
   - [ ] lddconfig
   - [x] ldconfig

##

LPI101(39#1) Which of the following environment variables overrides or extends the list of directories holding shared libraries?
   - [ ] LD_LOAD_PATH
   - [ ] LD_LIB_PATH
   - [x] LD_LIBRARY_PATH
   - [ ] LD_SHARE_PATH
   - [ ] LD_RUN_PATH

##

LPI101(43#1) Which of the following commands lists all currently installed packages when using RPM package management?
   - [ ] yum --query --all
   - [ ] yum --list --installed
   - [x] rpm --query --all
   - [ ] rpm --list –installed

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

LPI101(62#1) What is the difference between the i and a commands of the vi editor?
   - [ ] i (interactive) requires the user to explicitly switch between vi modes whereas a (automatic) switches modesautomatically.
   - [x] i (insert) inserts text before the current cursor position whereas a (append) inserts text after the cursor.
   - [ ] i (independent rows) starts every new line at the first character whereas a (aligned rows) keeps the indentation of the previous line.
   - [ ] i (interrupt) temporarily suspends editing of a file to the background whereas a (abort) terminates editing.

##

LPI101(65#1) What happens after issuing the command vi without any additional parameters?
   - [ ] vi starts and loads the last file used andmoves the cursor to the position where vi was when it last exited.
   - [ ] vi starts and requires the user to explicitly either create a new or load an existing file.
   - [ ] vi exits with an error message as it cannot be invoked without a file name to operate on.
   - [x] vi starts in command mode and opens a new empty file.
   - [ ] vi starts and opens a new file which is filled with the content of the vi buffer if the buffer contains text.

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
   - [x] The command has to run immediately but the user needs to log out.
   - [ ] The system is being shut down and the command needs to restart execution immediately after the reboot.
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

LPI101(96#1) Which variable defines the directories in which a Bash shell searches for executable commands?
   - [ ] BASHEXEC
   - [ ] BASHRC
   - [x] PATH
   - [ ] EXECPATH
   - [ ] PATHRC

##

LPI101(97#1) Regarding the command: nice -5 /usr/bin/prog Which of the following statements is correct?
   - [ ] /usr/bin/prog is executed with a nice level of -5.
   - [x] /usr/bin/prog is executed with a nice level of 5.
   - [ ] /usr/bin/prog is executed with a priority of -5.
   - [ ] /usr/bin/prog is executed with a priority of 5.

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

LPI101(116#1) After successfully creating a hard link called bar to the ordinary file foo, foo is deleted from the filesystem. Which of the following describes the resulting situation?
   - [ ] foo and bar would both be removed.
   - [x] foo would be removed while bar would remain accessible.
   - [ ] foo would be removed. bar would still exist but would be unusable.
   - [ ] Both foo and bar would remain accessible.
   - [ ] The user is prompted whether bar should be removed, too.

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

LPI101(140#1) Which of the following are modes of the vi editor? (Choose two.)
   - [ ] edit mode
   - [x] insert mode
   - [ ] change mode
   - [ ] review mode
   - [x] command mode

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

LPI101(151#1) Which of the following partition types is used for Linux swap spaces when partitioning hard disk drives?
   - [x] 82
   - [ ] 83
   - [ ] 8e
   - [ ] fd
   - [ ] 7

##

LPI101(152#1) Which permissions and ownership should the file /etc/passwd have?
   - [ ] -rw-------1 rootroot531 Jun 5 22:45 /etc/passwd
   - [x] -rw-r--r--1 rootroot531 Jun 5 22:45 /etc/passwd
   - [ ] -rw-r--r--1 11531 Jun 5 22:45 /etc/passwd
   - [ ] -rw-------1 11531 Jun 5 22:45 /etc/passwd

##

LPI101(153#1) Which of the following commands can be used to search for the executable file foo when it has been placed in a directory not included in $PATH?
   - [ ] apropos
   - [ ] which
   - [x] find
   - [ ] query
   - [ ] whereis

##

LPI101(154#1) In Bash, inserting 2>&1 after a command redirects:
   - [ ] standard error to standard input.
   - [ ] standard input to standard error.
   - [ ] standard output to standard error.
   - [x] standard error to standard output.
   - [ ] standard output to standard input.

##

LPI101(156#1) Which of the following commands will change the quota for a specific user?
   - [x] edquota
   - [ ] repquota
   - [ ] quota -e
   - [ ] quota

##

LPI101(157#1) Which type of filesystem is created by mkfs when it is executed with the block device name only and without any additional parameters?
   - [x] ext2
   - [ ] ext3
   - [ ] ext4
   - [ ] XFS
   - [ ] VFAT

##

LPI101(160#1) In compliance with the FHS, in which of the following directories are documentation files found?
   - [ ] /usr/share/documentation
   - [ ] /usr/local/share/documentation
   - [ ] /var/share/doc
   - [x] /usr/share/doc
   - [ ] /etc/share/doc

##

LPI101(163#1) Which of the following commands are common Linux commands for file management? (Choose three Answers.)
   - [ ] copy
   - [ ] mv
   - [x] move
   - [x] cp
   - [x] mkdir

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

LPI101(177#1) Which of the following commands can be used to display the inode number of a given file? (Choose two.)
   - [ ] inode
   - [ ] ln
   - [x] ls
   - [ ] cp
   - [x] stat

##

LPI101(181#1) Which of the following commands will produce the following output?
   - [ ] jobs
   - [ ] proclist
   - [ ] netstat
   - [x] ps

##

LPI101(182#1) Which of the following describes the correct order in which the components of the system boot process are started?
   - [ ] BIOS, kernel, bootloader, init system
   - [x] BIOS, bootloader,kernel, init system
   - [ ] Bootloader, BIOS, kernel, init system
   - [ ] BIOS, bootloader, init system, kernel
   - [ ] Bootloader, BIOS, init system, kernel

##

LPI101(183#1) Which of the following commands instructs SysVinit to reload its configuration file?
   - [ ] reinit
   - [ ] initreload
   - [ ] telinit 7
   - [x] telinit q
   - [ ] init reinit

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

LPI101(189#1) What does the command mount -a do?
   - [ ] It mounts all available filesystems onto the current directory.
   - [ ] It shows all mounted filesystems.
   - [ ] It mounts all user mountable filesystems for thecurrent user.
   - [x] It mounts all filesystems listed in /etc/fstab which have the option auto set.
   - [ ] It mounts all filesystems listed in /etc/fstab which have the option noauto set.

##

LPI101(190#1) After running the command umount /mnt, the following error message is displayed: umount: /mnt: device is busy. What is a common reason for this message?
   - [ ] The kernel has not finished flushing disk writes to the mounted device.
   - [x] A user has a file open in the /mnt directory.
   - [ ] Another file system still contains a symlink to a file inside /mnt.
   - [ ] The files in /mnt have been scanned and added to the locate database.
   - [ ] The kernel thinks that a process is about to open a file in /mnt for reading.

##

LPI101(192#1) Which of the following commands will change all CR-LF pairs in an imported text file, userlist.txt, to Linux standard LF characters and store it as newlist.txt?
   - [x] tr ‘\r\n’ ‘’ < userlist.txt > newlist.txt
   - [ ] tr –c ‘\n\r’ ‘’ < newlist.txt > userlist.txt
   - [ ] tr –d ‘\r’ < userlist.txt > newlist.txt
   - [ ] tr ‘\r’ ‘\n’ userlist.txt newlist.txt
   - [ ] tr –s ‘^M’ ‘^J’ userlist.txt newlist.txt

##

LPI101(195#1) What is the purpose of the xargs command?
   - [ ] It passes arguments to an X server.
   - [x] It reads standard input (STDIN) and builds up command lines to execute.
   - [ ] It helps shellscripts take variable argument lists.
   - [ ] It asks a question, graphically, and returns the answer to the shell.
   - [ ] It allows users to specify long options for commands that normally only accept short options.

##

LPI101(196#1) Which of the following is a limitation of the cut command?
   - [ ] Thecutcommand can only select output by field position.
   - [x] Thecutcommand cannot reorder fields.
   - [ ] Thecutcommand only works on ASCIItext.
   - [ ] Thecutcommand cannot use different input and output delimiters.

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

LPI101(203#1) What is true regarding UEFI firmware? (Choose two.)
   - [x] It can read and interpret partition tables
   - [x] It can use and read certain file systems
   - [ ] It stores its entire configuration on the /boot/ partition
   - [ ] It is stored in a special area within the GPT metadata
   - [ ] It is loaded from a fixed boot disk position

##

LPI101(204#1) Which of the following commands installs all packages with a name ending with the string foo?
   - [ ] zypper get “*foo”
   - [ ] zypper update “foo?”
   - [ ] zypper force “foo*”
   - [ ] zypper install “*foo”
   - [x] zypper add “.*foo”

##

LPI101(206#1) When redirecting the output of find to the xargs command, what option to find is useful if the filenames contain spaces?
   - [ ] –rep-space
   - [ ] –printnul
   - [ ] –nospace
   - [ ] –ignore-space
   - [x] –print0

##

LPI101(208#1) What is contained on the EFI System Partition?
   - [ ] The Linux root file system
   - [x] The first stage boot loader 
   - [ ] The default swap space file
   - [ ] The Linux default shell binaries
   - [ ] The user home directories

##

LPI101(212#1) Which of the following commands changes all CR-LF line breaks in the text file userlist.txt to Linux standard LF line breaks and stores the result in newlist.txt?
   - [x] tr –d ‘\r’ < userlist.txt > newlist.txt
   - [ ] tr –c ‘\n\r’ ‘’ <newlist.txt> userlist.txt
   - [ ] tr ‘\r\n’ ‘’ <userlist.txt> newlist.txt
   - [ ] tr ‘\r’ ‘\n’ userlist.txt newlist.txt
   - [ ] tr –s ‘/^M/^J/’ userlist.txt newlist.txt

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

LPI101(226#1) Which of the following directories on a 64 bit Linux system typically contain shared libraries? (Choose two.)
   - [ ] ~/.lib64/
   - [x] /usr/lib64/
   - [ ] /var/lib64/
   - [x] /lib64/
   - [ ] /opt/lib64/

##

LPI101(227#1) A faulty kernel module is causing issues with a network interface card. Which of the following actions ensures that this module is not loaded automatically when the system boots?
   - [ ] Using lsmod --remove --autoclean without specifying the name of a specific module
   - [ ] Using modinfo –k followed by the name of the offending module
   - [ ] Using modprobe –r followed by the name of the offending module
   - [x] Adding a blacklist line including the name of the offending module to the file /etc/modprobe.d/blacklist.conf
   - [ ] Deleting the kernel module’s directory from the file system and recompiling the kernel, including its modules

##

LPI101(228#1) Which of the following commands displays the path to the executable file that would be executed when the command foo is invoked?
   - [ ] lsattr foo
   - [ ] apropos foo
   - [ ] locate foo
   - [ ] whatis foo
   - [x] which foo

##

LPI101(230#1) When considering the use of hard links, what are valid reasons not to use hard links?
   - [ ] Hard links are not available on all Linux systems because traditional filesystems, such as ext4, do not support them
   - [ ] Each hard link has individual ownership, permissions and ACLs which can lead to unintended disclosure of file content
   - [x] Hard links are specific to one filesystem and cannot point to files on another filesystem
   - [ ] If users other than root should be able to create hard links, suln has to be installed and configured
   - [ ] When a hard linked file is changed, a copy of the file is created and consumes additional space

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

LPI101(247#1) A yum repository can declare sets of related packages. Which yum command installs all packages belonging to the group admintools?
   - [ ] yum pkgsel --install admintools
   - [ ] yum install admintools/*
   - [x] yum groupinstall admintools
   - [ ] yum taskinstall admintools
   - [ ] yum collection install admintools

##

LPI101(249#1) Which of the following commands installs the GRUB boot files into the currently active file systems and the boot loader into the first partition of the first disk?
   - [x] grub-install /dev/sda
   - [ ] grub-install /dev/sda1
   - [ ] grub-install current /dev/sda0
   - [ ] grub-install /dev/sda0
   - [ ] grub-install current /dev/sda1

##

LPI101(253#1) Which of the following statements are correct when comparing Linux containers with traditional virtual machines (e.g. LXC vs. KVM)? (Choose three.)
   - [x] Containers are a lightweight virtualization method where the kernel controls process isolation and resource management.
   - [x] Fully virtualized machines can run any operating system for a specific hardware architecture within the virtual machine.
   - [ ] Containers are completely decoupled from the host system's physical hardware and can only use emulated virtual hardware devices.
   - [ ] The guest environment for fully virtualized machines is created by a hypervisor which provides virtual and emulated hardware devices.
   - [x] Containers on the same host can use different operating systems, as the container hypervisor creates separate kernel execution.

#

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

LPI101(262#1) Which of the following commands sets the SetUID permission on the executable /bin/foo?
   - [x] chmod 4755 /bin/foo
   - [ ] chmod 1755 /bin/foo
   - [ ] chmod u-s /bin/foo
   - [ ] chmod 755+s /bin/foo
   - [ ] chmod 2755 /bin/foo

##

LPI101(263#1) After a power outage, the XFS file system of /dev/sda3 is inconsistent. How can the existing file system errors be fixed?
   - [ ] By using mount -f to force a mount of the file system
   - [ ] By running xfsck on the file system
   - [ ] By mounting the file system with the option xfs_repair
   - [ ] By running xfsadmin repair on the file system
   - [x] By running xfs_repair on the file system

##

LPI101(264#1) Which of the following properties of an existing file changes when a hard link pointing to that file is created?
   - [ ] File size
   - [x] Link count
   - [ ] Modify timestamp
   - [ ] Inode number
   - [ ] Permissions

##

LPI101(267#1) Which of the following commands is used to change options and positional parameters within a running Bash shell?
   - [ ] history
   - [ ] setsh
   - [ ] bashconf
   - [x] set
   - [ ] envsetup

##

LPI101(268#1) Which of the following commands display the IDs of all processes owned by root? (Choose two.)
   - [ ] pgrep -c root
   - [x] pgrep -u root
   - [ ] pgrep -f root
   - [ ] pgrep -U 0
   - [ ] pgrep -c 

##

LPI101(270#1) Which of the following tools can show the complete path of an executable file that the current shell would execute when starting a command without specifying its complete path? (Choose two.)
   - [ ] find
   - [ ] pwd
   - [x] which
   - [x] locate
   - [ ] type

##

LPI101(272#1) Which of the following commands outputs test to the shell?
   - [ ] cat <!EOT test EOT
   - [ ] cat <|EOT test EOT
   - [ ] cat !<EOT test EOT
   - [ ] cat &<EOT test EOT
   - [x] cat <<EOT test EOT

##

LPI101(274#1) If the gzip compressed tar archive texts.tgz contains the files a.txt and b.txt, which files will be present in the current directory after running gunzip texts.tgz?
   - [ ] Only a.txt, b.txt, and texts.tgz
   - [ ] Only texts.tar and texts.tgz
   - [ ] Only a.txt.gz and b.txt.gz
   - [x] Only a.txt and b.txt.

##

LPI101(277#1) When booting from the hard disk, a computer successfully loads the Linux kernel and initramfs but hangs during the subsequent startup tasks. The system is booted using a Linux based rescue CD to investigate the problem. Which of the following methods helps to identify the root cause of the problem?
   - [ ] Using the dmesg command from the rescue CD's shell to view the original system's boot logs.
   - [ ] Investigating the file /proc/kmsg on the computer's hard disk for possible errors.
   - [x] Investigating the file /var/log on the computer's hard disk for possible errors.
   - [ ] Using chroot to switch to the file system on the hard disk and use dmesg to view the logs.
   - [ ] Rebooting again from the hard drive since the system successfully booted from the rescue CD.

##

LPI101(278#1) Where is the bootloader stored on the hard disk of a UEFI system?
   - [ ] In the EFI Boot Record (EBR).
   - [ ] In the Master Boot Record (MBR).
   - [x] On the EFI System Partition (ESP).
   - [ ] On the partition labeled boot.
   - [ ] On the partition number 127.

##

LPI101(280#1) Which of the following statements are correct about the initial RAM disk involved in the boot process of Linux? (Choose two.)
   - [x] An initramfs is a compressed file system archive, which can be unpacked to examine its contents.
   - [ ] An initramfs file contains the MBR, the bootloader and the Linux kernel.
   - [ ] After a successful boot, the initramfs contents are available in /run/initramfs/.
   - [x] The kernel uses the initramfs temporarily before accessing the real root file system.
   - [ ] An initramfs does not depend on a specific kernel version and is not changed after the initial installation.
