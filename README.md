SDLogger is an open source project based on Nathan Seidle's OpenLog (http://github.com/SparkFun/OpenLog/wiki) to create a simple data logger for full-size high-density SD memory cards.

Ported code:

OpenLog_v1:    		Port of OpenLog 1.61 compiled with larger buffer and support for FAT32 and SD cards up to 16GB
OpenLog_v2:    		Port of OpenLog 2.2 (not fully functional yet)
OpenLog_v3:    		Port of OpenLog 3.11 (used with Arduino 1.0 with SDFat and SerialPort libraries added)
OpenLog_v3_Light:	Used for high-speed logging. By removing the menu and command mode the receive buffer is increased.
fatfs_chan:    		Port of ChaN FatFs R0.08a
petit_fatfs:   		Port of ChaN petit FatFs R0.02
arduino-1.0:   		Files for using SDLogger as an arduino board with arduino-1.0
arduino-0018:  		Core file and SdFat library for arduino-0018
arduino-0021:  		Core file and SdFat library for arduino-0021
arduino-0022:  		Core file for arduino-0022

###EDIT: Andy Goss 17 JUNE 2014 2209 EDT (GMT-0400)

Updated the OpenLog_v3 to version 3.11a for FreeEMS native 115200 baud, 8-Odd-1 datalogging.
The user will need to copy the CONFIG.TXT to their SDHC card to set this up, as the default file will be created if this file is not copied by the user for 9600 baud, 8-None-1 datalogging.
