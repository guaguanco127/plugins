#Audio Plugins: BR-Utility-Stereo-1.0 
By Brian Riordan  
guaguanco127@gmail.com  
brianriordanmusic@gmail.com  
[https://github.com/guaguanco127/plugins](https://github.com/guaguanco127/plugins)

These plugins are available as VST3 for Mac and Windows, and AU for Mac. 
Abstractions for Max/MSP, and Max for Live devices also included. 

All versions of these plugins were created in Max/MSP using RNBO 

Max/MSP version 8.5.6
RNBO 1.2.3

##Table of Contents

[BR-Utility-Stereo-1.0 Info](#plugininfo)  
[Instructions on installing the plugin](#installation)  
[Instructions on using as an abstraction in Max/MSP](#maxmsp)  
[Max for Live Device](#maxforlive)

##<a name="plugininfo"></a>BR-Utility-Gain-1.0 Info

Plugin Name: BR-Utility-Stereo-1.0 from 11-21-2023  
Plugin Manufacturer Name: guaguanco127  
Plugin Manufacturer Code: U002

A basic audio plugin for adjusting stereo settings.
  
**Modes:**   
**Stereo:** Normal stereo signal passes through  
**Swap:** This swaps the stereo signal, so the left is coming out of the right, and the right is coming out of the left  
**Left:** The left signal now plays through both the left and right  
**Right:** The right signal now plays through both the left and right  
**Mid:** Both signals added together and divided in half, in mono  
**Side:** A mono signal that consists of only signals that were in the stereo filed (sides) but not in the middle of the signal. 

**Pan:**  
Pans the stereo signal left (-100.0), midle (0.0), or right (100.0)

**Width:**  
Adjusts the width of of the stereo signal. 100. is normal stereo. 0. is a mono signal.


##<a name="installation"></a>Instructions on installing the plugin:

1: Install your favorite audio software (DAW) on your computer. Make sure the software is off when installing the plugin
 
2: Locate your plugin plug-in directory. (Usually called a VST directory)  

Some software has this built in to the program file, in which case you may skip this step and proceed to the next one. A DAW such as Ableton Live requires you to do this manually, like so:  

Go to the "Options" menu and select "Preferences".  
Under "Preferences", select the "File Folder" menu.
Click the "Browse" button next to "VST Plug-In Custom Folder".  
Select the folder you would like Ableton to use for VST Plug-Ins.
Confirm that the "Use VST Plug-In Custom Folder" option is turned on, and the file path listed under "VST Plug-In Custom Folder" leads to the folder you just selected.

For VST3:   
For Windows use BR-Win-Utility-Stereo-1.vst3   
For Macintosh use BR-Mac-Utility-Stereo-1.vst3 or BR-AU-Utility-Stereo-1.component

3: Reopen your DAW and search for the plugin the same way you'd open any effect in a track

##<a name="maxmsp"></a>Instructions on using as an abstraction in Max/MSP:


For Max/MSP, create a patch inside a folder. Then copy and paste br-utility-gain-1.0.maxpat inside of that folder. Create a new object with the name br-utility-stereo-1.0 and you can use it as an object in your main patch. 

This abstraction was created using gen~ 

The basic version (without the use of gen~) is coming soon. 

The br-utility-stereo-rnbo-1.0.maxpat version is designed for those who want to learn from, or observe the RNBO methods I used to create all of these plugins. 

##<a name="maxforlive"></a>Max for Live Device:

Coming soon.....
 