下载

进入[官网下载页面](http://www.raspberrypi.org/downloads/)  
选择ArchLinux下载,解压  

烧录
准备好sd卡,插入电脑
```
diskutil list #找到插入的sd卡
diskutil umountDisk /dev/disk1  #umount sd卡
sudo dd if=ArchLinuxARM-2014.06-rpi.img of=/dev/disk1  bs=1M  #烧录
```



