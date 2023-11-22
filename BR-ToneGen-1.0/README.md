# Audio Plugins: BR-ToneGen-1.0 
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

[BR-ToneGen-1.0 Info](#plugininfo)  
[Instructions on installing the plugin](#installation)  
[Instructions on using as an abstraction in Max/MSP](#maxmsp)  
[Max for Live Device](#maxforlive)

## <a name="plugininfo"></a>BR-ToneGen-1.0 Info 

Plugin Name: BR-ToneGen-1.0 from 11-21-2023  
Plugin Manufacturer Name: guaguanco127  
Plugin Manufacturer Code: T001

A basic tone generator that allows you to switch between a since tone, triangle, sawtooth, or square wave. White noise and pink noise generators are also available.

Frequency is available between 20 hz and 22,000 hz

A basic audio plugin for adjusting the volume of a stereo signal. 
The decibel range is from -72.0 dB to 0.0 dB.
-72 dB is converted to negative infinity dB.
Currently works in any sample rate or bit depth. 


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
For Windows use BR-Win-ToneGen-1.vst3   
For Macintosh use BR-Mac-ToneGen-1.vst3 or BR-AU-ToneGen-1.component

3: Reopen your DAW and search for the plugin the same way you'd open any effect in a track

## <a name="maxmsp"></a>Instructions on using as an abstraction in Max/MSP:


For Max/MSP, create a patch inside a folder. Then copy and paste br-ToneGen-1.0.maxpat inside of that folder. Create a new object with the name br-ToneGen-1.0 and you can use it as an object in your main patch. 

This abstraction was created using gen~ 

The br-ToneGen-rnbo-1.0.maxpat version is designed for those who want to learn from, or observe the RNBO methods I used to create all of these plugins. 

## <a name="maxforlive"></a>Max for Live Device:

Coming soon.....
 