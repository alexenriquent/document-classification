# Document Type Classification
## Overview
This proof-of-concept project is an attempt to demonstrate an end-to-end pipeline for document type classification using a deep feedforward neural network. The labels to predict include "agenda", "medical record", "paper" and "resume". Two notebooks are included: 
* **document_classification**: An end-to-end process from ingesting and preprocessing local files, training the model and saving it locally.
* **azureml_document_classification**: This notebook illustrates an alternative scenario using Azure Machine Learning to manage the machine learning life cycle from data collection, data preparation, feature engineering, model training and evaluation through to model deployment and maintenance.
## Tech Stack
* **Language**: Python
* **Libraries**: Scikit Learn, Keras with Tensorflow backend, Numpy, Pandas, Pickle and Tika
* **Learning Algorithm**: Deep Feedforward Neural Network
* **Other Services**: Azure Machine Learning and Docker
