# Binary Image Classification - Cat vs. Non-Cat

## Overview
This project implements a **Deep Neural Network (DNN) for Binary Image Classification**, specifically designed to classify images as either containing a **cat** or not. The model is built using **TensorFlow**, leveraging deep learning techniques to achieve high classification accuracy.

## Features
- **Deep Neural Network (DNN)**: Custom architecture optimized for image classification.
- **Binary Classification**: Determines whether an image contains a cat or not.
- **TensorFlow**: Implemented using state-of-the-art deep learning frameworks.
- **Dataset Handling**: Supports image pre-processing and augmentation for better generalization.
- **Performance Metrics**: Tracks accuracy, precision, recall, and loss over training epochs.

## Installation
To run this project, ensure you have Python installed, then install the required dependencies:

```bash
pip install tensorflow numpy matplotlib opencv-python
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/adityaamehra/Cat-vs-dog.git
   cd Cat-vs-dog
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
3. Train the model using the provided dataset and evaluate its performance.

## Dataset
The model requires a dataset of labeled images containing cats and non-cat images. Ensure the dataset is structured as follows:
```
/dataset
   /cats
      cat1.jpg
      cat2.jpg
   /dog
      dog1.jpg
      dog2.jpg
```

## Model Architecture
The deep neural network consists of:
- **Convolutional Layers** for feature extraction
- **Pooling Layers** for dimensionality reduction
- **Fully Connected Layers** for final classification
- **Softmax Activation** for binary output (Cat/Non-Cat)

## Performance Evaluation
The model is evaluated using:
- **Accuracy**
- **Precision & Recall**
- **Confusion Matrix**
- **Loss Curves**

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the **MIT License**.

