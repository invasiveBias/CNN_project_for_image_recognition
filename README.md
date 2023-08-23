# CNN_project_for_image_recognition
A project to understand Convolutional Neural networks for image classification. The model uses the conventional method of processing mages through convolutional layers and then flattening features through end-point feed forward linear layers.
The project also aims to compare the performance of newly-built model & a pre-trained model for image classification task.
The project is split into General understanding of Convolutional Neural Networks, Data processing, Building,training & evaluating a model from scratch & then fine-tuning & eavluating a downloaded pretrained model
The project was developed mainly with the Tensorflow based Keras Library for Model development training & evaluation, notable sub-modules include Sequential, Layers & Callback,Pre_processing on the image data was done with the cv2(openCV),os & numpy libraries.
The dataset used to train the model is a dataset of 17,000 images grouped into 6 classes.
The Pre-trained model used in this project is the ResNet50 model.
Project was built on Jupyter notebook with a Local CPU machine. GPU/TPU based machines are recommended to get faster training time & fairer loss reduction during training.
