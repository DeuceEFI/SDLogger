Last Edit: Andy Goss 17 JUNE 2014 2222 EDT (GMT-0400)

To compile any custom changes that you might make to the Arduino sketch, make sure to go to:

File -> Preferences

and change the Sketchbook location to the root of my SDLogger repository as it will automatically include the SdFat and SerialPort libraries which are found in the /libraries directory found in the root of my SDLogger repository.  You will need to exit out of Arduino 1.0 then relaunch it to use this new path.

Once you compile and upload the sketch to your SDLogger you will need to copy the CONFIG.TXT file found in the OpenLog_v3 directory of my repository to the root of your SDHC card to setup the logger for FreeEMS 115200, 8-Odd-1 datalogging.

The resulting files will be in FreeEMS *.bin format, LOG00000.bin for new logfile for each power on event or SEQLOG00.bin for sequential logging to the same file.  The CONFIG.TXT file in my repository is setup for 115200 8-O-1, new log file for each power on event.

Enjoy! :-)
