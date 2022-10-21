# Document Classification
## Overview
This proof-of-concept project is an attempt to demonstrate an end-to-end pipeline for document classification using a deep feedforward neural network with tf-idf as input features. The labels to predict include "agenda", "medical record", "paper" and "resume". Two notebooks are included: 
* **document_classification**: An end-to-end process from ingesting and preprocessing local files, training the model and saving it locally.
* **azureml_document_classification**: This notebook illustrates an alternative scenario using Azure Machine Learning to manage the data science lifecycle from data ingestion, model training and evaluation as well as model deployment.
## Tech Stack
* **Language**: Python
* **Libraries**: Scikit Learn, Keras with Tensorflow backend, Numpy, Pandas, Pickle and Tika
* **Learning Algorithm**: Deep Feedforward Neural Network
* **Other Services**: Azure Machine Learning and Docker
