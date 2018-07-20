# AlexNet

AlexNet was the first CNN to do a pretty good job on the ImageNet challenge, it contains 8 layers, 5 convolutional layers 
and 3 Fully Connnected layers. 

There is two implementations here, one with Pure Tensorflow and one with Keras, the Keras implementation works fine, it gets
around 95% top 5 error on the Cifar10 dataset and about 64% top 1 error, the Tensorflow implementation still does not work well 
and it hovers around 10% top 1 error, so i'll need to find out what's wrong with that one.