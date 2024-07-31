## README

### Title: English to French - Neural Machine Translation with RNN Models

This Jupyter Notebook provides a comprehensive walkthrough for developing and evaluating various Recurrent Neural Network (RNN) models for the task of English to French neural machine translation. Below is an outline of the notebook's flow and its primary components.

### 1. Natural Language Processing Nanodegree - Project 2
### 2. Dataset
Details about the dataset used for training and testing the translation models. The dataset consists of English to French sentence pairs.

### 3. Files
Lists the files involved in the project, including datasets and any additional resources necessary for running the notebook.

### 4. Data Preprocessing
Discusses initial preprocessing steps already performed on the dataset, such as punctuation delimitation and text normalization to lowercase. Highlights the need for further preprocessing.

### 5. Dataset Statistics
Provides a brief statistical overview of the dataset, noting unique and total word counts.

### 6. Padding (IMPLEMENTATION)
Implementation details for padding sequences to ensure uniform input lengths for the neural network models.

### 7. Preprocess Pipeline
Outlines the preprocessing pipeline, preparing the data for training by tokenizing and converting text to sequences.

### 8. Models
Introduction to different neural network models to be implemented for the translation task.

### 9. Model 1: RNN (IMPLEMENTATION)
Step-by-step implementation of a simple RNN model for translation.

### 10. Model 2: Embedding (IMPLEMENTATION)
Implementation of an RNN model with word embedding layers to improve translation quality.

### 11. Model 3: Bidirectional RNNs (IMPLEMENTATION)
Implementation of a bidirectional RNN model to capture context from both directions of the input sequence.

### 12. Model 4: Encoder-Decoder (IMPLEMENTATION)
Implementation of an Encoder-Decoder architecture, a foundational model for sequence-to-sequence tasks like translation.

### 13. Model 5: Custom (IMPLEMENTATION)
Implementation of a custom neural network model that combines various advanced techniques for potentially improved performance.

### 14. Prediction (IMPLEMENTATION)
Code for generating translations using the trained models and evaluating their performance.

### Additional Information

The code was run in the Udacity workspace since the exact environment was not reproducible, and there was no Docker-related information from Udacity for this project.

However, I have included the pip freeze output in the requirements.txt file to indicate the versions that were used.

Check the 'machine_translation.ipynb' file for detailed code.

For more information, please refer to the provided README from [Udacity](./README_Udacity.md).