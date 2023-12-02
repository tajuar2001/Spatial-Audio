# SpatialAudio

An exploration of Digital Signal Processing techniques to create spatial sound with 2-channel audio. Read more about the project and our progress [here](https://eecs3dsound.wixsite.com/eecs351g1)


## Key Concepts

### Interaural Time/Level Difference (ITD/ILD)
- differences in timing and level between the left and right channels
- allows for computation of the angle of the sound
- conversely, can be used to manipulate a given audio sample to sound as if it came from a different angle

### Pinna Effect
- visible part of outer ear
- directional filtering of high-frequency sounds

### Head-Related Transfer Function (HRTF)
- system for approximating how audio sounds like to humans
- can be drawn empirically with lab equipment (or online databases containing empirical data)

### Cross-Correlation
- signal technique for finding signal similarities
- can compute time shifts between two signals
- useful for alignment, pattern matching, and analysis
