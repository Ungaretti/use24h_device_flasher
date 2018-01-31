# use24h_device_flasher

### This program flashes the use24h firmware into a use24h device. Quick and easy.

<img src="https://github.com/Ungaretti/Gui-for-esptool-ck/blob/master/assets/Screenshot.PNG">

You may choose to download the .zip file and extract it in a folder or download the standalone executable. Both are at the "release" page of this Github project.

The contents of the zip file, once extracted, have an executable, a copy of [Esptool-ck](https://github.com/igrr/esptool-ck) and the firmware binary file. 

<img src="https://github.com/Ungaretti/Gui-for-esptool-ck/blob/master/assets/fileview.PNG">

It executes a little faster since the standalone executable is actually a "wrapped" version of of the contents of the zip file.

### Note: the firmware that comes with both releases is NOT the use24 firmware yet, as it is still in development.

Actually this program has an "+Options" window that allows you to flash any firmware into any NodeMcu development board (ESP8266).

<img src="https://github.com/Ungaretti/Gui-for-esptool-ck/blob/master/assets/Screenshot2.png">

[Esptool-ck](https://github.com/igrr/esptool-ck) is a program writen in C to flash firmware to the ESP8266. Don't confuse it with exptool.py, a python program that does pretty much the same thing, but requires python installed in your computer.
