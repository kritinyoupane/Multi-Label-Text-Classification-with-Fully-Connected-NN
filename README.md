# Multi-Label-Text-Classification-with-Fully-Connected-NN

# Data-preprocess
For preprocessing the data, the code is present in google colab. One can use any one of the following method to clean the data 
1) Cleaning Using Regular Expression
2) Stemming 

The programmer can either run the code for cleaning the dataset or run the code to import the clean dataset directly from drive. The second option is recommended as it will save the time.

# Vectorize the dataset
It converts the given sequence of text into vectors. Word vectorization is a map words from vocabulary to a corresponding vector of real numbers which is used to find word predictions, word similarities/semantics. We have used **TFIDF** vectorizer.

# Balancing the dataset
The dataset is highly imbalance. So, we have used **SMOTE** (Synthetic Minority Over-sampling Technique) for minority class and **RandomUnderSampler** for majority class to balance the dataset.

# Label Encoding and One Hot Encoding
Label Encoding is used to represent the labels in numeric form. But, the number of labels in train dataset and validation dataset isn't equal. So, one hot encoding is used to ensure the uniformity in the shape of target classes.

# Training Fully Connected Neural Network 
Train the neural network from the colab code or directly import it from the model subdirectory in the drive link.

# Making the Predictions
One can make the prediction and calculate f1 score on either validation or test dataset running the function **predictions_f1score**.

#Team Info
Kriti Nyoupane - kritineupane544@gmail.com
Gaurav Jyakhwa - gjyakhwa1@gmail.com
