# Flower Classification

In this mini project, I have used the flower dataset from kaggle in order to train a CNN model that can classify flowers. I have also 
described the functions of all the classes, methods in the PyTorch libraries so that a novice can understand it very clearly. Gpu's have
also been used.

## Getting Started

The first step is to download the dataset from the given [link](https://www.kaggle.com/alxmamaev/flowers-recognition). Clone this repository on your local machine so as to access the .ipynb files or you can directly access from google colab. 
The structure of the repository is shown as below:
```
Flower-Classification-using-CNN-pytorch
│   README.md   
│
└───src
│   │   Data loading.ipynb
│   │   Flower classification with gpu.ipynb

```
### Prerequisites

I recommend using google colab in order to access these files. There will be no dependency as everything is pre-installed. If you are using
Jupyter Notebook, you have to install the dependencies which are imported in the interactive notebook. 

### Procedure
Data loading.ipynb is used to split the dataset into training and testing set (and validation set). 

**Beware:** This notebook can only be run once.

Flower classification with gpu.ipynb is used to train a CNN model to classify the flower images and find out the accuracy of the model.
