# Banknote Authentication

This is the code for a classifier that detects fake banknotes.

## Overview

I built a multilayer perceptron which classifies real and forged banknotes, using the [TensorFlow](https://www.tensorflow.org/) library. Data preprocesssing was done with [Scikit-learn](http://scikit-learn.org/stable/). The inputs are numeric values, and the output is binary.

The model was able to classify banknotes with a **100%** accuracy, which suggests that the data was probably just easy to classify.

## Dependencies

- numpy
- pandas
- scikit-learn
- tensorflow

Install dependencies using [pip](https://pip.pypa.io/en/stable/).

## Dataset

The dataset was taken from the [UCI Repository](https://archive.ics.uci.edu/ml/datasets/banknote+authentication). It contains 1,372 observations (banknotes) and 4 attributes.

**Note:** Data were numeric values extracted from Wavelet Transformed Images (WTIs) of banknote specimens.

| Column  | Definition |
| ------------- | ------------- |
| Image.Var  | Variance of the WTI  |
| Image.Skew  | Skewness of the WTI  |
| Image.Curt  | Curtosis of the WTI  |
| Entropy  | Entropy of the image  |
| Class  | Authenticity of the banknote  |

## Usage

Run the notebook on a localhost server using `jupyter notebook`.
