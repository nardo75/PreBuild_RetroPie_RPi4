# PreBuild RetroPie v01.03 by nardo75

# DOWNLOAD HERE:
The .img is on my mega, bc it's too big for github: [Download-Prebuild_RetroPie_byNardo75](https://example.com/meinedatei)


## Features
- **Username:** `derschalker`  
- **Password:** `changeme`  
- All official RetroPie repositories pre-installed.  
- **RetroPie-Manager-Plus** is installed and accessible via:  
  [http://your.rpi.ip.here:8000](http://your.rpi.ip.here:8000).  
- **PSX (PlayStation)** pre-configured.  
- **NDS (Nintendo DS)** pre-configured.  
- Automatic USB drive mounting for `/home/$USER/RetroPie/roms` using `fstab`.

## USB Drive Mount Instructions
1. Find the UUID of your USB drive:  
   ```bash
     sudo blkid /dev/sda1
   ```
2. Edit the fstab configuration file:
  ```bash
    sudo nano /etc/fstab
  ```
3. Add the following line, replacing your-uuid with your USB drive’s UUID:
  ```bash
    UUID=your-uuid /home/$USER/RetroPie/roms ext4 defaults 0 2
  ```
Save and exit. Your drive will now automatically mount.

## Coming Soon
Stay tuned for more updates and new features in future versions!

## Need Help?
Feel free to reach out for advice or assistance:

**X (Twitter):** @nardo_75

**Instagram:** @nardo75


##

Best regards,
Nardo75

##

**Don't forget to hit the ⭐ if you like this repo.**

![GitHub Stars](https://img.shields.io/github/stars/nardo75/PreBuild_RetroPie_RPi4?style=social)
![GitHub Forks](https://img.shields.io/github/forks/nardo75/PreBuild_RetroPie_RPi4?style=social)
![GitHub Contributors](https://img.shields.io/github/contributors/nardo75/PreBuild_RetroPie_RPi4)
