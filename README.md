# Music genre classification

In this project i use multiple classification models and CNN to classify audio genres. The goal is to classify raw music audio into genres.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install librosa.

```bash
!pip install librosa
```

## Data

A collection of 10 genres with 100 audio files each, all having a length of 30 seconds (the famous GTZAN dataset, the MNIST of sounds)

CSV file - Containing features of the audio files. One file has for each song (30 seconds long) a mean and variance computed over multiple features that can be extracted from an audio file.

## Modeling

Two approches taken: standard machine learning, and deep learning. 

### Machine Learning Argorithms:

* LogistiocRegression
* SVM
* KNeighborsClassifier
* DecisionTreeClassifier
* RandomForestClassifier
* Naïve Bayes

### Deep Learning

I use TensorFlow to build neural networks. We see whether models built from extracted features perform better than CNN with tabular data.