# Assignment 8

1. Go through this repository: [https://github.com/kuangliu/pytorch-cifar ](https://github.com/kuangliu/pytorch-cifar)
2. Extract the **ResNet18** model from this repository and add it to your API/repo. 
3. Use your data loader, model loading, train, and test code to train ResNet18 on **Cifar10**
4. Your Target is 85% accuracy. No limit on the number of epochs. Use default ResNet18 code (so params are fixed). 

## Package used
The athena package was developed and used in this assignment. [Link to the package documentation](https://firekind.github.io/athena).

## Training
The model was trained for 30 epochs, with an **SGD optimizer** with **learning rate 0.01** and **momentum 0.9**. The highest accuracy was achieved at **epoch 30**, and it was **85.14%** using **Cross Entropy Loss** over **StepLR**. 

Observations:

1. Can have better LR Strategy
2. Heavy Over fitting
3. Need Augmentations
4. More optimised Resnet 18 could be written and used.