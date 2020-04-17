# Minecraft 1.15.2 installation on Raspberry Pi
This repo is just a dumping ground for articles, blogs, tutorials, that I've found useful when setting up my Raspberry Pi 3 to run a Java Edition Minecraft server. 

You are more then welcome to create a fork of this or add a pull request. 

## Tutorials:
* [Setting up the Raspberry Pi server](https://www.linuxnorth.org/minecraft/index.html)

* [Setting up Backups](https://www.linuxnorth.org/minecraft/modded_linux.html#Step%209%20-%20Backup%20Your%20Server%20Frequently)

## Firewall
* [Setup Firewall](https://www.linuxnorth.org/five_minute_firewall/)

## Moving Mods from PC to Raspberry Pi
I found [WinScp](https://winscp.net/eng/index.php) perfect for moving the .jar files from Windows to Raspberry Pi. 
Note: You may need to add `sudo su -` to the SCP / Shell settings within WinScp to allow for you to copy files to the RPi 

## Install Forge on Local Windows client to allow for Mods
Even if the mods are on the server, each client needs to have them installed too.
[How to install mods on Windows](https://www.windowscentral.com/minecraft-java-edition-guide-how-to-install-mods)

## Mods installed so far : 
* [ForgeEndertech](https://www.curseforge.com/minecraft/mc-mods/forgeendertech)
* [Advanced Finders](https://www.curseforge.com/minecraft/mc-mods/advanced-finders)
* [Large Ore Deposits](https://www.curseforge.com/minecraft/mc-mods/large-ore-deposits)
