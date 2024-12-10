## Managing GRUB Configuration

### Edit GRUB Configuration

- **To edit the GRUB configuration file:**
```bash
nano /etc/default/grub
```
  You can use this command to modify settings such as GRUB_TIMEOUT and GRUB_BACKGROUND.


- **To update GRUB after making changes:**
```bash
update-grub
```
This command regenerates the GRUB configuration file based on the settings you've modified.

## GRUB Timeout Style
You can set the timeout style in the grub configuration:
- **To hide the GRUB menu upon boot:**
```bash
GRUB_TIMEOUT_STYLE=hidden
```
To display the GRUB menu:
    GRUB_TIMEOUT_STYLE=menu
GRUB Timeout Setting
    To set the timeout duration (in seconds) for the GRUB menu:
GRUB_TIMEOUT=5








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
