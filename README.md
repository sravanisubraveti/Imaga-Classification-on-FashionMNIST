# Image Classification for FashionMNIST data set
To perform the classification of Fashion MNIST dataset we use basic Machine Learning Al-gorithms.  The Feature extraction and Classification algorithms helps us classify large data.Feature extraction is an important step to deal with large data set, by reducing the largenumber of variables to more manageable groups for computing purposes.In this assignment we are using Feature extraction methods like PCA, LDA methods to re-duce the dimensions of the large dataset which has 784 columns in both train and test dataset.  After applying the dimentionality reduction techniques we are applying classical clas-sification techniques to the reduced data set obtained.  We are using classical methods likeSupport Vector Machine (SVM), Random Forest(RF), Gradient Boosting Classifier (GBC).

Applied CNN, ResNet models to the FashionMNIST dataset
The below are the list of models we tried out and determined the accuracy:
1. CNN with one convolutional layer.
2. CNN with two convolutional layers.
3. CNN with three convolutional layers.
4. ResNet (Residual Neural networks).
After loading the data, we scaled the data so that all the values are in [0,1] interval. Now
the training data is splitted into training and validation data, further pre-processed them by
reshaping them into the shape the network expects.
