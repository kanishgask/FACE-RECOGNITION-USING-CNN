# FACE-RECOGNITION-USING-CNN
Face Recognition using CNN
**Overview**
This project implements a Convolutional Neural Network (CNN) to perform face recognition by classifying human faces from images. The model is trained on labeled face datasets, learns to distinguish different individuals, and can predict the identity of faces in new images.

**Features**
Loads labeled face image datasets organized by person/class

Splits data into training and validation sets

Builds a CNN architecture with convolutional, pooling, and dense layers

Compiles and trains the model with validation

Evaluates model performance using accuracy and loss metrics

Visualizes training history with accuracy and loss plots

Saves the trained model for future inference

Includes a utility function for predicting face identity on new images

Getting Started
**Prerequisites**
Python 3.7+

TensorFlow 2.x

Matplotlib

(Optional) Jupyter Notebook or any Python IDE

Install required packages with:

bash
Copy
Edit
pip install tensorflow matplotlib
Dataset Preparation
Prepare your dataset in the following folder structure:

python-repl
Copy
Edit
faces_dataset/
├── person1/
│   ├── image1.jpg
│   ├── image2.jpg
├── person2/
│   ├── image1.jpg
│   ├── image2.jpg
...
Each folder represents one person/class and contains their face images.

**Usage**
Update the dataset_path variable in the script to point to your dataset folder.

Adjust the img_size and num_classes parameters if needed.

Run the training script to train and validate the CNN model.

Visualize the accuracy and loss graphs to check training progress.

Save the trained model to disk for later use.

Use the provided predict_face function to classify new face images.

**Example**
python
Copy
Edit
predict_face('path_to_image.jpg')
This will output the predicted person's name and confidence score.

Dataset Sources
You can use popular face datasets such as:

Labeled Faces in the Wild (LFW)

CelebA Dataset

VGGFace2 Dataset

Or create your own dataset following the folder structure above.
**OUTPUT:**
![image](https://github.com/user-attachments/assets/6eead9da-71a2-48c6-8b88-2c7c5943d5d2)
![image](https://github.com/user-attachments/assets/d1eac51a-63ef-4615-b214-05a2054dc39c)


