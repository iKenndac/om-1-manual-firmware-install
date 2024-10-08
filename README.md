# Manually Installing an OM-1/OM-1 Mark II/OM-5 Firmware Update Via SD Card

This readme file describes the process of updating the firmware of an OM-SYSTEM OM-1, OM-1 Mark II, or OM-5 camera by downloading an update file from OM-Systems' update server and copying it to an SD card. This is an alternate mechanism to using the OM Workspace application or the mobile app for the camera.

**Important:** While these instructions detail how to download the update file from OMS' own servers and arrange it such that the camera will install it, this is _not_ an officially-supported mechanism for end users to update the firmware of their cameras (as far as I'm aware, this is the procedure used by service centres use to install firmware). While I have had success with this method on my own camera, this is done **at your own risk**.

**Also Important:** Additionally, I will not provide help or technical support outside of these instructions. Please read through these instructions carefully, making sure you understand all of the steps. If you don't understand anything in these steps, refer to your OMS' support pages for instructions on how to update using the OM Workspace or mobile apps. 

Finally, these steps don't explicitly back up or restore your camera's settings. Be sure to back up the camera's settings with OM Workspace or the camera's mobile apps (or a pen and paper) before performing the update if saving them is important to you.

### Preparation

1. Make sure your camera is charged.
2. Download the update file you want from the list at the bottom of this page. 
3. Insert an SD card useable/formatted by the camera (it doesn't have to be empty) into an SD card reader connected to your computer. 
4. Create a folder on the root of the SD card called `DCOLYMP`.
5. Rename the firmware update file you downloaded to the correct one for your camera according to the table below.
6. Copy the renamed file into the `DCOLYMP` folder on your SD card.
7. You should now have a folder called `DCOLYMP` on your SD card with a file named according to the below table inside it.
8. Remove the SD card from your card reader.

### File Names

Rename the downloaded firmware file to the following, depending on your camera:

- OM-1: `E1439999.BIN`
- OM-1 Mark II: `E1469999.BIN`
- OM-5: `E1449999.BIN`

### Installation

1. Turn off the camera.
2. Put the SD card containing the firmware into Slot 1 of your camera.
3. Hold down the **OK** button on the back of the camera.
4. While continuing to hold down the **OK** button, turn on the camera.
5. If you made a mistake somewhere in the process so far, the camera will start as normal. Go back to the beginning and double-check your work.
6. If you did everything correctly, the camera screen will stay blank for a few seconds, then the orange lamp on the front of the camera should illuminate solidly (i.e., not blinking). The update is now installing, and you can release the **OK** button. The screen will stay blank — don't worry!

**IMPORTANT: DO NOT TURN OFF THE CAMERA OR REMOVE POWER WHILE THE ORANGE LAMP IS INDICATING THAT INSTALLATION IS IN PROGRESS.**

7. After a few minutes (and it _can_ take several minutes), the orange lamp will start to blink. This means the update has finished installing.
8. Turn off the camera, wait a few moments, then turn it on again.
9. You'll now have the updated firmware installed. 

### Post-Installation 

It's sensible to remove the update file from your SD card to avoid accidentally triggering the installation process again in the future — the camera will happily re-install the same firmware version it already has.

### Download Links

**Note:** These links are directly to Olympus/OMS download servers. The update files aren't hosted in this repository.

#### OM-1

- [OM-1 Firmware 1.2](https://dl01.om-digitalsolutions.net/OMDS/FIRMWARES/0001/1430/OLY_E_143_1200_0000_0000.BIN)
- [OM-1 Firmware 1.3](https://dl01.om-digitalsolutions.net/OMDS/FIRMWARES/0001/1430/OLY_E_143_1300_0000_0000.BIN)
- [OM-1 Firmware 1.4](https://dl01.om-digitalsolutions.net/OMDS/FIRMWARES/0001/1430/OLY_E_143_1400_0000_0000.BIN)
- [OM-1 Firmware 1.5](https://dl01.om-digitalsolutions.net/OMDS/FIRMWARES/0001/1430/OLY_E_143_1500_0000_0000.BIN)
- [OM-1 Firmware 1.6](https://dl01.om-digitalsolutions.net/dslr/1430/v1600/OLY_E_143_1600_0000_0000.BIN)
- [OM-1 Firmware 1.7](https://dl01.om-digitalsolutions.net/dslr/1430/v1700/OLY_E_143_1700_0000_0000.BIN)

#### OM-1 Mark II

- [OM-1 Mark II Firmware 1.1](https://dl01.om-digitalsolutions.net/dslr/1460/v1100/OLY_E_146_1100_0000_0000.BIN)
- [OM-1 Mark II Firmware 1.2](https://dl01.om-digitalsolutions.net/dslr/1460/v1200/OLY_E_146_1200_0000_0000.BIN)

#### OM-5

- [OM-5 Firmware 1.2](https://dl01.om-digitalsolutions.net/dslr/1440/v1200/OLY_E_144_1200_0000_0000.BIN)
