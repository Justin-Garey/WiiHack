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

## Setting up d2x cIOS Installer
- Install d2x cIOS Installer from the HomeBrew Browser
- (For official guide: https://wii.guide/cios)
- Wii Must be connected to the internet
- Under CIOS SETTINGS
- - Select cIOS <"v10 beta52 d2x-v10-beta52">
- - Select cIOS base <57>
- - Select cIOS slot <249>
- - Select cIOS revision <65535>
- Press A twice
- After it has successfully installed, press A to go back to CIOS SETTINGS
- Under CIOS SETTINGS
- - Select cIOS <"v10 beta52 d2x-v10-beta52">
- - Select cIOS base <56>
- - Select cIOS slot <250>
- - Select cIOS revision <65535>
- B to exit
- Restart the Wii

## For Wii Menu Shortcuts
- Install YAWMM - Yet Another Wad Manager
- See below on how to create a WAD
- Open and use IOS 249
- Select NAND emulator device < disable >
- Select Source device: < Wii SD Slot >
- Select the WAD you would like to use
- Select Action: < Install WAD >
- Restart Wii and it should be available to use

## Creating a WAD