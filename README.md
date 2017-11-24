# Iris Dataset Tensorflow Problem Sheet
## CA Relating to Fourth Year Emerging Technolgies

## Project Specs

### 1. Use Tensorflow to create model


  Use Tensorflow to create a model to predict the species of Iris from a flower’s sepal width, sepal length, petal width, and petal      length.

### 2. Split the data into training and testing


  Split the data set into a training set and a testing set. You should investigate the best way to do this, and list any online   references used in your notebook. If you wish to, you can write some code to randomly separate the data on the fly.

### 3. Train the model


  Use the testing set to train your model.

### 4. Test the model


  Use the testing set to test your model, clearly calculating and displaying the error rate.

## What is the Iris Data Set?
This data sets consists of 3 different types of irises’ (Setosa, Versicolour, and Virginica) petal and sepal length, stored in a 150x4 numpy.ndarray. 
The rows being the samples and the columns being: Sepal Length, Sepal Width, Petal Length and Petal Width.
The below plot uses the first two features. See here for more information on this dataset.

## What is Tensorflow?
TensorFlow is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API. 

**REF**: [https://www.tensorflow.org/](https://www.tensorflow.org/)

## What is Keras?
Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research.

**REF**: [https://keras.io/](https://keras.io/)

## How to run application 

Make sure you have at least Python 3.5 installed

**REF** [https://www.python.org/downloads/](https://www.python.org/downloads/)

Be sure install Keras and Jupyter Notebook and upgraded to latist version

`pip --upgrade keras`
`pip --upgrade jupyter notebook`

Clone the repo to your desktop, navigate to the directory of the repo, and in the command prompt type

`jupyter notebook Iris DataSet Using Keras with Tensorflow Backend.ipynb`

