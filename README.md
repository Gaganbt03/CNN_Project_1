````markdown
# Image Classification using Convolutional Neural Network

A deep learning project that uses a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset using TensorFlow and Keras.

## Project Overview

This project demonstrates the implementation of a CNN-based image classification model. The workflow includes loading the CIFAR-10 dataset, preprocessing the images, preparing training and validation data, building the CNN architecture, training the model, and evaluating its performance on unseen test data.

## Objectives

- Build a CNN-based image classification model.
- Preprocess image data for deep learning.
- Design and train a convolutional neural network.
- Use validation data during model training.
- Evaluate the trained model using test data.
- Analyze the classification performance.

## Dataset

The project uses the CIFAR-10 dataset.

CIFAR-10 contains:

- 50,000 training images
- 10,000 test images
- 10 image classes
- RGB images of size 32 × 32 pixels

## Classes

The CIFAR-10 dataset contains the following classes:

| Class ID | Class |
|----------|-------|
| 0 | Airplane |
| 1 | Automobile |
| 2 | Bird |
| 3 | Cat |
| 4 | Deer |
| 5 | Dog |
| 6 | Frog |
| 7 | Horse |
| 8 | Ship |
| 9 | Truck |

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Model Architecture

The project uses a Convolutional Neural Network designed for image classification.

The model includes:

- Convolutional layers
- Max-pooling layers
- Flatten layer
- Dense layers
- Dropout

The convolutional layers extract visual features from the input images, while the dense layers perform the final classification.

## Data Preprocessing

The dataset is loaded using the Keras CIFAR-10 dataset utilities.

The preprocessing workflow includes:

1. Loading the CIFAR-10 training and testing datasets.
2. Preparing the input images.
3. Preparing the class labels.
4. Splitting the training data into training and validation sets.
5. Feeding the processed data into the CNN model.

## Model Training

The model is compiled using:

- Loss function: Categorical Crossentropy
- Optimizer: RMSprop
- Metric: Accuracy
- Batch size: 32
- Epochs: 10

Validation data is used during training to monitor the model's performance.

## Evaluation

After training, the model is evaluated using the CIFAR-10 test dataset.

The notebook reports a test accuracy of:

**67.52%**

## Project Workflow

```text
CIFAR-10 Dataset
       ↓
Data Loading
       ↓
Data Preprocessing
       ↓
Training / Validation Split
       ↓
CNN Architecture
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Test Accuracy
````

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Gaganbt03/CNN_Project_1.git
cd CNN_Project_1
```

### 2. Install Dependencies

```bash
pip install tensorflow numpy matplotlib
```

### 3. Open the Notebook

Open:

```text
CNN_CIFAR10_Classification.ipynb
```

using Google Colab or Jupyter Notebook.

### 4. Run the Notebook

Run the notebook cells sequentially to:

1. Load the CIFAR-10 dataset.
2. Prepare the training and validation data.
3. Build the CNN model.
4. Compile the model.
5. Train the model.
6. Evaluate the model on the test dataset.

## Results

The CNN model achieved:

**Test Accuracy: 67.52%**

The result demonstrates that the model was able to learn visual patterns from the CIFAR-10 dataset and classify images into their corresponding categories.

## Applications

CNN-based image classification can be used in:

* Image recognition
* Computer vision systems
* Automated visual inspection
* Object classification
* Smart camera applications
* Image-based analysis

## Future Improvements

* Train the model for more epochs.
* Apply data augmentation.
* Experiment with deeper CNN architectures.
* Perform hyperparameter tuning.
* Use batch normalization.
* Apply transfer learning using pretrained models.
* Improve classification accuracy.

## Author

**Gagan B T**

BE – Computer Science and Engineering
Atria Institute of Technology, Bengaluru

GitHub: https://github.com/Gaganbt03

```
```
