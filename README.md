# Ragas-JohnMark_LW1_Image_Classification.ipynb
## Google Colab Link here: https://colab.research.google.com/drive/1yD8OgnX2z9umcPORjQb2kEvL-kMZ9D_b?usp=drive_link

Questions: (February 8, 2026)
What is the Fashion MNIST dataset? ANS is a public image dataset that’s commonly used to train and benchmark machine-learning models especially for image classification
Why do we normalize image pixel values before training? ANS To make training faster and more stable by keeping input values on a similar scale which helps the model learn more effectively and converge properly
List the layers used in the neural network and their functions.
**Input layer** Takes the 28×28 grayscale image (pixel values)., **Convolutional layer** (Conv2D), Extracts local features like edges, textures, and shapes using filters., **Activation layer (ReLU)** Adds non-linearity so the network can learn complex patterns., **Pooling layer (MaxPooling)** Reduces spatial size, keeps important features, and lowers computation., **Flatten layer** Converts the 2D feature maps into a 1D vector., **Fully connected (Dense) layer** Learns high-level combinations of features for classification., **Output layer (Dense + Softmax)** Produces probabilities for each of the 10 clothing classes.

What does an epoch mean in model training? ANS is one complete pass through the entire training dataset during model training
Compare the predicted label and actual label for the first test image. ANS The predicted label and the actual label are the same
What could be done to improve the model’s accuracy? ANS Add more convolutional layers or filters Train for more epochs Use regularization Tune hyperparameters Use data augmentation Increase model capacity
