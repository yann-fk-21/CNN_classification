# CNN_classification

This repository contains a Jupyter Notebook file (`CNN_classification.ipynb`) that demonstrates image classification using a Convolutional Neural Network (CNN). This notebook uses the CIFAR-10 dataset to train and evaluate the model.

## File Contents

- **Importing Necessary Libraries**: TensorFlow, Keras, Matplotlib, NumPy.
- **Downloading and Preprocessing CIFAR-10 Data**: Loading data, normalization, and visualizing samples.
- **Defining the CNN Model**: Creating a sequential model with multiple convolution and pooling layers.
- **Compiling and Training the Model**: Compiling the model with the Adam optimizer and `sparse_categorical_crossentropy` loss function, then training it on CIFAR-10 data.
- **Evaluating the Model**: Evaluating model performance on test data and visualizing predictions.

## Usage

To run the notebook, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yann-fk-21/CNN_classification.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd CNN_classification
   ```
3. Open the `CNN_classification.ipynb` file with Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook CNN_classification.ipynb
   ```
4. Run the cells in the notebook to train and evaluate the CNN model.

## Prerequisites

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Python libraries: TensorFlow, Keras, Matplotlib, NumPy

You can install the required libraries by executing the following command:
```bash
pip install tensorflow keras matplotlib numpy
```

## Author

This project was created by [yann-fk-21](https://github.com/yann-fk-21).
