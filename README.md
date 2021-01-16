# Speech2Text
The Speech2Text project converts an audio file into text using deep learning. The model is built from scratch using tensorflow framework wrapped with keras.  

The data used is publicly available and is downloaded from Kaggle - https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data

The steps followed are as follows:
- Importing the necessary libraries
- Data Exploration
- Data Preprocessing
- Train and Validation dataset preparation
- Building Model from scratch
- Model Training
- Predictions on Validation dataset
- Predictions on Test data

The created model is saved in "model" directory by the name of "speech2text.hdf5".
The accuracies achieved on training the model for 30 epochs are:
- Train Accuracy : 86.77%
- Test Accuracy : 79.84%

*Accuracies can be improvised by training the model for more number of epochs on a GPU.
