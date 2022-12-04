# Autism Safety

## Description
The Main task is to perform both Autistic and Normal kids classes classification we used mp4 dataset videos as inputs into  the  Convolutional neural networks (CNN) Model

## The dataset
The [dataset]([https://pavis.iit.it/index.php/datasets/autism-spectrum-disorder-detection-dataset](https://drive.google.com/drive/folders/1N-bNh1waxe3KTS5tPWTKNeDPlOXQ48FU?fbclid=IwAR1y9WJhDdMRE7ww1fHCluh2BvqD4DVpdH1NnhKpuT2JjgKDDKtEAna12wQ)) contains trials performed by both autistic  and normal Kids.

#### Example of autistic kids.
![alt text](aut.PNG)

#### Example of normal kids.
![alt text](nrml.PNG)


## The code 
This repo is based on [this public code](https://github.com/kracwarlock/action-recognition-visual-attention) implementing an [attention-based LSTM](https://arxiv.org/abs/1511.04119v3) and is meant to classify autistic kids from the kinematics of motion. It contains:
- matlab scripts for estracting CNN features from the video frames (GoogleNet - Caffe) 
- python scripts for the actual LSTM training (theano)

### (Main) Dependencies
* Python 2.7
* [NumPy](http://www.numpy.org/)
* [scikit learn](http://scikit-learn.org/stable/index.html)
* [skimage](http://scikit-image.org/docs/dev/api/skimage.html)
* [Theano](http://www.deeplearning.net/software/theano/)
* [h5py](http://docs.h5py.org/en/latest/)
* Matlab
* [Caffe](https://github.com/BVLC/caffe)


## License
This repository is released under the MIT LICENSE.
