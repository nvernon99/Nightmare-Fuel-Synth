# Nightmare Fuel - Synthesizer Plug-In

Summary:
- This is a JUCE/C++ based MIDI-controlled monophonic synthesizer in VST3 and Standalone (.exe) formats
- Uses 6 saw wave oscillators
- UI is made up of 4 main sections: Filter, ADSR, Pitch, and Reverb
- It's made to sound aggressive and freaky! Certainly not designed for warm or sterile tones

Filter:
- State Variable TPT filter in lowpass mode. Cutoff and resonance can be controlled
- Drive parameter which modifies the input gain into a tan(x) function waveshaper

ADSR
- Simple ADSR Envelope (effecting the amplitude of each note) generator which can be controlled by the UI

Pitch
- Detune slider which detunes some of the oscillators from the fundamental frequency 
- Whammy slider which pitchshifts all oscillators up to 4 octaves up

Reverb
- Reverb size, width (panning), and damp (lowpass) are all controlled via the UI
- Dry and wet levels can be modified

Some of the code is based on open-source code by Joshua Hodge ("The Audio Programmer") as part of his TAP Synthesizer. The rest of the code is by me, Nolan Vernon

Enjoy!
