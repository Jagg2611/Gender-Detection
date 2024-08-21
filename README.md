**Gender Detection Using CNN**

This project implements a Convolutional Neural Network (CNN) model to accurately detect gender from images. The model is trained on a dataset of facial images using OpenCV for webcam integration and face detection.

**Project Overview**

Dataset: https://drive.google.com/drive/folders/18n8xW9alNCqVkkLjEgoegDn2RM55KdTi?usp=drive_link
Dataset Size: 2,907 images (1,528 male, 1,379 female)
Model: Convolutional Neural Network (CNN)
Framework: TensorFlow/Keras
Training Epochs: 200

**Setup and Installation**

-Clone the Repository
`git clone https://github.com/yourusername/gender-detection.git
cd gender-detection`

-Install Required Libraries
`pip install -r requirements.txt`

-Download Dataset
The dataset should be organized with two main folders: one for male images and another for female images.
Male images should be located in: gender_dataset_face/man
Female images should be located in: gender_dataset_face/woman

**Model Performance**
After training, the training and validation loss and accuracy metrics will be visualized in the generated plot (plot.png).
