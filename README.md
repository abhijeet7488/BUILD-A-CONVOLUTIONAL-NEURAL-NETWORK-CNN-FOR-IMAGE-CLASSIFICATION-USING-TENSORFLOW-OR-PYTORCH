# BUILD-A-CONVOLUTIONAL-NEURAL-NETWORK-CNN-FOR-IMAGE-CLASSIFICATION-USING-TENSORFLOW-OR-PYTORCH
COMPANY: CODTECH IT SOLUTIONS
NAME: ABHIJEET KUMAR
INTERN ID: CTO4DG2125
DOMAIN: MACHINE LEARNING
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH
DESCRIPTION :
The goal of this task is to build a Convolutional Neural Network (CNN) using TensorFlow (or PyTorch) that can classify images into categories. 
I have used the CIFAR-10 dataset, which includes small 32x32 pixel color images of real-world objects like dogs, ships, and airplanes.
Step 1: Import Required Libraries
 importing TensorFlow and other useful libraries like matplotlib for plotting, and NumPy for data manipulation.
Step 2: Load and Explore the CIFAR-10 Dataset
TensorFlow provides the CIFAR-10 dataset built-in, so it’s easy to load and split into training and test sets.
then normalize the pixel values to range between 0 and 1 by dividing by 255, which helps speed up model training.
 Step 3: Visualize the Images
I use matplotlib to see a few sample images and confirm that the data looks correct.
 Step 4: Build the CNN Model
Then, I stack layers using Keras' Sequential API. 
A CNN typically includes: 
1.Conv2D: learns features from image patches.
2.MaxPooling2D: reduces image size.
3.Flatten + Dense: turns features into predictions.
Step 5: Compile the Model
I choose the optimizer, loss function, and evaluation metric. Categorical crossentropy is used for multiclass classification.
Step 6: Train the Model
Then, I train the model using training data for several epochs or cycles.
Step 7: Evaluate the Model
Evaluate the Model how well the model performs on the unseen test data.
Step 8: Make Predictions and Plot Confusion Matrix
I predict classes and evaluate performance using a confusion matrix to see which classes are confused with each other.
