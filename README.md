## CIFAR-10-Classification
##### Developed a simple Artificial Neural Network and a Convolutional Neural Network for CIFAR 10 dataset. 
##### Confusion Matrix, Heatmap and Classification Report is used for performance evaluation with performance metrics for training used is Accuracy. 
#### The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
#### The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.
#### Here are the classes in the dataset, as well as 10 random images from each:
1. airplane										
2. automobile										
3. bird										
4. cat										
5. deer										
6. dog										
7. frog										
8. horse										
9. ship										
10. truck

## How to use model:

- Importing libraries: Import necessary libraries such as:-
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn
  * Tensorflow
  * Keras
  * Warnings
  * Models, datasets, layers

- Loading Data: Then load the data using the already present cifar10 dataset in tensorflow. Use the syntax => datasets.cifar10.load_data()

- Training the model: You can train the model using either traditional Artificial Neural Network or using Convolutional Neural Network. Add the required loss and activation functions, performance metrics along with the optimizers and you can also apply any regularization technique such as Drop regularization if required.

- Testing model: Test the model using unseen data and calculate the testing accuracy.

- Validating model: Validate or evaluate you model using a Confusion Matrix or Heatmap and calculate the accuracy, precision, recall, F1-Score, etc, according to your necessity. 

