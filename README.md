# emotion_analysis
# Emotion Prediction from Audio Data
This project aims to predict emotions from audio data using various Python libraries and machine learning techniques. Emotion recognition from audio is a challenging yet intriguing task with numerous applications in fields such as human-computer interaction, sentiment analysis, and mental health monitoring.

## Introduction
The ability to accurately detect emotions from audio data opens up a wide range of possibilities in understanding human behavior and improving human-computer interaction. This project leverages machine learning algorithms to classify audio samples into different emotional categories such as happy, sad, angry, etc.

## Installation
To run this project, ensure you have Python installed on your system along with the necessary dependencies. You can install the required packages using pip. You need to first check the "requirements.txt" file in the repository.

## Usage
Data Preparation: Ensure your audio data is properly labeled with corresponding emotion labels.
Feature Extraction: Extract relevant features from the audio data. This includes MFCCs, chroma, spectrograms.
Model Training and Prediction: Train a machine learning model using the extracted features and emotion labels. Also use the same trained model to predict the features.

## Libraries and Dataset Used
This project makes use of the following Python libraries:
  Librosa: For audio feature extraction.
  Soundfile: For reading the data in "wav" file
  Scikit-learn: For machine learning algorithms and evaluation metrics.
  NumPy: For better handling of numerical arrays.
  os and glob: For handling the file in the disk storage.
  Dataset: The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) contains speech data labeled with various emotions.
 
## Training the Model
An Machine Learning MPL classifier model is trained on the splitted dataset and then used to predict the features of the training set.
