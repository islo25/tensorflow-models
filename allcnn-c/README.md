# tensorflow-models
My poor implementations of a few successful neural networks.  

I extensively used codes from either:   

1. https://github.com/lisa-lab/pylearn2    
2. https://github.com/NervanaSystems/neon  
3. https://github.com/tensorflow/tensorflow.   

Start by downloading CIFAR-10 for python and change the folder data-dir.  

cifar10-allcnn : This code is me trying to reimplement a [nervana neon model](https://github.com/NervanaSystems/ModelZoo/tree/master/ImageClassification/CIFAR10/All_CNN) inspired by : [Striving for Simplicity: the All Convolutional Net by Jost Tobias Springenberg, Alexey Dosovitskiy, Thomas Brox and Martin Riedmiller](http://arxiv.org/abs/1412.6806).  
I got to 89.31% top-1 accuracy on CIFAR-10 test set which is slightly less than nervana 89.5%.  
Here is the training informations:  
![Alt text](/img.png?raw=true "Optional Title")
