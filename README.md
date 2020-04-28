- Add a txt file test.log to your project
- File Requirement: make a live data collection of your PC
- File must include following information:
> - date and time
> - os version
> - hardware information
> - uptime
> - services information
> - nic information
> - route information
> - arp information
> - information of processes

### Environment: WSL ubuntu virtual machine on windows10

### Corresponding commands:
- Date
- OS:cat /etc/issues | Kernel:uname -a | cat /proc/cpuinfo | cat /proc/meminfo
- Disk Information: fdisk -l | df -h
- uptime
- service -status-all
- ifconfig -a
- netstat -rn
- arp -a
- ps auxwwem
