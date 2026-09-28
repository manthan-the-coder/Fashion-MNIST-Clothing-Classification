# Fashion-MNIST-Clothing-Classification
Clothing image classification using TensorFlow and Fashion-MNIST

## About the Project

This project is a Machine Learning image classification project built using **TensorFlow and Keras**.

The model is trained on the **Fashion-MNIST dataset** to classify images of clothing and footwear into 10 different categories.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Machine Learning
* Neural Networks

## Dataset

The project uses the Fashion-MNIST dataset provided through Keras.

The dataset contains grayscale images of clothing items with 10 classes:

* T-shirt/top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle boot

## Model Architecture

The neural network consists of:

```text
Input Image (28 × 28)
        ↓
Flatten
        ↓
Dense Layer (128 neurons, ReLU)
        ↓
Dense Layer (10 neurons, Softmax)
        ↓
Class Prediction
```

## Preprocessing

The image pixel values are normalized from the range 0–255 to 0–1 by dividing the images by `255.0`.

## Training

The model is compiled using:

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Metric: Accuracy
* Epochs: 5

## Prediction

After training, the model evaluates the test dataset and predicts clothing categories for test images.

The project also displays the actual and predicted class names for sample images.

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd Fashion-MNIST-Clothing-Classification
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the project

```bash
python fashion_mnist_classifier.py
```

## Project Structure

```text
Fashion-MNIST-Clothing-Classification/
│
├── fashion_mnist_classifier.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Learning Outcome

Through this project, I practiced:

* Loading datasets using Keras
* Image preprocessing
* Neural network creation
* Model compilation
* Model training
* Model evaluation
* Image classification
* Visualizing predictions

## Future Improvements

* Increase model accuracy
* Experiment with different neural network architectures
* Add a CNN-based model
* Save and load the trained model
* Build a simple web interface for predictions

## Author

Manthan Dike