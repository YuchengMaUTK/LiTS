# Liver segmengtation using deep learning
we use 3DResUnet to segment liver in CT images and use DenseCRF as post processing.
Souce code link: https://github.com/assassint2017/MICCAI-LITS2017

## Dataset
Liver tumor Segmentation Challenge (LiTS) contain 131 contrast-enhanced CT images provided by hospital around the world. 

## Usage
parameter in **parameter.py**, so first set dataset path then run 
**./data_pareper/get_training_set.py** to get the training set
then you can run **./train_ds.py** to train the the network from scratch. after the model is well trained, run **val.py** to test the model on test set.
