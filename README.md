## Neural_Networks
The provided code comprises two distinct machine learning projects, each with its own purpose and dataset

## Basic Fashion MNIST Classification

This part of the code focuses on image classification using TensorFlow and Keras. It leverages the Fashion MNIST dataset, which contains grayscale images of various fashion items.

The dataset is loaded and split into training and testing sets.

Data normalization is performed by scaling pixel values between 0 and 1.

A neural network model is defined, consisting of input flattening, a dense hidden layer with ReLU activation, and an output layer with softmax activation for multi-class classification.

The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss.

Training is executed for five epochs on the training data.

Predictions are generated for the test data, and for the first six predictions, both the actual and predicted labels are displayed alongside their respective images.

## IMDb Movie Review Sentiment Analysis(text classification)

This section of the code deals with sentiment analysis of IMDb movie reviews using TensorFlow and Keras.

The IMDb dataset is loaded, containing movie reviews labeled as either positive or negative sentiment.

Text preprocessing is conducted, including padding sequences to a maximum length of 250 words.

A neural network model is constructed, comprising an embedding layer, a global average pooling layer, and dense layers for binary sentiment classification (positive/negative).

The model is compiled with the Adam optimizer and binary cross-entropy loss.

Training is carried out for 40 epochs, with validation data utilized for monitoring model performance.

After training, the model is saved as "model.h5."

An example is provided for using the saved model to predict sentiment for text from an external file ("test.txt").
