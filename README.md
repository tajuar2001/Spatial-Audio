# SpatialAudio
Exploring Digital Signal Processing techniques to create immersive spatial sound using 2-channel audio. This project leverages concepts like Interaural Time Difference (ITD), Interaural Level Difference (ILD), the Pinna Effect, Head-Related Transfer Function (HRTF), and Cross-Correlation to simulate a three-dimensional audio experience. Learn more about our journey and progress[here](https://eecs3dsound.wixsite.com/eecs351g1)

## Key Concepts
### Interaural Time/Level Difference (ITD/ILD)
- These are the differences in time and level of audio signals received by the left and right ears.
- Key to determining the angle of origin of a sound.
- Manipulate audio samples to create the illusion of sound emanating from different directions.

### Pinna Effect
- Focuses on the outer ear's role in sound localization.
- The pinna (visible part of the ear) assists in filtering and directing high-frequency sounds, contributing to vertical localization.

### Head-Related Transfer Function (HRTF)
- Simulates how an individual's ears receive sound from a point in space.
- Can be customized based on empirical data, allowing for a personalized audio experience.

### Cross-Correlation
- A method to analyze the similarity and time lag between two signals.
- Important in aligning audio signals, detecting patterns, and conducting in-depth sound analysis.

### Implementation
In this project, we've implemented various algorithms and techniques to simulate the spatial audio experience. The Jupyter Notebook (SpatialG1.ipynb) in this repository provides an in-depth look at our methods and findings, including:

- Data analysis and visualization techniques for understanding sound characteristics.
- Application of DSP techniques to create spatial sound illusions.
- Experiments with different sound samples and simulation scenarios.

