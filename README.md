# WiiHack
A comprehensive guide on hacking the Wii and what you can do once it is hacked

## Initial Hack Using SmashStack Method
- (For official guide: https://wiibrew.org/wiki/Smash_Stack)
- First make sure the wii is connected to Wii-fi (Wifi)
- Next the wii should be updated if there are any updates available.
- (This hack method should work if it is not but I have only done it on a fully updated wii)
- After the wii has been updated insert Super SmashBros Brawl
- Next insert an sd card that is 2 GB or less (Not SDHC) (Go here to check models that work https://www.wiibrew.org/wiki/SD/SDHC_card_compatibility_tests)
- You will want to go to the stage builder and move any custom stages to the sd card (Even the preexisting samples)
- Remove the sd card and put it in your computer.
- Rename the folder called private to privateold 
- Inside the initial folder is a folder called private and a file called boot.elf. The private folder is from the smash stack download and the boot.elf is from the hackmii installer. Make sure these are in the root of the sd card (As in you see the private folder and boot.elf once you click into the sd card).
- Go to the stage builder in Super SmashBros Brawl.
- As soon as you open it, the boot.elf should load and install the homebrew channel.

## Setting up the homebrew channel and bootmii
- (For official guide: https://wii.guide/hbc.html#:~:text=When%20at%20the%20HackMii%20installer,back%20and%20go%20to%20BootMii.)
- You will get a scam warning screen. It can be ignored as this is a free guide.
- After thirty seconds, you can press 1 to continue.
- Press continue, then hit "Install The Homebrew Channel"
- Press continue when finished.
- Hit Bootmii to begin its setup.
- Hit install Bootmii as boot2 if you can.
- Then Hit install BootMii as IOS
- Once that finishes, select "Continue" and select "Exit" to go to the homebrew channel

## Making a NAND Backup of Bootmii
- Good idea to do this after setting up homebrew and bootmii
- (For official guide: https://wii.guide/bootmii)
- Launch the homebrew channel and press home
- Select "Launch Bootmii"
- Select the options button, that is the icon with gears. You will need to use a gamecube controller as wiimotes do not work in bootmii.
- Select the BackupMii option, that is the icon with the green arrow.
- Just let the backup finish and do not worry about "bad blocks"
- Once it is finished you can exit the screen by pressing any button.
- To exit bootmii, press the back button. That is the button with an arrow then you can either go to the Wii menu or Homebrew Channel.

## Setting up the Homebrew Browser
- Download from here (https://wiibrew.org/wiki/Homebrew_Browser) or find in the repository
- Put the homebrew_browser folder from the download into a folder /apps located in the root of the sd card
- Launch the homebrew browser from the homebrew channel

## Recommended downloads from the Homebrew Browser
- 

## Setting up d2x cIOS Installer
- Install d2x cIOS Installer from the HomeBrew Browser
- (For official guide: https://wii.guide/cios)
- Wii Must be connected to the internet
- Under CIOS SETTINGS
  - Select cIOS <"v10 beta52 d2x-v10-beta52">
  - Select cIOS base <57>
  - Select cIOS slot <249>
  - Select cIOS revision <65535>
- Press A twice
- After it has successfully installed, press A to go back to CIOS SETTINGS
- Under CIOS SETTINGS
  - Select cIOS <"v10 beta52 d2x-v10-beta52">
  - Select cIOS base <56>
  - Select cIOS slot <250>
  - Select cIOS revision <65535>
- B to exit
- Restart the Wii

## For Wii Menu Shortcuts
- Install YAWMM - Yet Another Wad Manager
- (Video Description: https://youtu.be/EAdCh0Xa45s)
- See below on how to create a WAD
- Open and use IOS 249
- Select NAND emulator device < disable >
- Select Source device: < Wii SD Slot >
- Select the WAD you would like to use
- Select Action: < Install WAD >
- Restart Wii and it should be available to use

## Modifying a WAD
- 

## Downloading Wii Back Up Manager
- (source: http://www.wiibackupmanager.co.uk/downloads.html and be careful of spam ads on the site)
- Download the zip file from the site
- First extract the WiiBackUpManger zip 
- Enter the folder
- Select either the Win64 or Win32 executable (Probably double click WiiBackUppManager_Win64)
- You may have to select yes to allowing the application to run on your computer

## Formatting the Hard Drive for Usage
- Most hard drives do not come in the proper format for use with the Wii
- To fix this, we have to format the drive into FAT32
- The easiest ways to do this are either:
  - Using the built in format option in a file explorer 
  - (Might not work with some hard drives as their is no FAT32 option)
  - Or Using Wii Back Up Manager
- To Use Wii Back Up Manager:
  - (Refer to Downloading Wii Back Up Manager)
  - Once the application is open, click on tools
  - Select Format Drive
  - The first option is for the drive to format, make sure you select the one you will putting into the wii
    - Warning: Anything on the drive will be wiped
  - Select FAT32 as the formatting option
  - Select 32kb cluster size (This should be default anyways)
  - Then click start and wait for the process to finish

## Put Wii games on the hard drive and fix Wii ROMS that are larger than 4GB 
- Problem: Wii ROM (in wbfs format) is larger than 4GB which is not compatible with the FAT32 format of the hard drive being used for the wii
- Solution: Use Wii Back Up Manager (Refer to Downloading Wii Back Up Manager)
- How: 
  - Once in the program click Add then click Files
  - Add all the games you need to fix
  - Check the check box to the left of the game names
  - Select Drive 1 as the place to save to
  - Click where the dropdown menu says inactive and select where the games should be saved to
  - Select yes to creating a wbfs folder
  - Go back to files, click transfer and select drive 1