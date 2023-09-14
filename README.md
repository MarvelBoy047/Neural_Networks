### Neural_Networks
The provided code comprises two distinct machine learning projects, each with its own purpose and dataset
# # Fashion MNIST Classification: Classifying Fashion with Neural Networks

In the first part of our code, we embark on a journey into the realm of fashion with the Fashion MNIST dataset. Our mission is to classify fashion items with precision. Here's a detailed breakdown of what we achieved:

Data Preparation: We loaded the Fashion MNIST dataset and split it into training and testing sets. To ensure uniformity, we scaled pixel values to fall within the range of 0 to 1.

Model Creation: Our neural network model consists of layers for flattening, dense hidden units with ReLU activation, and an output layer using softmax activation. This architecture is designed for multi-class classification.

Training and Evaluation: The model was trained for five epochs using the training data. The Adam optimizer and sparse categorical cross-entropy loss function were employed. The result was an accurately trained model.

Prediction Showcase: To demonstrate the model's capabilities, we made predictions on test data. The first six predictions were showcased, complete with both actual and predicted labels, providing a visual representation of the model's accuracy.

# # IMDb Movie Review Sentiment Analysis: Deciphering Movie Emotions

In the second part of our code, we dive into the world of IMDb movie reviews, aiming to unravel the sentiments hidden within text data. Our journey through this sentiment analysis task includes the following:

Data Loading and Preprocessing: We loaded the IMDb dataset, which contains movie reviews categorized as positive or negative sentiment. Extensive text preprocessing was undertaken, including padding sequences to a consistent length of 250 words.

Model Architecture: Our neural network model comprises an embedding layer, global average pooling, and dense layers for binary sentiment classification. This architecture equips the model to distinguish between positive and negative sentiments in movie reviews.

Training and Evaluation: The model underwent rigorous training for 40 epochs using a subset of the data for validation. We used the Adam optimizer and binary cross-entropy loss function. The model demonstrated remarkable accuracy.

Saving the Model: After successful training, we saved the model as "model.h5" for future use.

External Text Prediction: As a bonus, we showcased how the model can be loaded and applied to predict sentiment for text from an external file ("test.txt"). This feature extends the model's usability beyond the code itself.

Both projects exemplify the power of machine learning in diverse domains, showcasing the effectiveness of neural networks in classifying fashion items and deciphering sentiment in movie reviews.
