# Crystal-Gazers
This universitary project aims to train a ML model with the Wikipedia dataset in order to predict the next word given a sequence of words. The model will output a word for every input given. The model is developped in Python and executed in Kaggle.com .

## Model description

To archieve the desired prediction we will use a Transformer model with one or more layers. A transformer is a model that adopts the mechanism of self-attention, deferentially weighting the significance of each part of the input data. The model will be trained on text data which was originally created by humans. 

The model file gives the possibility to introduce multihead attention. At the end, there will be an accuracy comparison based on the performance of both methods. 

## Dataset
The Wikipedia dataset is a collection of scraped Wikipedia pages. The dataset is defined in catalan language, thus the model will be trained to recognize input exclusively in catalan.

The dataset can be found in the following link:

https://www.kaggle.com/datasets/jarfo1/viquipdia
---

language:
  - ca
  
tags:
  - prediction
  - NLP
  - text
  - transformer
  - CrossEntropy
  - text generation
  
license:  
  - apache-2.0
  
dataset:
  - Viquipèdia
  
metrics:
  - accuracy
  - CrossEntropyLoss

---
