# CNN-on-CIFAR-10
Using the CIFAR-10 dataset, a Convolutional Neural Network of 3 convolutional layers and 2 fully connected layers is implemented and evaluated.

## Dataset
The CIFAR-10 dataset is a collection of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 testing images. The classes are:


![cat6](https://user-images.githubusercontent.com/116349435/232276654-15e5bcf3-60f3-4760-9559-26af163c38e7.png)

## Model Architecture
### The CNN model used here has:

* Convolutional layer with 32 filters, kernel size of 3x3, and ReLU activation function
* MaxPooling layer with pool size of 2x2
* Convolutional layer with 64 filters, kernel size of 3x3, and ReLU activation function
* MaxPooling layer with pool size of 2x2
* Convolutional layer with 128 filters, kernel size of 3x3, and ReLU activation function
* MaxPooling layer with pool size of 2x2
* Flatten layer to convert 3D feature maps to 1D feature vectors
* Dense layer with 200 neurons and ReLU activation function
* Output Dense layer with 10 neurons (one for each class) and Softmax activation function
* The model was trained using the Adam optimizer and categorical crossentropy loss function 
