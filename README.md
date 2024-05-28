# Veeam for Arch
Rebuiled *.deb packages of Veeam agent for Arch-based systems

Works for Kernel version 6.8

# Usage
```
sudo pacman -U blksnap-6.1.2.1781-1-any.pkg.tar.zst
sudo pacman -U veeam-libs-6.1.2.1781-1-x86_64.pkg.tar.zst  
sudo pacman -U veeam-6.1.2.1781-1-x86_64.pkg.tar.zst

sudo systemctl start veeamservice.service
sudo systemctl enable veeamservice.service

sudo veeam
```
