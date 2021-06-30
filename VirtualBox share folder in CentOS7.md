# Create a share folder (vboxshare) in windows and configure it from VirtualBox
* Open VirtualBox application
* Select VM
* Click on **Settings** option
* Select **Shared Folders** option from left panel
* Click on **+ with folder icon** option and **Add Share** dialog will pop-up
* Select your desire folder for sharing with CentOS7
* - [x] Auto-mount
* Finall press **OK** button

# Insert VBoxGuestAdditions.iso under IDE controller
* From **Settings** window, click on **Storage** option
* Add **VBoxGuestAdditions.iso** image under IDE controller
* Click on **OK** button

# Configure CentOS7
* Start VM

## Install dependencies
```
$ sudo yum -y update
$ sudo yum -y groupinstall "Development Tools"
$ sudo yum -y install openssl-devel bzip2-devel libffi-devel
```
* Mount the CD
```
sudo mount -t iso9660 /dev/cdrom /mnt
/mnt/VBoxLinuxAdditions.run
```
* Known issue
---
>VirtualBox Guest Additions: Kernel headers not found for target kernel 3.10.0-1160.31.1.el7.x86_64. Please install them and execute /sbin/rcvboxadd setup modprobe vboxguest failed

**Fix:**
You can install the kernel-devel package by:
```
$ yum install kernel-devel
```
---

* Reboot VM
```
sudo shutdown -r now
```

* Create shared folder
```
mkdir ~/shared
```
* Mount shared folder
```
 mount -t vboxsf vboxshare ~/shared
ls -la ~/shared
```
* Make mount folder persistent
* Open /etc/fstab file
```
sudo nano /etc/fstab
```
Add the following lines at the bottom of fstab (separated by tabs) file and Save it. ```ctrl+x then y```
```
# VirtualBox shared folder persistent
vboxshare	/root/shared	vboxsf	defaults	0	0
```
* Again reboot the VM and log-in
```
sudo shutdown -r now
```
---
Thank you for reading this document.
---
