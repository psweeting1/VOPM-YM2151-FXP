# VOPM-YM2151-FPX
Want to make music using the YM2151 on your Mac, but finding it a complete pain to get working, then you've come to the right place.

# What is VOPM?
VOPM is an emulation of the Yamaha YM2151 (OPM) 4 operator FM sound chip (This software was not created by me). It has a Windows and Mac version. Using it on Windows is pretty easy and straight forward using lost of free VST host plugins, however using on Mac has proven to be a challenge. You can download the emultor here: [vst4](https://vst4free.com/plugin/1066/)

VOPM can open and save OPM files, this only works on Windows OS, but by using a VST host plugin you can also import and export FXP which will work with VOPM. FXP is a more universal format that can be used across Windows, Mac and Linux.

# Mission
Convert all OPM files to FXP to be used on Mac and Windows, no need to be reliant on OPM file formats that may or may not open correctly.

# How to use VOPM on Mac.
When you download VOPM for mac [vst4](https://vst4free.com/plugin/1066/) you'll find there is a file called VOPM.vst, this is your Virtual Instrument for the YM2151 and what you'll be importing into a VST host plugin.

In order to get VOPM to work on your Mac, you're going to need a VST host plugin. 

Here is a couple of VST Hosts that have been proven to work with VOPM on Mac.
[DDFM](https://ddmf.eu/metaplugin-chainer-vst-au-rtas-aax-wrapper/) 
[Blue Cat's PatchWork](https://www.bluecataudio.com/Products/Product_PatchWork/)

Depending on what you're using whether it's Logic Pro, Pro Tools or Cubebase etc, you can use theses VST host plugins with your music software of choice. (You can use the VST host as a stand alone as well). 

Please be aware some Mac OS's (Catalina) will block VOPM from opening when importing them into VST host Plugns. You'll need to temparoy disabled your gatekeeper on your Mac OS using terminal commands. 
[Helpful Link](https://osxdaily.com/2015/05/04/disable-gatekeeper-command-line-mac-osx/)

Don't forget to re-enable your gatekeeper, safety first.

Once you've succeccfully opened VOPM on your Mac using whatever VST host plugin of choice, you'll probably find it wont open a OPM file, a file format that VOPM can use to save and open instruments and sounds from the YM2151. So now we're stuck, we can't use the VOPM on Mac using OPM files (if you had any).

# What is this repo

You can find OPM files of every single Sega game released on the internet, containing the present instruments used in the game. Here in this repo I've converted as many OPM files as I could to FXP so you can open it on Windows and Mac easily without having to be restrained by OPM files. 

Yes, I haven't been able to do every single OPM on there, but with time this repo will grow with time.

# How do you convert OPM in to FXP?

Using a Windows machine (Boo!), find yourself a VST host plugin, I used VST mini host and open VOPM. Once you have VOPM open, import an OPM file, then once you've imported and tested it works, use your VST host plugin to export FXP files.

# Can I help?

If you've followed this documentation and have managed to export FXP files of each instrument from a game level or whole game and you want to share it with the world like I have, then please create a merge request and I'll review it and add it to the repo.

# Thank you

Thank you for taking the time to read my documentation and use my repo, if you have found and errors or need help, please raise an issue and I'll try and help.

Big thank you to the creator of VOPM and everyone that has created the OPM files that work with the VOPM. 



