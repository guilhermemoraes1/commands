### Command -options arguments

- `adduser`: Adding new user accounts to the system.
- `alias`: Used to create a temporary or permanent shortcut for a longer command or series of commands.
- `apropos`: Used to search for and display a list of manual pages (documentation) that are related to a specific keyword or topic.
- `apt update`: This command refreshes the package lists, ensuring that the system has the latest information about available packages.
- `apt upgrade`: This command upgrades the installed packages to their latest versions.
- `apt install package_name`: It installs a specific package.
- `apt remove package_name`: It removes a specific package from the system.
- `apt search search_term`: It searches for packages based on a specified search term.
- `apt show package_name`: It displays detailed information about a specific package.
- `apt list`: It lists all available packages.
- `apt autoremove`: It removes any automatically installed packages that are no longer required.
- `apt full-upgrade`: It performs a more aggressive upgrade that can install or remove additional packages if necessary.
- `cat`: Used to concatenate and display the content of text files.
- `cd`: Change directory.
- `chmod`: Used to change the permissions (read, write, execute) of files and directories.
- `chgrp`: Used to change the group ownership of files and directories.
- `chown`: Used to change the ownership of files and directories.
- `chsh`: 
- `clear`: Clear the screen and remove previous text or output.
- `cut`: Used for extracting specific sections (fields or columns) from text files or input streams.
- `df`: Used to display information about the disk space usage on a system.
- `dmesg`: Used to display the [kernel ring buffer](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-ring-buffer).
- `dmidecode`: Used to display information about the disk space usage on a system.
- `echo`: Used to print text or messages to the terminal or console.
- `env`: Used to display or modify the environment variables for a specific command or shell session.
- `exit`: Used to terminate a terminal session or close a shell.
- `export`: Used to set environment variables, making them available to other processes or shells
- `fdisk`: Used for partitioning and formatting hard drives or storage devices.
- `file`: Determine the type of a file by examining its content, rather than relying solely on the file extension.
- `find`: Used to search for files and directories within a specified directory hierarchy based on various criteria.
- `free`: Used to display information about the system's memory usage.
- `head`: Display the beginning or top part of a text file.
- `history`: Display a list of previously executed commands in the current terminal session. 
- `hostname`: Display the hostname of the system.
- `htop`: It is a more advanced and feature-rich alternative to the traditional [top](#top) command.
- `info`: Used to access documentation and information about various commands, programs, and topics within the GNU Project.
- `init`: Used to change the runlevel of the system or initialize the system.
- `insmod`: Used to manually insert (load) a [kernel module](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules) into the running Linux kernel.
- `ip`: Used for configuring and managing network interfaces, routes, and tunnels.
- `journalctl`: Utilize the systemd init system to view and query system logs.
- `kill`: Used to terminate or signal processes in the system.
- `last`: Used to view information about previously logged-in users.
- `ldconfig`: Used to update the shared library cache.
- `ldd`: Shows which libraries a program needs to run.
- `less`: View text files page by page with navigation features.
- `ln`: Used to create links between files, Hard Link and Symbolic (Soft) Link.
- `locate`: 
- `ls`: List the files and directories in the current directory (folder).
- `lsblk`: Used for list devices that can read from or write to by blocks of data.
- `lscpu`: Display information about the CPU and its capabilities.
- `lshw`: used to display detailed information about the hardware components and configuration of a computer system.
- `lsmod`: List the currently loaded [kernel modules](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules) on the system.
- `lspci`: List all the [PCI devices](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#pci) connected to the computer's PCI bus.
- `lsusb`: List all the USB  devices connected to the computer.
- `man`: Used to display manual pages for commands, programs, and other system components.
- `mkdir`: Make directory.
- `modinfo`: Display information about a [kernel module](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules).
- `modprobe`: Used to add, remove, or manage [kernel modules](https://github.com/guilhermemoraes1/commands/blob/main/lpic.md#kernel-modules) dynamically.
- `more`: Display the content of text files one screen at a time.
- `mv`: Move (rename).
- `pgrep`: Used to find and list the process IDs (PIDs) of processes based on their names.
- `ping`: Used to test the reachability of a host on an IP network.
- `printenv`: Used to display the current environment variables. 
- `ps`: Used to provide information about currently running processes on the system.
- `pstree`: Used to display a hierarchical tree-like view of all currently running processes on the system.
- `pwd`: Print working directory.
- `rm`: Remove.
- `rmdir`: Remove directory.
- `rmmod`: Remove or unload kernel modules from the running kernel.
- `route`: Used to view and manipulate the IP routing table.
- `runlevel`: Used to display the current runlevel of the system.
- `set`: Used to set and manipulate the shell's internal variables and options.
- `shutdown`: Used to gracefully shut down or restart the computer.
- `sort`: Used to arrange the lines of a file or the output of a command in a specific order.
- `source`: Used in shell scripting to execute commands or scripts within the current shell environment.
- `ss`: Used for displaying detailed socket statistics.
- `stat`: 
- `su`: Switch user.
- `sysctl`: Used to view, configure, and manage kernel parameters at runtime.
- `systemctl`: 
- `tail`: Display the end or tail portion of a text file.
- `telinit`: Used to change the system's runlevel.
- <a name="top"></a>`top`: Provides real-time information about the system's processes and resource usage.
- `type`: Used to display information aboout a shell command.
- `typeset`: Used in shell scripting to define and set attributes for variables.
- `unalias`: Used to remove alias definitions.
- `uname`: Display system information about the operating system.
- `unexpand`: Used to convert spaces to tabs in a text file. It is essentially the reverse of the `expand` command.
- `unlink`: Used in the context of file systems to remove a symbolic or soft link.
- `unset`: 
- `usermod`:
- `useradd`:
- `uptime`: Displays the current time, how long the system has been running, and the average system load over the last 1, 5, and 15 minutes.
- `vim`: Text editor.
- `w`: 
- `wall`: Allows a user to send a message to all users who are currently logged in to the system.
- `wc`: Used to count the number of lines, words, and characters in a text file or standard input.
- `whereis`:
- `who`: 
- `whoami`: Display the username of the current user who is logged into the terminal or session.
- `which`: 

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
