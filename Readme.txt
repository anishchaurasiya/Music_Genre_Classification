Our code repository contains various notebooks for each task. To reproduce the code, please follow the instructions below - 

1) Download all the notebooks and upload them on your google drive

2) Download the 3 datasets we have used for our experiments:
a)https://github.com/mdeff/fma
b)https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification
c)https://research.google.com/audioset/

and upload them on the google drive. Keep in mind this location as you will have to mount the drive and run accordingly

The following contains summaries about each of the notebooks - 

File: music_genre.ipynb and gtzan_v2.ipynb

These notebooks contains 4 experiments conducted on the GTZAN dataset.The GTZAN dataset also contained feature vectors corresponding for every audio file. Two files with features of audio cropped to 3 sec and audio cropped to 30 sec were provided. We directly applied various ML algorithms to these features and report the accuracy. Thereafter, we also performed our own feature engineering on 3sec and 30sec clips through calculating the chroma and mfcc features of the datasets creating a 75 x 1 feature vector for every audio file. These feature vectors were passed through 7 machine learning algorithms - Naive Bayes, Stochastic Gradient Descent classifier, K-Nearest Neighbour, Decision Tree, Random Forest, Support Vector Machine and Logistic Regression.

File: google_dataset.ipynb

In this notebook, we provide a novel approach in creating our own custom data set for music genre classification. We utilize the Google audio dataset [ ] and write our own scripts to extract and categorize the audio files. This dataset contains time stamps of YouTube videos and the corresponding genres. We use our scripts to download these youtube videos, convert them to the lossless wave files and categorize them into the provided genres. This dataset contained audio files classified into 7 genres. We applied feature engineering to calculate a 97-dimensional spectral feature vector for every audio file. Thereafter, we applied three algorithms - Logistic Regression, Random Forest and Support Vector Machine on these features.

File: DS203_EDA.ipynb

In this notebook, explorative data analysis has been performed on the FMA dataset. Since our experiments were based on GTZAN dataset and that required EDA in the experiment notebooks, we decided to perform EDA separately on the FMA dataset for completeness.

Link for video presentation - https://drive.google.com/drive/folders/1sAo-zuPXJ16QzBQWQcxzavDAcwXbWh9b?usp=sharing

