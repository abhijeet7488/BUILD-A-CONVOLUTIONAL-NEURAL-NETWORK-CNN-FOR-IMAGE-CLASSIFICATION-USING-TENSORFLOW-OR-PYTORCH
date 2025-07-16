# BUILD-A-CONVOLUTIONAL-NEURAL-NETWORK-CNN-FOR-IMAGE-CLASSIFICATION-USING-TENSORFLOW-OR-PYTORCH
COMPANY: CODTECH IT SOLUTIONS
NAME: ABHIJEET KUMAR
INTERN ID: CTO4DG2125
DOMAIN: MACHINE LEARNING
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH
DESCRIPTION :
In this task, I build a Convolutional Neural Network (CNN) using TensorFlow to classify images of clothing items from the Fashion MNIST dataset. 
CNNs are deep learning models designed specifically for image processing — 
they can automatically learn spatial features such as edges, shapes, and textures that help in classifying images accurately.
The Fashion MNIST dataset contains 70,000 grayscale images (60,000 for training and 10,000 for testing), 
each of size 28x28 pixels, across 10 categories such as t-shirts, shoes, bags, etc. Each image is labeled with a class ranging from 0 to 9.

Step 1: Import Required Libraries
First, I import necessary Python libraries

Step 2: Load the Dataset
The Fashion MNIST dataset is available directly in TensorFlow. I Just load and split it into training and testing data.

 Step 3: Preprocess the Data
Before feeding images to the model:
Normalize pixel values (from 0-255 to 0-1)
Reshape images to include a channel dimension (28, 28, 1)

 Step 4:: Define the CNN Model
I build a CNN using Sequential() with layers:
Conv2D: Applies convolution filters (It learns features from image patches)
MaxPooling2D: Reduces spatial size (It reduces image size)
Flatten: Converts 2D into 1D (turns features into predictions)
Dense: Fully connected layers for prediction.  (It also turns features into predictions).

Step 5: Compile the Model
Then, I compile the model with:
loss: sparse_categorical_crossentropy (for multi-class)
optimizer: adam (adaptive learning)
metrics: For accuracy

Step 6: Train the Model
Then, I train the model using the training data for a few epochs.

Step 7: Make Predictions
Then, I use the trained model to predict new images.

Step 8: Visualize Some Predictions
Plot images along with their actual and predicted labels.

OUTPUT:
<img width="1222" height="822" alt="Image" src="https://github.com/user-attachments/assets/2b462d6f-3353-4965-ac65-872ea809af18" />

