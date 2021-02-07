# EasyFlash-for-Deauther
![GitHub](https://img.shields.io/github/license/clu3bot/EasyFlash-for-Deauther)
[![GitHub issues](https://img.shields.io/github/issues/clu3bot/EasyFlash-for-Deauther)](https://github.com/clu3bot/EasyFlash-for-Deauther/issues)
![GitHub repo size](https://img.shields.io/github/repo-size/clu3bot/EasyFlash-for-Deauther)
![Maintenance](https://img.shields.io/maintenance/yes/2021)
![GitHub followers](https://img.shields.io/github/followers/clu3bot?style=social)

# Description
EasyFlash for Deauther allows the user to easily flash bin files to esp8266 and other development boards. This script uses espressif's esptool and spacehuhn's wifi deauther v2.0.0 paired with a userfriendly interface created by clu3bot(Me). This interface allows the user to quickly flash Esp8266 and varius other developement boards with bin files. The script comes with spacehuhn's wifi deauther v2.0.0 so you can start flashing deauthers immediately. As I stated previously the interface is very userfriendly so you're able to change what bin file to flash with, without having to type a command or edit the script. 

# Things to know
When you first run the script it will check if espressif's esptool packages are installed, if they aren't installed the script will go ahead and clone that esptool repo to download the necessary files.

# Use any compatable bin file
To flash with alternative bin files make sure your files are located in the /Files/ directory. The interface will prompt the user with an option to change the bin file used to flash the device. Simply select that option and type the name of the file.  

# Content

[Screenshots](https://github.com/clu3bot/EasyFlash-for-Deauther/tree/main/imgs)


# Help/Errors

When using the EasyFlash interface you will be prompted to scan for the ttyUSB port number and asked to type the number shown. If you type a number besides the number shown you will get a no File or Directory error. This is easily fixed by using the Rescan option and further typing the correct number shown.

# Feedback

Please report issues with this project as I will fix them asap. If there are features that should be added, let me know. 
