# Audio Plugins: BR-Utility-StereoMix-1.0 
By Brian Riordan  
guaguanco127@gmail.com  
brianriordanmusic@gmail.com  
[https://github.com/guaguanco127/plugins](https://github.com/guaguanco127/plugins)

These plugins are available as VST3 for Mac and Windows, and AU for Mac. 
Abstractions for Max/MSP, and Max for Live devices also included. 

All versions of these plugins were created in Max/MSP using RNBO 

Max/MSP version 8.5.6
RNBO 1.2.3

## Table of Contents

[BR-Utility-StereoMix-1.0 Info](#plugininfo)  
[Instructions on installing the plugin](#installation)  
[Instructions on using as an abstraction in Max/MSP](#maxmsp)  
[Max for Live Device](#maxforlive)

## <a name="plugininfo"></a>BR-Utility-StereoMix-1.0 Info

Plugin Name: BR-Utility-StereoMix-1.0 from 11-22-2023  
Plugin Manufacturer Name: guaguanco127  
Plugin Manufacturer Code: U003

A basic audio plugin for adjusting stereo settings. This is different from the BR-Utility-Stereo-1.0 plugin as it allows for inverting of the channels, along with panning and gain.
  
**Invert_mode** Allows for inverting the signal of both, or either channel

**Left_Decibels** Adjust the gain of the left channel between -72.0 and +35 decibels. -72.0 instantly converts to negative infinity. 

**Right_Decibels** Adjust the gain of the right channel between -72.0 and +35 decibels. -72.0 instantly converts to negative infinity. 

**Left_Panning** Allows for the left channel coming in to be panned to either channel. Default is -100. (Left). Range is -100.0 to +100.0, with 0.0 being the middle.  

**Right_Panning** Allows for the right channel coming in to be panned to either channel. Default is 100. (Right) Range is -100.0 to +100.0, with 0.0 being the middle.  


## <a name="installation"></a>Instructions on installing the plugin:

1: Install your favorite audio software (DAW) on your computer. Make sure the software is off when installing the plugin
 
2: Locate your plugin plug-in directory. (Usually called a VST directory)  

Some software has this built in to the program file, in which case you may skip this step and proceed to the next one. A DAW such as Ableton Live requires you to do this manually, like so:  

Go to the "Options" menu and select "Preferences".  
Under "Preferences", select the "File Folder" menu.
Click the "Browse" button next to "VST Plug-In Custom Folder".  
Select the folder you would like Ableton to use for VST Plug-Ins.
Confirm that the "Use VST Plug-In Custom Folder" option is turned on, and the file path listed under "VST Plug-In Custom Folder" leads to the folder you just selected.

For VST3:   
For Windows use BR-Win-Utility-StereoMix-1.vst3   
For Macintosh use BR-Mac-Utility-StereoMix-1.vst3 or BR-AU-Utility-StereoMix-1.component

3: Reopen your DAW and search for the plugin the same way you'd open any effect in a track

## <a name="maxmsp"></a>Instructions on using as an abstraction in Max/MSP:


For Max/MSP, create a patch inside a folder. Then copy and paste R-Utility-StereoMix-1.0.maxpat inside of that folder. Create a new object with the name BR-Utility-StereoMix-1.0 and you can use it as an object in your main patch. 

This abstraction was created using gen~ 

The basic version (without the use of gen~) is coming soon. 

The BR-Utility-StereoMix-RNBO-1.0.maxpat version is designed for those who want to learn from, or observe the RNBO methods I used to create all of these plugins. 

## <a name="maxforlive"></a>Max for Live Device:

Coming soon.....
 