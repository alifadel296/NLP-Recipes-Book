# Spam Email Classification with Deep Learning

## Project Description
This Jupyter notebook demonstrates the implementation of four deep learning models for classifying emails as "spam" or "not spam" (ham). The models include a 1-D Convolutional Neural Network (CNN), a Simple RNN, an LSTM, and a Bidirectional LSTM. The project leverages NLP techniques for text preprocessing and TensorFlow/Keras for model building and training.

## Key Features
- **Text Preprocessing**:  
  - Removal of stopwords, special characters, and lowercase conversion.  
  - Tokenization and padding of sequences for model input.  
- **Deep Learning Models**:  
  - **1-D CNN**: Utilizes convolutional layers for feature extraction.  
  - **Simple RNN**: Basic recurrent neural network implementation.  
  - **LSTM**: Long Short-Term Memory network for sequence modeling.  
  - **Bidirectional LSTM**: Enhances LSTM by processing sequences in both directions.  
- **GPU Acceleration**: Training optimized with TensorFlow GPU support.  
- **Evaluation**: Classification reports (precision, recall, F1-score) for each model.

## Dataset
**To download the dataset you use this link** :
-   ### https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset#spam.csv
## Note
- **I used google colab with T4 GPU to run this notebook**