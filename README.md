
# Image Classification with Batch Average Loss Function


## Description
To learn from a dataset containing images while also preserving privacy can be challenging. This
project presents a framework that utilizes a custom loss function which compares predictions and the
statistics from the batches to help the model learn from the data.

## Dataset
The dataset used for training the model is CIFAR-10: https://www.cs.toronto.edu/~kriz/cifar.html, and is loaded using tensorflow library 'tensorflow.keras.datasets'.
## Installation
No installation is required. The notebook runs on Google Colab with dependencies installed automatically

## Dependencies
Required packages:
 - 'numpy'
 - 'tensorflow'
 - 'matplotlib'
 Run first cell in notebook to install dependencies.

## Usage
1. Open notebook: https://colab.research.google.com/drive/1uYZkF1-OE1b7mcWx836TlA1Z0AW88bOA?usp=sharing

2. Costumize inputs (optional):
   - Adjust the class distribution as needed as long as they remain unbalanced.
   - Batches and epochs can also be modified as needed.

3. Run all cells. GPU usage is recommended for training the model.

## Author

Rina Ahmetaj

## Credits

This project was completed under the supervision of Professor Zhao at Lehman College - CUNY.

