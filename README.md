# Graph-Anomaly-Detection

Python version required: 3.8

## AMNet
The Tensorflow implementation of Adaptive Multi-frequency filtering graph neural network proposed in the paper.

## Dependencies
The project works on Tensorflow and Spektral whcih is a Python library for graph deep learning, based on the Keras API and TensorFlow 2. 
```
tensorflow-2.11.0
spektral-1.2.0
```
Every required library is downloaded and imported in the code file

## Dataset
The two benchmark datasets Yelp and Elliptic for evaluation. The datasets are provided. The spektral graph-data object is created using the Adjacency Matrix, Feature matrix, the Lables and the boolean arrays of Test, Train and Validation masks from the preprocessed datasets available for PyTorch implementation). Please mount these datasets to Google Drive and unzip them. 

## Run the model.
To run this project, go to the ```Amnet.ipynb``` file, which is a Google Colab notebook. Give the path of the dataset( Either Yelp of Elliptic) and run the file with required settings.

### Model parameter settings
Channels for Yelp must be set to 64 and Elliptic must be set to 128.





