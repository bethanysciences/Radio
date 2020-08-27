# Various Radio Topics  
  
## Antennas

- Enf Fed Half Wave (EFHW)
- Baluns and Ununs

## Digital Modes

- FT8
- PSK31
- WinLink

## Software Defined Radio (SDR)

- RTL_SDR
- openwebrx [Jakob Ketterl's Fork](https://github.com/jketterl/openwebrx)
  
## Useful Raspian Commands  
  
[Raspian Linux Documentation](https://www.raspberrypi.org/documentation/linux/)  
  
```zsh  
sudo reboot
ssh pi@192.168.86.49
sudo raspi-config
vcgencmd measure_temp
vcgencmd measure_clock arm
vcgencmd measure_volts core
vcgencmd get_config arm_freq
systemctl is-active application.service
systemctl list-units --type=service
sudo systemctl reload-or-restart application.service
sudo systemctl enable <service>    # disable start stop restart reboot 
journalctl -u openwebrx.service  
df                                 # disk space
hostname                           # displays current system hostname
cat /proc/version                  # OS version
free                               # free memory
lsusb                              # connected USB hardware
find / -name example.txt           # search for file or directory anywhere
pwd                                # present directory
mkdir                              # new directory
rmdir                              # remove empty directories
rm                                 # remove file
cp                                 # copy file
mv                                 # move file
cat                                # file contents | pipes output, grep "search" *.txt
head                               # file beginning -n [number of lines]
chmod                              # file permissions
scp                                # ssh copy
whereis                            # find command location
sudo apt update
sudo apt upgrade
sudo apt install
tail -f /var/log/syslog | grep python3  # system log console output /var/log/syslog
iwconfig wlan0  
ifconfig                                # network configuration details  
nmap                                    # network exploration and scanning tool  
ps -A                                   # lists running processes  
top
htop  
pgrep <app name>  
kill PID#  
pkill <app name>  
iwconfig wlan0  
```  
  