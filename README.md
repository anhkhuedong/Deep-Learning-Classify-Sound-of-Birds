# Classify Sound of Birds with Deep Learning Models

### Objectives

This project leverages deep learning techniques to analyze and classify bird types based on their sounds.

1. Exploratory Data Analysis on audio file (mp3)
2. Prepare and preprocess dataset for machine learning model
3. Develop and optimize deep learning model to achieve 97% accuracy
   
### Data Source

Sound of 114 Species Of Birds Till 2022: (https://www.kaggle.com/datasets/soumendraprasad/sound-of-114-species-of-birds-till-2022)

### Methodology

1. Exploratory Data Analysis on one audio file (mp3) (for illustration purposes) 
    * Fourier Transform, Short-time Fourier Transform
    * Amplitude vs Time graph
    * Mel Frequency Cepstral Coefficients (MFCC) graph
2. Prepare and preprocess dataset for machine learning model
    * Randomly select and process 19 bird types from 114 species in the original dataset
    * Process all audio files for these 19 bird types
    * Segment audio files into 15-second duration to increase the number of samples
    * Develop MFCC for each 15-second audio segment and store all data in JSON file
3. Develop and optimize deep learning model to achieve 97% accuracy
    * Build a neural network with various activation methods e.g. relu, softmax
    * Optimize model with different learning rates, # of epochs, batch sizes, dropout rate, and regularization
### Acknowledgements

1. Sound Of 114 Species Of Birds Till 2022
(https://www.kaggle.com/datasets/soumendraprasad/sound-of-114-species-of-birds-till-2022)
   
2. Music Genre Classification with Python - A Guide to Analyzing Audio/Music Signals in Python by Parul Pandey
(https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8)

3. Deep Learning (for Audio) with Python playlist by Valerio Velardo - The Sound of AI
(https://www.youtube.com/playlist?list=PL-wATfeyAMNrtbkCNsLcpoAyBBRJZVlnf) 
