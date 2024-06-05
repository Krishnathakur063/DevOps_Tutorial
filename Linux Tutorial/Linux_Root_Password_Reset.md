rw init=/sysroot/bin/sh
ctrl x
chroot /sysroot
passwd root

touch /.autorelabel
exit
reboot

