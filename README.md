Password-Recovery-Tool
======================

 #Intro
 This program was created in 17 hours during a Hackathon as an individual project.
 
 #Description
 When a laptop is locked with password, a checksum of that password is stored to a so-called FlashROM - this is a chip on the mainboard of the device which also contains the BIOS code and other settings, e.g. memory timings. For most brands, this checksum is displayed after entering an invalid password for the third time.
The dramatic 'System Disabled' message is just scare tactics: when you remove all power from the laptop and reboot it, it will work just as before. From such a checksum (also called "hash"), valid passwords can be found by means of brute-forcing. The bypass mechanisms of other vendors work by showing a number to the user from which a master password can be derived. This password is usually a sequence of numbers generated randomly. -- Dogbert's Blog, May 2, 2009

#TheProject
 This application is designed to calculate the key codes of ACER, Sony Vaio and Dell laptopts. The initial version for the progrect was created October 15, 2013 only for ACER and Sony Vaio without graphical components: https://github.com/Rafa1994/BIOS-and-HDD-Key-code-Calculator . 
 This is the developed and final version with a beautiful User Interface and added components. Licesne numbers for each laptop is absolutely unique and this program helps easily to figure out corresponding key codes. The algorithm was figured out by multiple-testing and collecting data from different Internet sources. -- Rafayel Mkrtchyan, April 4, 2014.
