# matchalinux
Matcha Linux - Ubuntu-based OS made in Japan simple
## How to build
Matcha Linux has a build method that includes a [LUBS](https://github.com/FascodeNet/LUBS).    
Prease note that this can only build on Ubuntu or Ubuntu-based distributions.
### Preparation
```bash
sudo apt install binuils squashfs-tools xorriso grub-pc-bin grub-efi-amd64-bin mtools arch-install-scripts
git clone https://github.com/NSK-1010/matchalinux.git
cd matchalinux
git clone https://github.com/FascodeNet/LUBS.git
cp -r matcha LUBS/
```
### Build
```bash
sudo ./lubs matcha
```
## System Requirements
### Minium
CPU: Pentium M 1.0GHz    
RAM: 1GB    
Storage: 9GB
### Recommended
CPU: Core 2 Duo 1.6GHz    
RAM: 2GB    
Storage: 16GB