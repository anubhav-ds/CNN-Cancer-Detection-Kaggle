# CNN-Cancer-Detection-Kaggle
Histopathologic Cancer Detection Project

Histopathologic Cancer Detection Resnet 50 Model
The goal of this project is to train a Convolutional Neural Network, specifically Resnet with 50 layers, in order to identify if the center of the image of a body tissue collected from a pathology scan contains cancerous tissues or not. This is a binary classification problem, meaning that each training example is labeled as either being cancerous(1) or not cancerous(0).

Cancerous in this case means that at least one pixel of the image contains tumorous tissue.

The dataset is based on PatchCamelyon (PCam) benchmark dataset (the original PCam dataset contains duplicate images due to its probabilistic sampling, however, the version presented on Kaggle does not contain duplicates). The source of this data is this Kaggle competition: https://www.kaggle.com/competitions/histopathologic-cancer-detection

The dataset consists of 220025 training images that are all labeled with if they are cancerous or not. Additionally, there are 57458 unlabeled test images. The goal of this project for the built neural network to predict reasonably well the labels on this test set. The test data set does not come with test labels, so the test performance will be gotten by making submissions to the kaggle competition.
