# Transfer_learning

The following repository contains a practice implementation of the concept transfer learning using a pretrained image classification network resnet18. The dataset used is a binary classification image dataset containing ant and bees. Here, we have implemented two different models on the same dataset for the same task. In first implementation, complete model parameters are set to train whereas in the second implementation all the layers except the final layer are freezed and only the parameters of the final are set to update.

The following code was implemented in Pytorch using google colab for computation resource. The libraries used are - 

1. matplotib
2. torch
3. torchvision
4. numpy
5. time
6. copy
