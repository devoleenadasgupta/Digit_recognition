# Digit_recognition
This project focuses on digit recognition using deep learning, utilizing the MNIST dataset, which contains handwritten digits from 0 to 9. The dataset is first loaded and preprocessed, where pixel values are normalized to a scale of 0 to 1, and labels are converted into one-hot encoding for classification. A few sample images are visualized to gain insights into the dataset.
Two neural network models are built using Keras' Sequential API.
Model 1: This model consists of a Flatten layer to convert 28x28 images into a 1D array, followed by two Dense layers with 128 and 64 neurons, using the ReLU activation function. The final layer uses softmax activation to classify the digits into ten categories.
Model 2: This model also starts with a Flatten layer to convert the 28x28 images into 1D. It includes Dense layers with 128 and 64 neurons, using ReLU activation. Between the Dense layers, Dropout layers are added with a 30% dropout rate to reduce overfitting. The final layer uses softmax activation for classification into ten categories.
After training, the model's performance is evaluated on a test dataset using accuracy and loss metrics.
