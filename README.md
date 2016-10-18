### Image-Classification-with-TensorFlow

#### Description
Convolutional neural network is applied under TensorFlow framework to classify alphabets from notMNIST dataset.  95.6% accuracy is achieved with 2 hidden layers and a dropout, compared to 89% with logistic regression.  By making the network deeper and fine-tuning a few parameters, further accuracy improvement is expected.

#### Method
200,000 images with resolution of  28x28 are used for training on a laptop with 1.8 GHz Intel core i5 with no GPU.  It takes about 1 hr. The classification accuracy is tested on separate 10,000 images.

#### Instruction
To run the program:

First, type  `python importData.py` to import notMNIST dataset from 'http://commondatastorage.googleapis.com/books1000/'

Second, type `python convNet.py` to run ConvNet.

