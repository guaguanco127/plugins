# Max/MSP Patches, Abstractions, Externals, RNBO, VSTs, and Ableton Max for Live 
   
By Brian Riordan  
[guaguanco127@gmail.com](mailto:guaguanco127@gmail.com)  
[brianriordanmusic@gmail.com](mailto:brianriordanmusic@gmail.com)   
[https://www.brianriordanmusic.com/](https://www.brianriordanmusic.com/) 

This repository is a project started by Brian Riordan in 2023. Users with access to either Max/MSP or Ableton Live Suite will be able to use customized patches, abstractions, externals, or Max for Live devices. Users with access to RNBO can build their own VST or AU audio plugins for free to use with their own DAW.    

The purpose of this project is primarily educational. However, some basic patches or VSTs here are designed with "DAW agnosticism" in mind. If you have access to fundamental mixing plugins, then it doesn't matter which DAW you use.

The naming system (br.xxxx.xx.1.0) is because all of these are prototypes. A more "proper" name will occur when these reach a certain level of quality regarding their stability and GUI. When that happens, the effect may move to a Gumroad account. 

Please contact me at the emails provided above if you have any questions, notice any errors, or have any requests. 


## Links to Max/MSP Patches, Abstractions, Externals, RNBO, VSTs, and Ableton Max for Live:

[Basic Utility Effects](#utility) 

[Delay Effects](#delay)

[Glitch/Granular Effects](#grain)

[Spectral Effects](#spectral) 

[Modulation Tools](#modulation)

[Future Effects](#future) 

## <a name="utility"></a>Basic Utility Effects

These effects are modeled after the Ableton Utility audio effect. Inspect the patchers to see how they are built. The benefit of having access to these effects as a VST is that they can be used in any DAW, and you can decide on the placement and order of these effects. Additionally, these can be used as externals or abstractions in Max/MSP.  

Many of these effects have a RNBO patch included that allow the user to export as either a Max/MSP external, or a VST. 

[br.utility.gain.1.0](https://github.com/guaguanco127/br.utility.gain.1.0)  A basic utility effect that allows the user to adjust the volume of a stereo signal.

[br.utility.mute.1.0](https://github.com/guaguanco127/br.utility.mute.1.0)  A basic utility effect that allows the user to mute a stereo signal.

[br.utility.mono.1.0](https://github.com/guaguanco127/br.utility.mono.1.0)  A basic utility effect that sums a stereo signal into mono with 3 different mix settings.

[br.utility.monobass.1.0](https://github.com/guaguanco127/br.utility.monobass.1.0) A basic utility effect that allows the user to sum frequencies below a cutoff to mono while leaving frequencies above in stereo
 
[br.utility.stereo.1.0](https://github.com/guaguanco127/br.utility.stereo.1.0)  A basic utility effect that enables the user to adjust the mix of a stereo signal, such as swapping, left only, right only, mid, or side. Additionally, the user can change the resulting signal's width or pan.

[br.utility.stereomix.1.0](https://github.com/guaguanco127/br.utility.stereomix.1.0) A basic utility effect that allows the user to mix the individual stereo channels independently. In addition to invert settings, the user can adjust each channel's gain and panning. 

## <a name="delay"></a>Delay Effects   

[br.delay.pitch.a](https://github.com/guaguanco127/br.delay.pitch.a) A stereo delay with a pitch-shifter inside the delay line, so every repeat is shifted again. Protected feedback loop (soft saturation, Highpass/Lowpass) that can hold or build, low CPU at rest.

[br.delay.pitch.b](https://github.com/guaguanco127/br.delay.pitch.b) Version b of br.delay.pitch: the same pitch-shifting delay plus just-intonation pitch steps (overtone scale) with fine-tune cents, and randomizing of pitch, delay time and feedback -- by button, automatically, or on every attack you play.

[br.spacedelay](https://github.com/guaguanco127/br.spacedelay) A stereo multi-voice delay: up to 12 voices keep skipping to random delay times (crossfaded, click-free), each with its own randomly moving filter, amplitude and panning, plus a freeze that loops only the last moments of the delay.

## <a name="grain"></a>Glitch/Granular Effects

[br.munge](https://github.com/guaguanco127/br.munge) A real-time granulator and an emulation of the munger~ external object from Max/MSP. Additional features, such as the processing of a stereo signal, additional amplitude and stereo envelopes, ping-pong feedback, and a freeze that keeps the grains playing from only the last moments of the input, are included.

[br.stutter.a](https://github.com/guaguanco127/br.stutter.a) An abstraction/device that is built around the Max/MSP stutter~ object. A real-time granular glitch effect that is a signal capture buffer. 

[br.stutter.b](https://github.com/guaguanco127/br.stutter.b) An abstraction/device that is built around the Max/MSP stutter~ object. This contains all features as br.stutter.a but with extras. This effect adds LFOs in sync with each grain that can manipulate a filter, amplitude, and panning. 

[br.stutter.c](https://github.com/guaguanco127/br.stutter.c) An abstraction/device that is built around the Max/MSP stutter~ object. This contains all features as br.stutter.b but with extras. This effect includes an auto re-triggering feature, auto-detection, adjustment of the phase (starting position) of the grains, and a refresher that restarts the grain when it reaches a certain position within the phase.




## <a name="spectral"></a>Spectral Effects

[br.freeze](https://github.com/guaguanco127/br.freeze) A spectral freeze Max/MSP object and Max for Live Device. It can also freeze automatically on every attack you play.  

[br.freezex](https://github.com/guaguanco127/br.freezex) A spectral freeze object/device similar to br.freeze, except this allows for crossfading into the next freeze by as much as 10 seconds. It can also freeze automatically on every attack you play.

[br.pitchshift](https://github.com/guaguanco127/br.pitchshift) A pitchshifting device/object with slight latency and no artifacts. Preferred for harmonization.

[br.whammy.1.0](https://github.com/guaguanco127/br.whammy.1.0) A pitch-shifting device/object with no latency and some artifacts. 

## <a name="modulation"></a>Modulation Tools

[br.scale](https://github.com/guaguanco127/br.scale) Max/MSP abstractions that turn an LFO into volume or frequency on curves that sound even to the ear.

## <a name="future"></a>Future Effects/Instruments

These are planned effects to be released on a later date. 

br.scrub.1.0 A granular effect that scrubs through a buffer in real-time. 

br.delay.reverse.1.0 A reverse delay effect 

br.skipper.1.0 A granular effect that acts like a chaotic degital delay that randomly skips between delay times. 

br.repeater.1.0 A type of looper that plays back the most recent "n seconds" stereo signals between 0. and 10,000 ms. This differs from a regular looper in that it reads from a circular buffer. It is reactionary in the sense that if you hear something that just happened you can go back and grab it. Scrubbing and speed features will be available. 

br.strong.1.0 A Karplus Strong style synth with different features. Higher fideltiy and deeper sound than the traditional synth. 

br.retrigger.1.0 A granular sampler that can retrigger any sample as frequent as the nyquist frequency without changing the pitch. Pitchshifting feature for timbrel adjustments will be a feature. 

br.tone.1.0 A standard tone generator. Sine, Sawtooth, Triangle, Square, White Noise, and Pink Noise. 

br.delay.1.0 A stereo delay with more dynamic features than the typical stock plugin. Analog and digital modes, along with cross feedback features, and tape warp effects will be featured.

br.comber.1.0 Not your typical comb filter. A cascade of all pass filters create many chaotic possibilities. Almost a granular sound. 

br.looper.1.0 Not your typical looper. Various granular effects will be a feature. 

br.modulator.1.0 A variety of modulators (chorus, flanger, phasor, tremolo, vibrato) with a variety of LFOs with folding and chaotic features 

br.synth.detect.1.0 A synth that takes in an audio signal and turns it into a synth.

Many more.....









