# trigger-word
trigger-word-detection
based on the project in coursera

task1 - cleaning the audio files, actually the sam words spoken was recorded by people, so I need to exactly and manually trim the clips to include just the sam sound and also the format of the recorded sound was in opus, so had to convert it to wave file

task2 - clean the audio samples such that they are 10s long and have a sampling frequency in common

Some of the useful sources that I found online are:

1. https://www.dlology.com/blog/how-to-do-real-time-trigger-word-detection-with-keras/
  Here there is a good explanation of the procedure and also how to do the trigger word detecction in real time
  
2. https://github.com/Kulbear/deep-learning-coursera/blob/master/Sequence%20Models/Trigger%20word%20detection%20-%20v1.ipynb

Here the coursera assignment for the tutorial has been solved fully


* The sampling rate which they have taken as 441000 is a function of the microphone, that means that for every second of the audio,there are about 44100 samples taken.

*****7/july/2019*****

the task is to create a training example, generate its spectogram and analyse and finf ou the required time step in the input and output.
