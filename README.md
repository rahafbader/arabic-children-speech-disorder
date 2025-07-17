# Arabic Speech Disorder Detection Using CNN-RNN

This project aims to detect speech disorders in Arabic-speaking children using deep learning. It introduces and compares two deep learning models based on a hybrid architecture of Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN), including both LSTM and Bidirectional LSTM layers.

The goal is to support early intervention by providing a fast, objective, and automated tool to classify Arabic speech samples as either **normal** or **disordered**.

##  Project Overview

Traditional diagnosis of speech disorders relies on human judgment, which can be time-consuming and subjective. Our system uses audio signal processing and deep learning to automatically analyze Arabic speech and detect potential pronunciation issues in children.

### Key Features
- Arabic speech dataset preprocessing using `librosa`
- MFCC (Mel-Frequency Cepstral Coefficients) feature extraction
- CNN layers for spectral feature learning
- LSTM and Bidirectional LSTM layers for temporal pattern detection
- Achieved **~85%** accuracy on test data
- Built with TensorFlow and Keras
