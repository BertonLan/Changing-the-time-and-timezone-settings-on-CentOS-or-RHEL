# Changing-the-time-and-timezone-settings-on-CentOS-or-RHEL
Changing the time and timezone settings on CentOS or RHEL
``` 
# date
# hwclock
# timedatectl
# timedatectl list-timezones
# timedatectl set-timezone Asia/Shanghai
# yum -y install utp ntpdate
# ntpdate cn.pool.ntp.org
# hwclock --systohc
# timedatectl set-timezone Asia/Shanghai
```
