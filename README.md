# PreBuild RetroPie v01.03 by nardo75

##
![GitHub Stars](https://img.shields.io/github/stars/nardo75/PreBuild_RetroPie_RPi4?style=social)
![GitHub Forks](https://img.shields.io/github/forks/nardo75/PreBuild_RetroPie_RPi4?style=social)
![GitHub Contributors](https://img.shields.io/github/contributors/nardo75/PreBuild_RetroPie_RPi4)

## Features
- **Username:** `derschalker`  
- **Password:** `changeme`  
- All official RetroPie repositories pre-installed.  
- **RetroPie-Manager-Plus** is installed and accessible via:  
  [http://your.rpi.ip.here:8000](http://your.rpi.ip.here:8000).  
- **PSX (PlayStation)** support with BIOS pre-configured.  
- **NDS (Nintendo DS)** support with BIOS pre-configured.  
- Automatic USB drive mounting for `/home/derschalker/RetroPie/roms` using `fstab`.

## USB Drive Mount Instructions
1. Find the UUID of your USB drive:  
   ```bash
   sudo blkid /dev/sda1
Edit the fstab configuration file:
bash
Code kopieren
sudo nano /etc/fstab
Add the following line, replacing your-uuid with your USB drive’s UUID:
text
Code kopieren
UUID=your-uuid /media/ssd ext4 defaults 0 2
Save and exit. Your drive will now automatically mount.
Coming Soon
Stay tuned for more updates and new features in future versions!

## Need Help?
Feel free to reach out for advice or assistance:

**X (Twitter):** @nardo_75

**Instagram:** @nardo75



**Don't forget to hit the ⭐ if you like this repo.**
