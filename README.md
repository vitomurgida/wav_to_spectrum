# wav_to_spectrum
A simple Python code which reads an audio recording in .wav format and computes the frequency spectrum of the signal.

It outputs:
- original signal time history
- slice of the time history to be analyzed, arbitrarily chosen by the user, and frequency spectrum based on it
peaks frequencies, amplitudes and rms
- sampling frequency
- measurement duration

The user can choose:
- .wav file location
- time range in which performing the FFT analysis (start and end time)
- maximum frequency to visualize in the spectrum (which, as theory teaches, is limited by the sampling frequency of the microphone used for the measurement)
- threshold for which a peak is peaked or not for frequency peak recognizition, as a percentage of the largest peak

