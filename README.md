# Unicorn vs. Narwhal Classifier
Below, I'll be implementing a basic convolutional neural network (CNN) in Python to classify images of unicorns and narwhals. You can read the full blog post and get more background on the project at https://shaynechammavanijakul.com/2020/07/14/unicorn-narwhal-classifier/.

In this repository, you'll find the following materials: 

## train
These contain images used for training. Four hundred images were originally used, but one hundred are posted here. 

## test
These contain the eighty total images used for testing. 

## unicorn_narwhal_model_train
Here, we prepare our images for training using Keras, and then both build and save our binary classification model. 

## unicorn_narwhal_model_test
Here, we test the model we've created. Load an image through the path, and the model will determine whether a unicorn or a narwhal is detected. 
