# Audio Plugins: BR-Stutter-A-1.0 
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

[BR-Stutter-A-1.0 Info](#plugininfo)  
[Instructions on installing the plugin](#installation)  
[Instructions on using as an abstraction in Max/MSP](#maxmsp)  
[Max for Live Device](#maxforlive)

## <a name="plugininfo"></a>BR-Stutter-A-1.0 Info

Plugin Name: BR-Stutter-A-1.0 from 11-21-2023  
Plugin Manufacturer Name: guaguanco127  
Plugin Manufacturer Code: S001

A glitch effect that captures a small segment of sound (up to 1000 milliseconds) and repeats.
    
**On_off:** When "off" is selected, sound passes through as is, when "on" is selected, the effect is processing the signal. Please note that this is different than disabling the plugin in your DAW. The plugin must be enabled from the DAW in order for the audio to be recorded so that it can be glitched at a later time. 
 
**retrigger:** When "1" is selected the effect captures the next chunk of sound that was occuring at that moment.  

**Size in ms:** This dictates how large of a sample will be captured. This only changes when the effect is either turned off then back on, or retriggered. It will not change the sound while the stutter is working on a sample.  

**speed:** The speed of the sample. 1.0 = normal, 2.0 = twice as fast. -1.0 = backwards. The range is from -16.0 to 16.0 and the default is 1.0  

**mix_mode:** Insert = an interruption of the sound, gate = you will not hear the dry signal as the plugin is "off," you will only hear it once the plugin is "on"  

**latent_mode:** When latent mode is "on" it means that the stutter will wait to grab the next sample. The wait is equivalent to the "size in ms." When latent mode is "off" the stutter grabs the sample immediately. The default is "on." The reason for this feature is that the stutter can only grab what has already been recorded. Sometimes performers and producers what to grab what is about to be played, or the beginning of a musical gesture


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
For Windows use BR-Win-Stutter-A-1.vst3   
For Macintosh use BR-Mac-Stutter-A-1.vst3 or BR-AU-Stutter-A-1.component

3: Reopen your DAW and search for the plugin the same way you'd open any effect in a track

## <a name="maxmsp"></a>Instructions on using as an abstraction in Max/MSP:


For Max/MSP, create a patch inside a folder. Then copy and paste BR-Stutter-A-1.0.maxpat inside of that folder. Create a new object with the name BR-Stutter-A-1.0 and you can use it as an object in your main patch. 

This abstraction was created using gen~ 

The basic version (without the use of gen~) is coming soon. 

The BR-Stutter-A-rnbo-1.0.maxpat version is designed for those who want to learn from, or observe the RNBO methods I used to create all of these plugins. 

## <a name="maxforlive"></a>Max for Live Device:

Coming soon.....
 