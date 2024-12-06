Day 5

_____

12/06/2024 - 8:37 AM
dr ///// paul // DrNavarrio // doc // callhimdoctor // nob

****
     Challenge: Spend at least 30 minutes a day learning Linux.
****
_____

Resources used: 
- Udemy Course: Learn Linux in 5 Days and Level Up Your Career - Jason Cannon

_____
 
Today I started the "Day 2" section of the course. I only got through one video, it was only 12 minutes but I was pausing to take a lot of notes (as you can see below.) This was a very informational video, and I was able
to learn a lot, and actually understand it. If I didn't catch something I would rewind the video to hear him explain it again, and that worked. I knew all the basic directories, but I definitely learned a lot from this
video. I am glad I was able to learn a lot from that video.

If I have more time today I am going to go onto the next video. If I do that, I will update today's journal. 

/ - "Root", the top of the file system hierarchy
/bin - Binaries and other executable programs
/etc - System configuration files (control how the OS or applications behave. e.g. there is a file that tells the OS to boot into the GUI or command line)
/home - Home directories
/opt - Where optional or third party software (anything not installed with the installation of the OS)
/tmp - Temporary space, typically cleared on reboot (good to put temporary files, but don't put anything in there long term)
/usr - User related programs, libraries, and docs
/var - Variable data, most notably log files

/boot - Files needed to boot the OS (Linux Kernel is here)
/cgroup - Control Groups hierarchy
/dev - Device files, typically controlled by the OS and sysadmins.
/etc - System configuration files

/export - Shared file systems
/home - Home directories
/lib - System libraries 
/lib64 - System libraries, 64 bit
/lost + found - Used by the file system to store recovered files after a file system check
/media - Used to mount removable media (CD-ROMs, USBs)

/mnt - Used to mount external file systems
/proc - Provides info about running processes
/root - The home directory for the root account
/sbin - System administration binaries
/selinux - Used to display information about SELinux

/srv - Contains data which is served by the system
/srv/www - Web server files
/srv/ftp - FTP files
/sys - Used to display and sometimes configure the devices known to the Linux kernel.

/usr - User related programs, libraries, and docs
/usr/bin - Binaries and other executable programs
/usr/lib - Libraries
/usr/local - Locally installed software that is not part of the base OS
/usr/sbin - System administration binaries
/var - Variable data, most notably log files
/var/log - Log files

Directories = Folders
/ = main folder everything else = sub folders

Application Directory Structures:

/usr/local/crashplan/bin
/usr/local/crashplan/etc
/usr/local/crashplan/lib
/usr/local/crashplan/log

In this example crashplan is software not installed with the distro.

/opt/avg/bin
/opt/avg/etc
/opt/avg/lib
/opt/avg/log

In this example avg installed itself in /opt

Sometimes though when applications are installed they are not given their own directory structure. Instead they are installed in a shared manner:
/etc/opt/myapp
/opt/myapp/bin
/opt/myapp/lib
/var/opt/myapp

A good organization method is to install software based on the company or organization name. e.g. if you work for acme you might see something like this:

/opt/acme
/opt/acme/bin
/opt/acme/etc

This helps maintain a clear distinction from software developed in house and software from outside sources.

Another example of organization:

/opt/google
/opt/google/chrome
/opt/google/earth

- dr
Applications that do not come with the installation of your distro are typically found in /opt or /usr/local



- dr
