### Command -options arguments

- `apt update`: 
- `apt upgrade`:
- `cat`: Used to concatenate and display the content of text files.
- `cd`: Change directory.
- `clear`: Clear the screen and remove previous text or output.
- `dmesg`: Used to display the [kernel ring buffer](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-ring-buffer).
- `exit`: Used to terminate a terminal session or close a shell.
- `file`: determine the type of a file by examining its content, rather than relying solely on the file extension.
- `find`:
- `head`: Display the beginning or top part of a text file.
- `history`: Display a list of previously executed commands in the current terminal session. 
- `hostname`: Display the hostname of the system.
- `htop`: It is a more advanced and feature-rich alternative to the traditional [top](#top) command.
- `init`: Used to change the runlevel of the system or initialize the system.
- `insmod`: Used to manually insert (load) a [kernel module](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules) into the running Linux kernel.
- `journalctl`: Utilize the systemd init system to view and query system logs.
- `kill`: 
- `last`:
- `ldconfig`: Used to update the shared library cache.
- `ldd`: Shows which libraries a program needs to run.
- `less`: View text files page by page with navigation features. 
- `ls`: List the files and directories in the current directory (folder).
- `lsblk`: Used for list devices that can read from or write to by blocks of data.
- `lscpu`: Display information about the CPU and its capabilities.
- `lshw`: used to display detailed information about the hardware components and configuration of a computer system.
- `lsmod`: List the currently loaded [kernel modules](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules) on the system.
- `lspci`: List all the [PCI devices](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#pci) connected to the computer's PCI bus.
- `lsusb`: List all the USB  devices connected to the computer.
- `man`: Manual.
- `mkdir`: Make directory.
- `modinfo`: Display information about a [kernel module](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules).
- `modprobe`: Used to add, remove, or manage [kernel modules](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules) dynamically.
- `more`: Display the content of text files one screen at a time.
- `mv`: Move (rename).
- `pwd`: Print working directory.
- `rm`: Remove.
- `rmdir`: Remove directory.
- `rmmod`: Remove or unload kernel modules from the running kernel.
- `runlevel`: Used to display the current runlevel of the system.
- `shutdown`: Used to gracefully shut down or restart the computer.
- `su`: Switch user.
- `sysctl`: Used to view, configure, and manage kernel parameters at runtime.
- `tail`: Display the end or tail portion of a text file.
- `telinit`: Used to change the system's runlevel.
- <a name="top"></a>`top`: Provides real-time information about the system's processes and resource usage.
- `type`: 
- `uname`: Display system information about the operating system.
- `unexpand`: 
- `uptime`: Displays the current time, how long the system has been running, and the average system load over the last 1, 5, and 15 minutes.
- `vim`: Text editor.
- `wall`: Allows a user to send a message to all users who are currently logged in to the system.
- `wc`: Used to count the number of lines, words, and characters in a text file or standard input.
- `whoami`: Display the username of the current user who is logged into the terminal or session.
- `wich`: 

##
options

- `--help`: Display a brief summary of how to use the command and its available options.
- `-f`:  Used to force or enable a particular behavior.

##

- `cd`: User home.
- `cd ~`: User home.
- `cd -`: Switches between the current directory and the previously visited directory.

``` console
[grego@localhost /]$ cd
[grego@localhost ~]$ pwd
/home/grego
```

## 

- `hostname -i`: Display the IP address associated with the system's hostname.

## 

Options for the uname command:

- `uname -a`, --all            : Display all available information.
- `uname -s`, --kernel-name    : Display the kernel name (e.g., Linux).
- `uname -n`, --nodename       : Display the network (host) name of the machine.
- `uname -r`, --kernel-release : Display the kernel release version.
- `uname -v`, --kernel-version : Display the kernel version.
- `uname -m`, --machine        : Display the system hardware name (e.g., x86_64).
- `uname -p`, --processor      : Display the processor type or "unknown" if not available.
- `uname -i`, --hardware-platform : Display the hardware platform (e.g., x86_64).
- `uname -o`, --operating-system : Display the operating system name (e.g., GNU/Linux).
