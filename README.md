# Image Classification
This repository provides an implementation of image classification using convolutional neural network that adapts and optimizes the pre-trained VGG16 model using the transfer learning
technique. The model is capable of classifying images of animals into following four classes:

Dogs

Cats

Monkeys

Cows


# Dependencies
Languages - Python

Frameworks - Matplotlib, Scikit-learn, Numpy, TensorFlow, Keras

Additional environments - Jupyter Notebook


# Train, test and save the model
Run 'ImageClassification.ipynb' with Jupyter Notebook. Model file containing the architecture, weights and training configuration is saved as 'trained_model.h5' in the root folder.
I have provided a sample dataset in the 'cats-dogs-monkeys-cows' folder for reference. You may add your own images or modify the dataset altogether. Make sure you take care of the configured paths.


# Result
Results of training and testing the model on the sample dataset are as follows:

Accuracy on Training-Set: 1.0000

Loss on Training-Set: 0.2347

Accuracy on Validation-Set: 1.0000

Loss on Validation-Set: 0.1593

Confusion matrix is generated upon execution of 'ImageClassification.ipynb' with Jupyter Notebook.