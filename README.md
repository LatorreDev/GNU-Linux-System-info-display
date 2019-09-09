# GNU/Linux System Info

Script for show the GNU/Linux system info

![Alt Text](https://github.com/LatorreDev/GNU-Linux-System-info-display/blob/master/assets/Screenshot.png)

## Pre requisistes

dmidecode for show ram info

### Arch and derivates like Manjaro, Anarchy, Parabola, etc.
```bash
sudo pacman -S dmidecode
```

### Debian and derivates like Ubuntu, Mint, Deepin, Kali, etc.
```bash
sudo apt install dmidecode
```
# To exit some option
Press q

## Avaliable options
# Kernel info
Show the kernel info such as kernel version
# System Processes
Show the running processes on the system
# PCI devices info
Show all the PCI devices avaliable such as graphic card, Network and usb,etc
# Network interface info
Show only the network interface such as ethernet and wifi model cards 
# USB devices info
Show only the USB devices avaliable and his controllers
# Ram info
Show the info of each RAM module, including capacity, model, speed, etc. (You need dmidecode as you can see in the pre requisites)
# Battery info
Show the battery info such as capacity, health, brand, current status, etc.
# Kernel Modules
Show the current kernel modules on the system
# Services
Show the current running services (Only works with SystemD)
# quit
Exit the program
