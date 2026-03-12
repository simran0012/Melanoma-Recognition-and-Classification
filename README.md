Skin Cancer Detection using CNN

A deep learning based skin cancer classification system built using TensorFlow and Keras.
The model uses a Convolutional Neural Network (CNN) to classify dermoscopic skin images into 9 different types of skin lesions.

This project helps demonstrate how deep learning can assist in early skin cancer detection.

Dataset used: ISIC Skin Cancer Dataset

Technologies Used:
-Python
-TensorFlow
-Keras
-NumPy
-Pandas
-Matplotlib
-Seaborn
-Augmentor
-Google Colab

Model Architecture:
The CNN model contains:
1. Image Rescaling Layer
2. Multiple Convolutional Layers
3. Max Pooling Layers
4. Dropout Layers (to prevent overfitting)
5. Fully Connected Dense Layers
6. Softmax Output Layer

Data Augmentation:
To improve model generalization and solve class imbalance, augmentation techniques were applied:
1. Random Rotation
2. Horizontal and Vertical Flip
3. Zoom
4. Translation
5. Image rotation using Augmentor

Training

Model training parameters:
Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Epochs: 30
Batch Size: 32
Image Size: 180 × 180
Training included validation monitoring to reduce overfitting.

After improving the model and balancing the dataset:
Overfitting was significantly reduced.
Validation accuracy improved.
The model correctly predicted test images.

<img width="791" height="613" alt="image" src="https://github.com/user-attachments/assets/56ce0b9c-f4ba-4a9a-9b33-a805dd3c88bf" />
