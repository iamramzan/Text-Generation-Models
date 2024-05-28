# Text-Generation-Models

Project Overview:

In this project, I build a Text Generation Model using Natural Language Processing.

Project Steps:

- importing packages and the dataset
- convert the text to sequences of integers and also create sequences for training
- split input and target text
- shuffle the dataset and pack it into training batches
- RNN model with a few layers to build the model
- choose an optimizer and a loss function to compile the model
- train the model
- restore the latest checkpoint and rebuild the model with a batch size of 1
- generate the text

Local Setup:

- import tensorflow as tf
- import tensorflow_datasets as tfds
- import numpy as np
