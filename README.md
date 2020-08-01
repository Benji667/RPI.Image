# RPI.Image
SD card image for Raspberry Pi with LabVIEW 2020 installed.

## Create an image of the SD card

On Windows, the best software to do this is Win32 Disk Imager

- Download Win 32 Disk Imager, install it and launch it
- Enter the image destination folder and file name (.img)
- Select the SD card letter in the device list
- Click on “Read”
- This tool will create the image in the selected folder

## Restore

The easiest way to restore this backup is to flash the image on another SD card with Etcher

- Download Etcher from the official website
- Install and run it
- Choose your backup image on the left
- Choose your SD card
- Click on the “Flash” button

You’ll get a new SD card with the system in the same state as during the backup.
