
# Efficient Highlights Extraction using Python

Extraction of highlights from any of the sports using Python & computer vision libraries.


## Introduction


Professional editors typically spend a significant amount of time manually selecting and cropping interesting events from matches to extract highlights. This process can be quite time-consuming, especially when dealing with multiple matches. However, we have developed a Python-based model that automatically extracts highlights from a given video, providing an efficient solution. 
## Idea behind project

- Whenever something exciting happens during a game, the commentator's voice rises and the fans in the stadium start cheering. 
- The increasing pitch of the commentator's voice and the heightened cheering from the audience are strong indicators of exciting and noteworthy moments in the game. We are applying this idea to our project.
## Algorithm 

    1. Take a video file. (.mp4, .wmv, .mkv)

    2. Extract the audio from the video file which we are using. (.mp3, .wav)

    3. Break that audio into small chunks.

    4. Compute energy for those chunks. 

    5. We'll label each chunk as either an exciting play or not, depending on the threshold value we've set.

    6. Extract those highlight moments from the video.

    7. Merge all highlight clips to make a short video of highlights of the particular match.

    




## Features of an audio signal

- Zero Crossing Rate
- RMSE / Energy
- Spectral centroid
- STFT (Short Term Fourier Transform)
- Mel-Frequency Cepstral Coefficients (MFCCs)




## References

https://www.analyticsvidhya.com/blog/2022/05/comparison-of-the-rms-energy-and-the-amplitude-envelope/

https://khareanu1612.medium.com/audio-signal-processing-with-spectrograms-and-librosa-b66a0a6bc5cc

https://www.altexsoft.com/blog/audio-analysis/


