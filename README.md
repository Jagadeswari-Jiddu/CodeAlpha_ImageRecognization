# CodeAlpha_ImageRecognization
Image recognition, also known as image classification, is a computer vision task that involves the automatic identification and labeling of objects, scenes, or patterns within digital images. The goal is to enable machines to understand and interpret visual information similar to the way humans do.

Data Collection: Gather a large dataset of images labeled with the objects or features you want the model to recognize. For example, if you're building a model to recognize cats and dogs, you'll need lots of images of cats and dogs labeled accordingly.
(For this I used mnist,fashion_mnist,cifar_10 datasets from keras, lfw dataset from sklearn)

MNIST Dataset for recognizing  digits.

Fashion_mnist dataset for recognizing clothing items.

cifar_10 dataset for recognizing objects.

lfw dataset for recognizing labeled faces .

Preprocessing: Prepare the images for training by resizing them to a uniform size, normalizing pixel values, and possibly augmenting the data by applying transformations like rotation, flipping, or cropping to increase the diversity of the dataset.
(by using reshape function input(3d) is reshaped into 2d input and image transformatiion is also applied to the input)

Model Selection: Choose an appropriate machine learning model architecture for your task. Support Vector Classification, Random Forest Classified are used for image recognition due to their ability to effectively capture spatial hierarchies in images.

Training: Train the selected model on the labeled dataset. During training, the model learns to associate patterns in the images with their corresponding labels through a process of forward and backward propagation of errors.

Evaluation: Evaluate the trained model's performance on a separate validation dataset (Test data) to assess its accuracy, precision, recall, and other relevant metrics.
(In this I generated a classification Report for model evaluation)
Data Visualisation: Here I plotted test images vs predicted images using matplotlib.pyplot library by the function called imshow()
