# QMIST-data-classification
The QMNIST dataset contains 70,000 grayscale images of handwritten digits, each 28 by 28 pixels in size. The dataset is used for training and evaluating neural networks for digit recognition tasks.

Image Representation: The images are represented as 28x28 arrays, with pixel values ranging from 0 to 255, where 0 represents the background (black) and 255 represents the foreground (white). Labels: Each image is associated with a label, which is an integer between 0 and 9, representing the corresponding digit.

Label Mapping:

Label 0 1 2 3 4 5 6 7 8 9

Digit 0 1 2 3 4 5 6 7 8 9

The dataset is split into two parts:

Training Set: Contains 60,000 images used to train the model (train_images and train_labels). Test Set: Contains 10,000 images used to evaluate the model's performance (test_images and test_labels). In the tutorial, a neural network is trained on this dataset to classify the images, which are normalized for better training performance. The model is designed to learn patterns from the training set and generalize them for accurate classification of unseen images from the test set.
