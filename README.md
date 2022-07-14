# vkinfo
vkinfo (Void Kernel Info) is a simple bash script written for Void Linux, which enumerates kernels found in /boot, and then identifies which kernels can be removed by the "vkpurge" command, or especially, the **"vkpurge rm all"** command.  Invocation is **"vkinfo"**, without arguments. /boot is assumed to be mounted and available.
## Installation
Clone or download vkinfo, and copy the script to a desired location for executable files. For example:
- cp vkinfo /usr/local/bin/vkinfo
- chmod +x /usr/local/bin/vkinfo
