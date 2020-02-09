[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/benjaminaschultz/audio-processing-tutorials/HEAD)
# Audio Processing Tutorials
This is a collection of python jupyter note books exploring and explaining some different audio processing techniques/effects. I'm writing these mostly to satisfy my own curiosity, but maybe you'll enjoy coming along for the ride.

The notebooks here are designed to work with Binder, so no local installation is required. Click the binder badge above to build an image abnd start exploring. If you'd like to modify them and save the results, clone the repository, initialize a virtual environment and install the requirements via pip.

```
git clone git@github.com:benjaminaschultz/audio-processing-tutorials.git
cd audio-processing-tutorials
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

Then launch the notebook server

```
jupyter notebook
```


I'm aiming to eventually have notebooks on the following subjects

* Sound basics - a vibrating string, the harmonic series, 12 tone equal temperment, how human percieve pitch and rhythm
* Audio file types and representing sound on computers (MIDI, wav, mp3, sampling)
* Frequency Analysis, Fourier Transforms and Timbre [here](link)
* Overdrive, distortion
* Reverb, Chorus
* Placing sounds in space (Balance, Reverb cont'd)
* Post-processing vs Low-latency processing
* Weird "effects pedals" (time warp, harmonic/overtone manipulation)
* Attack, sustain and other transients
* Compression
* Packaging plugins for VST

