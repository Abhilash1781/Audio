# ClassTone Classifier
A deep learning project which classify and categorize the audio recordings of my classmates.

## Introduction:
Audio classification is the process of categorizing audio signals into predefined labels or categories based on their acoustic features . It is an important task in audio signal processing , with numerous applications in various domains , including speech recognition , emotion recognition etc.
In the recent advances in deep learning , Convolutional Neural Networks(CNN) have emerged as a powerful tool for audio classification . They can extract relevant features from audio signals in a data-driven manner and achive high accuracy in classification tasks.

## Aim:
To develop an accurate audio classification system that can classify and categorize the voices of my classmates.

## Technology used:
- #### Language
    - ![PYTHON](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)
      

- #### Libraries
  - ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
  - ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
  - ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
  - ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
  - ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
 

- #### IDE
  - ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)

## Prerequisites:
```bash

  matplotlib==3.7.0
  numpy==1.23.5
  pandas==1.5.3
  scikit-learn==1.2.1
  seaborn==0.12.2
  sklearn==0.0
  tqdm==4.65.0
  tensorflow==2.11.1
  keras==2.11.0
  librosa==0.10.0
```

## Motivation and Inspiration:
We aim to differentiate ourselves by taking a hands-on approach to data collection, analysis , and exploration rather than replying on pre-existing datasets from platforms like kaggle. 


## Data Collection:
We collected 1-minute audio samples from 11 of our classmates including us . Each audio samples were saved in .wav format instead of .mp3 format becuase .mp3 format compresses the audio which may not suitable while feature extraction.

## Note:
Unfortunately , we coulf not able to  share the audiosamples/dataset publicly inorder to preserve privacy of our contributors. 

You can create your own dataset by collecting clear audio samples from your classmates and save them as .wav format.

## Data pre-processing:
We partitioned each recording into 10 seperate 5-second audio files . By breaking down the audio into smaller segments , our model can process and analyze the data more effectively , enabling more accurate and granular predictions.




