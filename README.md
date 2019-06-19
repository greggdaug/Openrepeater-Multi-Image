# Openrepeater Multi Image

or_multi_img_061919.zip

16Gb image containg v2.1.1 + 2 empty partitions for switching between aditional versions.

Added aliases runOR1, runOR2 and runOR3 to /root/.bashrc for setting up /boot/cmdline.txt file.

Additional versions will require modification of /etc/fstab to mount proper root partition.

Partitions:

/dev/mmcblk0p1 = /boot
/dev/mmcblk0p2 = /root for v2.1.1
/dev/mmcblk0p3 = /root for ORv2
/dev/mmcblk0p4 = /root for ORv3
