# Zen OS
##### ZenOS is an edited version of Raspberry Pi OS (32 bit) and is supported for most older raspberry pis (3 and below).
With Zen OS, you can make your Raspberry Pi's OS easier to use by making mac-like taskbar designs and a quick access sidebar that can be opened from dragging your mouse to the top-left edge of the screen. This OS will make this way easier for people to use their Raspberry Pi.
### Credentials to log in /sudo
```
Username: admin
Password: pi
```
### How to install
The installation process is rather straightforward and very easy to do. Follow for how-to!
######
1. Download the preferred (Latest is recommended) version of the ZenOS image.
2. Download [Raspberry Pi Imager](https://downloads.raspberrypi.org/imager/imager_latest.exe) from the website or the link.
3. In Raspberry Pi Imager, Select your device. ![image](https://github.com/user-attachments/assets/80a592f6-619a-474f-aa53-08415da67f05)
4. Go in "Choose OS" and select "Use Custom" and select the image downloaded in step 1.
![image](https://github.com/user-attachments/assets/a086ea10-9512-45e2-a81a-9d2c34713c8d)
5. Select your SD Card for installation.
6. Press begin and you are ready!
### IMPORTANT: After Installation
It is important to do this after installation or else nothing will download or install.
YOU MUST:
1. Press the Zen Logo to open the start menu.
2. Open GPARTED, and type the password found above in [Credentials](https://github.com/Vipro-Projects-Corp/Zen-OS/main/README.md#credentials-to-log-in-sudo)
3. Find the "rootfs" partition, right click it, and select "Resize/Move".
4. Resize it all the way to the full size of your disk. (In future versions, there might be no need to do this, as startup scripts may handle it.)
