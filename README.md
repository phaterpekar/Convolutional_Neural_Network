# Convolutional_Neural_Network
Built a Convolutional Neural Network (CNN) utilizing Keras on top of Tensorflow to build an Image  Classification workflow.

Key steps taken:
- Pre-processing the data to bring it to a valid format to feed into the pipeline.
- Used a Sequential model utilizing Convolution, Maxpooling & Dropout layers.
- Split the data into training, validation & test sets. Fit the model on the training data. 
- Evaluate how the training loss & validation loss interact as number of epochs (training time) increases.
- Utilized the best parameters that reduced the validation loss using the callbacks module from Keras.
- Predicted on the test set & checked the classification reports, confusion matrix(cross-tabulation) to understand where the                 misclassifications occur. 
- Visually see the correct & misclassified images.
