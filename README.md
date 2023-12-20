# Max/MSP Patches, Abstractions, Externals, RNBO, VSTs, and Ableton Max for Live 
   
By Brian Riordan  
[guaguanco127@gmail.com](mailto:guaguanco127@gmail.com)  
[brianriordanmusic@gmail.com](mailto:brianriordanmusic@gmail.com)   
[https://www.brianriordanmusic.com/](https://www.brianriordanmusic.com/) 

This repository is a project started by Brian Riordan in 2023. Users that have access to either Max/MSP, Ableton Live Suite, the ability to use customized patches, abstractions, externals, or Max for Live devices. Users with access to RNBO can build their own VST or AU audio plugins for free to use with their own DAW.  

The purpose of this project is primarily educational. However, some basic patches or VSTs here are designed with "DAW agnosticism" in mind. If you have access to fundamental mixing plugins, then it doesn't matter which DAW you use.


## Links to Max/MSP Patches, Abstractions, Externals, RNBO, VSTs, and Ableton Max for Live:

[Basic Utility Effects](#utility) 

[Delay Effects](#delay)

[Glitch/Granular Effects](#grain)

[Spectral Effects](#spectral) 

## <a name="utility"></a>Basic Utility Effects

These effects are modeled after the Ableton Utility audio effect. Inspect the patchers to see how they are built. The benefit of having access to these effects as a VST is that they can be used in any DAW, and you can decide on the placement and order of these effects. Additionally, these can be used as externals or abstractions in Max/MSP.  

[br.utility.gain.1.0](https://github.com/guaguanco127/br.utility.gain.1.0)  A basic utility effect that allows the user to adjust the volume of a stereo signal.

[br.utility.mute.1.0](https://github.com/guaguanco127/br.utility.mute.1.0)  A basic utility effect that allows the user to mute a stereo signal.

[br.utility.mono.1.0](https://github.com/guaguanco127/br.utility.mono.1.0)  A basic utility effect that sums a stereo signal into mono with 3 different mix settings.

[br.utility.monobass.1.0](https://github.com/guaguanco127/br.utility.monobass.1.0) A basic utility effect that allows the user to sum frequencies below a cutoff to mono while leaving frequencies above in stereo
 
[br.utility.stereo.1.0](https://github.com/guaguanco127/br.utility.stereo.1.0)  A basic utility effect that enables the user to adjust the mix of a stereo signal, such as swapping, left only, right only, mid, or side. Additionally, the user can change the resulting signal's width or pan.

[br.utility.stereomix.1.0](https://github.com/guaguanco127/br.utility.stereomix.1.0) A basic utility effect that allows the user to mix the individual stereo channels independently. In addition to invert settings, the user can adjust each channel's gain and panning. 

## <a name="delay"></a>Delay Effects   

[br.delay.pitch.1.0](https://github.com/guaguanco127/br.delay.pitch.1.0) A stereo delay effect with a pitchshifter included in the delay line.

## <a name="grain"></a>Glitch/Granular Effects

[br.munge.1.0](https://github.com/guaguanco127/br.munge.1.0) A real-time granulator and an emulation of the munger~ external object from Max/MSP. Additional features, such as the processing of a stereo signal and additional amplitude and stereo envelopes, are included.


## <a name="spectral"></a>Spectral Effects

[br.freeze.1.0](https://github.com/guaguanco127/br.freeze.1.0) A spectral freeze Max/MSP object and Max for Live Device.  

[br.freezex.1.0](https://github.com/guaguanco127/br.freezex.1.0) A spectral freeze object/device similar to br.freeze.1.0, except this allows for crossfading into the next freeze by as much as 10 seconds.

[br.pitchshift.1.0](https://github.com/guaguanco127/br.pitchshift.1.0) A pitchshifting device/object with slight latency and no artifacts. Preferred for harmonization.

[br.whammy.1.0](https://github.com/guaguanco127/br.whammy.1.0) A pitch-shifting device/object with no latency and some artifacts. 







