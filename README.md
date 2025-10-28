# Team-09
Tennis Game Analysis Assignments
Task 02:
1) I imported the Fashion-MNIST dataset using the load_dataset("fashion_mnist") function from the datasets library
2) The dataset which was already splitted into train and test ,the i reshaped the training and test images into (28, 28, 1) format to match CNN input requirements and normalized the pixel values by dividing them by 255
3) Then the labels were converted into one-hot encoded vectors using to_categorical() for multi-class classification
4) Then i created sequential CNN model which has 2 convolutional layers(Conv2D) used for feature ectraction, 2 polling layers(MaxPooling2D) used to reduce spatial dimensions, flatten layer to convert features into single vector and dense layers with ReLU and Softmax activations for classification
5) I trained it for the given train dataset. After training, the model was evaluated on the test dataset to measure its final accuracy
6) Finally, I selected a sample test image and used the trained model to predict its clothing category,using matplotlib i displayed the test image alongside the predicted label
