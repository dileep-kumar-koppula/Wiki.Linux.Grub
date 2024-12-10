nano /etc/default/grub          // edits grub_timeout, background
update-grub             // update grub


// timeout sytle
GRUB_TIMEOUT_STYLE=hidden         // hides grub
         (or)
GRUB_TIMEOUT_STYLE=menu           // displays menu in grub


// timeout
GRUB_TIMEOUT=5

# update-grub

Generating grub configuration file ...
Found theme: /boot/grub/themes/kali/theme.txt
using custom appearance settings
Found background image: /usr/share/images/desktop-base/desktop-grub.png
Found linux image: /boot/vmlinuz-5.18.0-kali5-amd64
Found initrd image: /boot/initrd.img-5.18.0-kali5-amd64
Found linux image: /boot/vmlinuz-5.7.0-kali1-amd64
Found initrd image: /boot/initrd.img-5.7.0-kali1-amd64
Warning: os-prober will not be executed to detect other bootable partitions.
Systems on them will not be added to the GRUB boot configuration.
Check GRUB_DISABLE_OS_PROBER documentation entry.
Adding boot menu entry for UEFI Firmware Settings ...


          (or)
          
          
apt install grub-customizer
