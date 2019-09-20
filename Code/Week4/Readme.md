## Try me out! 

1. File Operations Data Structure 
```
vim /lib/modules/$(uname -r)/build/include/linux/fs.h
```
2. View Device Files 
```
ls -l /dev
```
3. System Device Major Numbers
```
vim /home/kernel/linux-hwe-4.15.0/include/uapi/linux/major.h
```
4. Device Documentation
```
vim /home/kernel/linux-hwe-4.15.0/Documentation/admin-guide/devices.txt
```
5. Create device file
```
sudo mknod -m 777 /dev/simple_character_device c 240 0
```
6. Processes
```
ls /proc
ls /proc/1
ps -a
top
```