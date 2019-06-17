# dotdotdot
My Linux dotfiles, including configurations for XServer, i3, polybar, and compton. 

My current setup (as of June, 2019):
![Rice](https://github.com/msradam/dotdotdot/blob/master/screenshots/Sun-16Jun19_19.53.png)

System Information (Neofetch'd):
OS: Arch Linux x86_64 
Host: XPS 13 9370 
Kernel: 5.1.9-arch1-1-ARCH 
Packages: 972 (pacman) 
Shell: bash 5.0.7 
DE: i3 
Terminal: urxvt 
Terminal Font: Input Mono, xft 
CPU: Intel i7-8550U (8) @ 4.000GHz 
GPU: Intel UHD Graphics 620 
Memory: 15755MiB 

## Installation
First, make backups of your current configuration files, then copy the appropriate dotfiles to your .config folder, located in your home directory.
To install my .Xresources:
`cp -r .Xresources ~/.Xresources && xrdb ~/.Xresources`
I recommend changing the DPI setting for your display depending on your resolution, currently Xft.dpi : 220 which is suitable for 4k displays.
