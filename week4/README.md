# <small>Speech-Emotion-Recognition-SoC</small><br>Week 4

This week is all about audio preprocessing which we will be using to extract features from the audio dataset for our actual project

## Why do we audio preprocessing ?
Audio preprocessing is essential for improving the quality and consistency of audio data, which enhances the performance of machine learning models. Key steps include noise reduction to remove unwanted sounds, normalization to standardize audio levels, and segmentation to break audio into manageable chunks. Feature extraction, such as obtaining MFCCs, transforms raw audio into meaningful representations. These steps help reduce overfitting, improve computational efficiency, and ensure that the models focus on relevant audio features, leading to better accuracy and reliability in tasks like speech and music recognition.

## Some terms to know
Sampling Rate: Number of audio samples per second; higher rates capture more detail.

Amplitude: Loudness of the audio signal; higher amplitude means louder sound.

Frequency: Number of wave cycles per second; determines pitch.

Waveforms: Show amplitude variations over time.

Spectrograms: Display frequency content over time, useful for detailed audio analysis.

## Librosa
We are going to use Librosa for audio preprocessing

-[Documentation](https://librosa.org/doc/latest/index.html)
-[Video Tutorial](https://youtu.be/MhOdbtPhbLU?si=jgJOd2vQDj8f7Rdt)