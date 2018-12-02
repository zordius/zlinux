Personal Linux Scripts and Configs

# System Steps (Manual)
* copy clean initial raspbian system into hd: sudo cp -ax / .
* copy fstab for boot and root
* copy cmdline.txt for root
* Setup console for large display: sudo dpkg-reconfigure console-setup

# System Steps (Auto)
* restore
* sudo shutdown now
* sudo sh /boot/zlinux/cmp/pkgs/remove

# Tips

* cmdline.txt force HDMI mode: 'nomodeset video=HDMI-A-1:1280x720@60' , this is the only way when new soft opengl driver enabled.
