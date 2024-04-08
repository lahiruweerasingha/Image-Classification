# Cats and Dogs Images Classification with CNN

This project involves building a Convolutional Neural Network (CNN) to classify images of cats and dogs. Below is the technical stack and an overview of the project:

## Technical Stack

- **Programming Language**: Python
- **Libraries**:
  - TensorFlow: For building and training the CNN model
  - Matplotlib: For data visualization
  - OpenCV: For image processing tasks
  - OpenDatasets: For downloading datasets directly from Kaggle
- **Model Architecture**: Convolutional Neural Network (CNN)
- **Data Preprocessing Techniques**:
  - Data Augmentation: Randomly flipping, rotating, and zooming images to increase dataset diversity
  - Scaling: Normalizing pixel values of images to the range [0, 1]
- **Evaluation Metrics**:
  - Loss Function: Binary Crossentropy
  - Metrics: Accuracy, Precision, Recall

## Project Overview

1. **Data Acquisition and Preprocessing**:
   - The dataset is downloaded using the OpenDatasets library from Kaggle, containing images of cats and dogs for classification.
   - Data is split into training, validation, and test sets.
   - Image resizing and batching are performed.

2. **Exploratory Data Analysis**:
   - Sample images are visualized along with their respective labels (cats or dogs).

3. **Data Augmentation and Scaling**:
   - Images are augmented using techniques like flipping, rotating, and zooming to improve model generalization.
   - Pixel values are scaled to the range [0, 1].

4. **Model Building**:
   - A sequential model is constructed using TensorFlow's Keras API.
   - Convolutional layers are added with max-pooling for feature extraction.
   - Dropout and batch normalization are used for regularization.
   - Dense layers are employed for classification.

5. **Model Training**:
   - The model is trained on the training data with specified epochs.
   - Training progress is monitored using validation data.

6. **Model Evaluation**:
   - Model performance is evaluated on the test set using metrics like accuracy, precision, and recall.
   - Sample image prediction is demonstrated.

7. **Results Visualization**:
   - Training and validation loss, as well as accuracy, are plotted over epochs.
