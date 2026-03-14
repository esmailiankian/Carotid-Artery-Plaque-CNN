# Carotid-Artery-Plaque-CNN
Deep learning classification of carotid plaque from ultrasound images

To run this code, please download the dataset from https://www.kaggle.com/datasets/pahunichoudhary/carotid-artery-ultrasound-and-color-doppler?resource=download and place it in the /data folder.

This project uses the "Carotid Artery Ultrasound and Color Doppler" dataset by Pahuni Choudhary and Apollo Sage Hospital, available on Kaggle.

# Carotid Artery Plaque Classification
This project uses a Deep Learning (CNN) approach to detect the presence of plaque in B-mode ultrasound images.

## Data Source
The dataset is the "Carotid Artery Ultrasound and Color Doppler" dataset available on [Kaggle](https://www.kaggle.com/datasets/pahunichoudhary/carotid-artery-ultrasound-and-color-doppler).

## Methodology
- **Architecture**: 3-layer Convolutional Neural Network (CNN) built with TensorFlow/Keras.
- **Preprocessing**: Images resized to 224x224, converted to grayscale, and normalized (0-1).
- **Optimization**: Adam optimizer with Binary Crossentropy loss.

## Results
- **Training Accuracy**: 100%
- **Test Accuracy**: 78.57%
- **Observations**: Significant overfitting was observed due to small sample size (n=18 patients), suggesting a need for data augmentation in future iterations.
