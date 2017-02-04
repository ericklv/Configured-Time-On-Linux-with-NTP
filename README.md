# Configured-Time-On-Linux-with-NTP

First install ntp 
# pacman -S ntp

Enable NTP
# systemctl enable ntpd

Set time on session
# ntpd -qg

Set time on hardware
# hwclock -w
