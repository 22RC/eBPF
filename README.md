# eBPF


Inside the repo there are two programs for monitoring processes using eBPF.


cdSnoop: is a daemon that monitors the bash processes that use the 'cd' command to move between filesystem directories.

pageFaultCount: is a program to see which processes are running that cause pagefaults in virtual memory.

If you want install eBPF on your device see here (https://github.com/iovisor/bcc/blob/master/INSTALL.md)
