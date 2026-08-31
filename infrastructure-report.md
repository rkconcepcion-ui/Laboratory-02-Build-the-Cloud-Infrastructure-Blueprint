# Infrastructure Report

## Server Information

- Operating System: Ubuntu Linux
- Kernel Version: 6.8.0-138-generic
- CPU Model: Intel Xeon E3123 (Sandy Bridge, IBRS update)
- CPU Cores: 1
- CPU Architecture: x86_64
- Total RAM: 1.9 GiB
- Disk Capacity: 20 GiB
- Hostname: ubuntu
- IP Address: 172.30.2.1, 172.17.0.1

## Mounted File Systems

| Filesystem | Size | Used | Available | Mounted on |
|---|---|---|---|---|
| tmpfs | 191M | 996K | 190M | /run |
| /dev/vda1 | 19G | 5.4G | 13G | / |
| tmpfs | 952M | 84K | 952M | /dev/shm |
| tmpfs | 5.0M | 0 | 5.0M | /run/lock |
| /dev/vda16 | 881M | 117M | 703M | /boot |
| /dev/vda15 | 105M | 6.2M | 99M | /boot/efi |

## Linux Commands Executed

- cat /etc/os-release
- uname -r
- lscpu
- free -h
- lsblk
- df -h
- hostname
- hostname -I
