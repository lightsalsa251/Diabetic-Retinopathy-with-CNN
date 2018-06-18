# Diabetic Retinopathy with CNN
Detect the stage of diabetes in human retina. The 150 GB image data is from Kaggle's Diabetic Retinopathy Detection Repository.
Run the flask app in Deployed Model folder to see the model in action.
Sample images have been stored in the Deployed Model folder for testing.\
ResNet architecture has been used for training\
![Residual Learning](https://cdn-images-1.medium.com/max/1200/1*ByrVJspW-TefwlH7OLxNkg.png)\
Convolutional Neural Networks aka ConvNet is a class of deep learning, most commonly applied to image datasets.\
There are multiple types of commonly used layers in ConvNets
* Convolution layer - This layer applies the convolution operation on an image with a defined stride and padding
* Pooling layer - This layer is used for reducing the dimensionality of feature maps by defining a mask and an operation to be performed, then moving the mask on the whole image according to the stride defined. No weights are learnt in this layer
* Fully Connected layer - Traditional neural layers, used at the end stem of the neural network. Used rarely these days due to the staggering amount of parameters it uses
* Dropout layer - Used for reducing over-fitting. It randomly turns off some neurons at each pass during the training
* Batch Normalisation - Normalises the output values thus reducing computation time. Also introduces regularisation effect\
![Conv Operation](http://machinelearninguru.com/_images/topics/computer_vision/basics/convolution/1.JPG)
#### I have written an article on detecting diabetic retinopathy [here](https://medium.com/@s.ganjoo96/diabetic-retinopathy-detection-with-resnet50-b621514bd22b)
## Installation
### Download the data and clone this repository
* Clone this repository to your computer.
* Get into the folder using cd Diabetic-Retinopathy-Detection-with-CNN.
* Download the data files from Kaggle into this directory.
### Installing the requirements
* pip install requirements.txt
## Usage
* Run each cell in the Model_script.ipynb file. 
* Save your model in the sub folder of Deployed Model folder.
* Run the app.py file.
* Let the server load, open a web browser and type localhost:5000
#### You are ready to go
## Result
Trained this model on cloud for **only** 2 epochs because of very little financial resources, the model achieves 73% accuracy.
