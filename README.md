# Digit-Classification
This notebook was written entirely in Google Colab, and as such is meant to run on a cloud-based instance of Python. 

This project is an exploration of Convolutional Neural Networks (CNNs) as a means of classifying spoken digits, pulled from Jakobovski's free-spoken-digit-dataset (https://github.com/Jakobovski). 

This was only meant as a way of exploring the developement of data for, and implementation of, a Convolutional Neural Network. WAV files are converted to Mel-spectrograms, which are visual representations of sound data. The CNN is then trained on these images and attempts to classify other spectrograms into particular classes 0-9. Accuracy achieved without image normalization is 55%. 

At some point in the future,the code will get cleaned up. It's quite messy, as is. 
