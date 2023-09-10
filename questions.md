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

LPI101(17#1) Which of the following commands reboots the system when using SysV init? (Choose TWO Answers.)
   - [x] shutdown -r now
   - [ ] shutdown -r "rebooting"
   - [x] telinit 6
   - [ ] telinit 0
   - [ ] shutdown -k now "rebooting"

##

LPI101(44#1) Which file should be edited to select the network locations from which Debian installation package files are loaded?
   - [ ] /etc/dpkg/dpkg.cfg
   - [ ] /etc/apt/apt.conf
   - [ ] /etc/apt/apt.conf.d
   - [x] /etc/apt/sources.list
   - [ ] /etc/dpkg/dselect.cfg

##

LPI101(51#1) Which of the following commands can be used to download the RPM package kernel without installing it?
   - [ ] yum download --no-install kernel
   - [x] yumdownloader kernel
   - [ ] rpm --download --package kernel
   - [ ] rpmdownload kernel

##

LPI101(60#1) Which of the following commands can be used to create a USB storage media from a disk image?
   - [ ] gdisk
   - [x] dd
   - [ ] cc
   - [ ] fdisk
   - [ ] mount

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

LPI101(81#1) Which of the following commands will send output from the program myapp to both standard output (stdout) and the file file1.log?
   - [ ] cat < myapp | cat > file1.log
   - [ ] myapp 0>&1 | cat > file1.log
   - [ ] myapp | cat > file1.log
   - [x] myapp | tee file1.log.

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

LPI101(101#1) When given the following command line. echo "foo bar" | tee bar | cat Which of the following output is created?
   - [ ] cat
   - [x] foo bar
   - [ ] tee bar
   - [ ] bar
   - [ ] foo.

##

LPI101(123#1) Which of the following Linux filesystems preallocates a fixed number of inodes at the filesystem's make/creation time and does NOT generate them as needed? (Choose TWO Answers.)
   - [ ] ext3
   - [x] JFS
   - [x] ext2
   - [ ] XFS
   - [ ] procfs.

##

LPI101(133#1) Which of the following statements is correct for a command ending with an & character?
   - [ ] The command's output is redirected to /dev/null.
   - [x] The command is run in the background of the current shell.
   - [ ] The command's output is executed by the shell.
   - [ ] The command is run as a direct child of the init process.
   - [ ] The command's input is read from /dev/null.

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

LPI101(181#1) Which of the following commands will produce the following output?
   - [ ] jobs
   - [ ] proclist
   - [ ] netstat
   - [x] ps

##

LPI101(188#1) Which of the following commands enables the setuid (suid) permission on the executable /bin/foo?
   - [ ] chmod 1755 /bin/foo
   - [x] chmod 4755 /bin/foo
   - [ ] chmod u-s /bin/foo
   - [ ] chmod 755+s /bin/foo.

##

LPI101(208#1) What is contained on the EFI System Partition?
   - [ ] The Linux root file system
   - [x] The first stage boot loader 
   - [ ] The default swap space file
   - [ ] The Linux default shell binaries
   - [ ] The user home directories

##

LPI101(223#1) Which of the following commands lists the dependencies of the RPM package file foo.rpm?
   - [x] rpm –qpR foo.rpm
   - [ ] rpm –dep foo
   - [ ] rpm –ld foo.rpm
   - [ ] rpm –R foo.rpm
   - [ ] rpm –pD foo.

##

LPI101(246#1) When in Normal mode in vi, which character can be used to begin a reverse search of the text?
   - [ ] ?
   - [ ] /
   - [ ] F
   - [x] r

##

LPI101(256#1) Which of the following commands are valid in the GRUB 2 configuration file? (Choose two.)
   - [x] menuentry
   - [ ] uefi
   - [ ] pxe-ifconfig
   - [x] insmod
   - [ ] kpartx.

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
