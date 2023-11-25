# Audio Plugins: BR-Delay-Pitch-1.0 
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

[BR-Delay-Pitch-1.0 Info](#plugininfo)  
[Instructions on installing the plugin](#installation)  
[Instructions on using as an abstraction in Max/MSP](#maxmsp)  
[Max for Live Device](#maxforlive)

## <a name="plugininfo"></a>BR-Delay-Pitch-1.0 Info

Plugin Name: BR-Delay-Pitch-1.0 from 11-24-2023  
Plugin Manufacturer Name: guaguanco127  
Plugin Manufacturer Code: D002

A 10 second delay that emmulates both digital and analog processes. 

This plugin includes all of the same features as the BR-Delay-1.0. However, it differs because a pitch-shifter is inserted into the delay lines and feedback. This way each repeat will be transposed based on the pitchshift ammount. 

WARNING: Some settings may cause the amplitude of the plugin to explode, feedback, or distort. Because of this, the -0.5 to +0.5 range of the pitch-shifter has been disabled. Additionaly, the feedback feature has been scaled back in half. Additionally, a volume to the delay has been included at the end of its signal chain.
    
**On_Off:** When "off" is selected, sound passes through as is, when "on" is selected, the effect is processing the signal. 
 
**Left Time ms:** The delay time in milliseconds for the left channel. Please note that while "Linked" is selected in "Stereo_mode" the higher delay time between left and right will always be the perscribed delay time for both channels.  

**Right_Time_ms:** The delay time in milliseconds for the right channel. Please note that while "Linked" is selected in "Stereo_mode" the higher delay time between left and right will always be the perscribed delay time for both channels.  

**Stereo_mode:** There are three different modes that dictate how the delay times work in stereo. 

When "Linked" is selected, then each channel will be the same delay time, using the higher of the two times between left and right. 

When "stereo" is selected then each channel will be independently set to its own delay time. This could mean that each channel will fall out of phase with each other over time. 

When "PingPong" is selected, a ping pong effect will occur with the stereo channel. First, a stereo delay will occur, then the feedback will remain linked to whichever delay time is highest betwen the right and the left.

**Delay_mode:** There are two different modes that dictate how delay times change.

When "Stereo" is selected, delay times can be changed without changing the pitch.

When "Analog" is selected, delay times change with an emulation of tape delay with dopler pitch shift effects. The duration of change is dictated by the "Tape_morph_ms" duration. 

**Tape morph ms:** Perscribes the time it takes for delay times to change when "Analog" is selected in Delay_mode. This feature is dissabled when "Digital" mode is selected. 

**Feedback:** Perscribes the amount of feedback amplitude in the delay lines. 0. = no feedback. 1. = a seemingly infinite loop. 0.5 = half feedback. 

**Feedback_mode:** Perscribes the behaviour of the stereo feedback lines.

When "Normal" is selected, the stereo delay feeds back with right channel to right, and left channel to left. 

When "Swap" is selected, the right channel feeds back to the left, and the left channel feeds back to the right. 

**Feedback_mode:** The percentage of dry and wet signal. 0.0 = only dry signal, and 100.0 = only the wet signal. 50.0 is 50% of each.

**Filter Freq 1:** The delay lines, and the feedback, have high pass and low pass filters. The lower of the two filter frequencies will always act as the high pass filter. The higher of the two frequencies will always act as the low pass filter. 

**Filter Freq 2:** The delay lines, and the feedback, have high pass and low pass filters. The lower of the two filter frequencies will always act as the high pass filter. The higher of the two frequencies will always act as the low pass filter. 

**Pitchshift:** The amount of transposition that should be applied to the delayed signal and its feedback. Each integer is equivalent to a semitone, or a half step. -1.0 pitch-shifts down by a semitone, while -0.5 is down by a quarter tone. -12.0 is an octave down, while +12.0 is an octave up. The range is -12.0 to 12.0.

**Delay_Volume:** A volume adjuster in decibels with a range of 0.0 dB to -72. dB. The default is set to -9 dB. 


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
For Windows use BR-Win-Delay-1.vst3   
For Macintosh use BR-Mac-Delay-1.vst3 or BR-AU-Delay-1.component

3: Reopen your DAW and search for the plugin the same way you'd open any effect in a track

## <a name="maxmsp"></a>Instructions on using as an abstraction in Max/MSP:


For Max/MSP, create a patch inside a folder. Then copy and paste BR-Delay-1.0.maxpat inside of that folder. Create a new object with the name BR-Delay-1.0 and you can use it as an object in your main patch. 

This abstraction was created using gen~ 

The basic version (without the use of gen~) is coming soon. 

The BR-Delay-rnbo-1.0.maxpat version is designed for those who want to learn from, or observe the RNBO methods I used to create all of these plugins. 

## <a name="maxforlive"></a>Max for Live Device:

Coming soon.....
 