# Semantic Segmentation
### Introduction
In this project, we use Fully Convolutional Network (FCN) to classify every pixel in an image to be road or not road. It is a basic step in scene understanding. This project implements the idea from this paper: https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)

##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Model
##### Hyperparameter
* number of epochs: 50
* batch size: 16
* keep_prob: 0.75
* learning_rate: 0.0001

##### Run
Run the following command to run the project:
```
python main.py
```
##### Results
###### Loss over training
The loss is decreasing over training and converge at the end. The loss value vs. training time is shown below.
[image]
###### Inference on test
Several sample images with labeled pixels are shown below.
[eg1]
[eg2]
[eg3]
[eg4]

