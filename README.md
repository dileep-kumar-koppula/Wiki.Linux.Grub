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
### You can set the timeout style in the grub configuration:
- **To hide the GRUB menu upon boot:**
  ```bash
  GRUB_TIMEOUT_STYLE=hidden
  ```
- **To display the GRUB menu:**
  ```BASH
  GRUB_TIMEOUT_STYLE=menu
  ```
## GRUB Timeout Setting
- **To set the timeout duration (in seconds) for the GRUB menu:**
  ```bash
  GRUB_TIMEOUT=5
  ```
## Final
- **To update the grub file:**
  ```bash
  update-grub
  ```

-----

# Alternative: Using GRUB Customizer

- **If you prefer a graphical interface, you can install GRUB Customizer:**
  ```bash
  sudo apt install grub-customizer -y
  ```
