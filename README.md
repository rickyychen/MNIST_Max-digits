# MNIST_Max-digits
## Contriubtors: 
- Mia Tran
- Peter Guanhua Rong
- Ricky Chen

## Abstract
This is the McGill MAIS202 Assignment 4/Kaggle competition. The goal in this assignment is to identify the largest numerical value in pictures that contain 3 handwritten numerical digits. The proposed and implemented algorithm to this task is a 5 layers convolution neural network. We implmeneted additional data generation using a image data geneartor from the Keras library and experimented with several data preprocessing methods, with careful trial and erros, a final testing accuracy of 98% was acheived. 

## Repository Structure
The repository contains 5 files:
- 2 Jupyter notebook files: 
  - Post_denoise.ipynb ( 96% accuracy )
  - Pre_denoise_Modified_MNIST.ipynb ( 98% accuracy )
- 1 ReadMe file: 
  - README.md
- 1 Results prediction file:
  - prediction.csv
- 1 Project writeup file:
  - Write-up.pdf
## Dataset
https://www.kaggle.com/c/mais-202-fall-2020-kaggle-competition/data

## Usage
1. Run the notebook "Pre_denoise_Modified_MNIST.ipynb" on local machine or google colab
2. Be sure to switch runtime to GPU to achieve a faster execution
3. Be sure to upload a kaggle varification key to gain access to the dataset
4. Run all cells
