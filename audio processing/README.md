Note: To reduce the file size i cleared my all outputs, so anyone who wants to see results can open it and run all cells.


A dataset capturing audio recordings over 5-6 days, labeled by time such as "Day-1-Morning," "Day-1-Afternoon," etc., undergoes pre-processing to normalize duration, sampling rate, and reduce noise. The code utilizes Librosa for various tasks: setting up paths, loading audio files, playing samples, extracting features, and performing Fourier Transforms for time-to-frequency domain conversion. Subsequently, the code plots the resulting spectrograms and calculates the mean/average differences of audio files across different times of the day (Morning, Afternoon, Evening, Night). This comprehensive analysis enables a nuanced understanding of audio variations throughout the labeled periods, facilitating effective audio processing and classification.


1. RESULT :

After plotting the FFT i get a plot showing the frequency components of the audio. Peaks in the plot correspond to dominant frequencies in the audio. By comparing the mean or average differences between audio files at different times, i am able analyze how audio features varying with timw.


2. What i learned:

I came to know how to normalize the audio in terms of duration, sample rate, noise reduction and also how make directories and saving processed audios in those directories through code. I learned how to plot audio data on graphs and examine their behavior and characteristics. This allowed me to visually explore the different aspects of audio for example frequencies.


3. Cause-and-effect relationships of data preprocessing:

Data preprocessing normalize the audio in terms of duration, sample rate, noise reduction, noise reduction improves the quality and consistency of audio data. Reducing audio duration conserves storage and speed up analysis. (44100 Hz) sampling rate ensures high-quality audio by capturing detailed sound.


