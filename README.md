# Skin Disease Classification on Pytorch and Tensorflow
The project contains the implementation of a Convolutional Neural Network for Image Classification, implemented in Pytorch and Tensorflow.
## Dataset
The dataset used for such project is [Skin Cancer MNIST: HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000). This dataset consists of 10015 dermatoscopic images, which show pigmented skin lesions.
The classes of such lesions are:
* Bowen's disease
* Basal cell carcinoma
* Bening keratosis-like lesions
* Dermatofibroma
* Melanocytic nevi
* Melanoma
* Vascular Lesions

Some images are reported below as an example:
![image](data.png "Data samples")
## Approach
The proposed approach consists in a Convolutional Neural Network, for multi-class image classification, which has been implemented from scratch.
## Usage
This repository contains two files: one for each framework. Inside each notebook, there is all the information and code needed to load and prepare the dataset properly.
## Results
| Framework      | Training accuracy | Validation accuracy | Test accuracy |
| ----------     | ----------------- | ------------------- | --------------|
| Pytorch        |      89.29%       |        81.72%       |    70.03%     |     
| Tensorflow     |      89.18%       |        80.30%       |    68.75%     |
