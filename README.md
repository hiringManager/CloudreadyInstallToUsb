# CloudreadyInstallToUsb

How to install Cloudready to a USB or removable device from a USB.
There's only one post on the internet that I was able to find and everytime I have to bumble through the steps until I relearn this. It's kinda hard to find since Neverware migrated their website poorly after this was posted, so it always takes me like an hour to figure this out. 

- Create Cloudready USB
- You don't have to login, just change tty <Ctrl + Alt + F3> (or other F keys)
- Login ( username:chronos )
- Locate which drive you want to install on: **sudo fdisk -l**
- Install with: **sudo chromeos-install --skip_dst_removable --dst /dev/sdX**
- Reboot and you should be done. Usually the first boot on ChromeOS installs is pretty slow (fsck and other stuff on their 900 partitions), so just wait it out.
  
If you have a newer device than a 1st gen Intel, then I recommend doing a brunch install so that you have Android Applications. But Cloudready is fast without all the Google Bloat. (Acquired by Google recently so RIP)
  
Link to my Hero: https://cloudreadykb.neverware.com/s/article/Manual-Installation-Via-the-Cmd-Line
