# NDNN
##Introduction
This repository contains the code used for generating and analyzing the data in the study "Scalable nonlinear reconfigurable all-optical diffractive neural network". We constructed a physical setup of a three-layer nonlinear reconfigurable diffractive neural network (DNN) with a single SLM and a single mirror-coated Si wafer. This repository contains the code used for training phase profile for the experimental setup.

A quick guide on the contents of the repository:

Folder 'dataset' contains jpg images used to train the 25 class quickdraw dataset. Each folder corresponds to one class.
'data_generation_draw.py': Data generation and preprocessing
'tf_opticsModule_draw.py': Define angular spectrum propagation
'data_ops_draw.py': Define sensors distribution and generate validation dataset
'initialization_draw.py': Define parameters
'mask_modulation_model_draw.py': Define nonlinear activation function and loss function. Build training model.
'onn_mask_train_draw.py'：Model training, evaluation, and saving
