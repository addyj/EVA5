## Neural Architecture Basics

#### EVA 5 Session 4 Assignment

##### Hyper Parameters : 

- Epochs : 12
- Batch Size : 512
- Learning Rate : 0.05
- Model Parameters : 19.77 k
- Momentum : 0.9
- Workers : 1
- Dropout : 0.1

##### Normalised Data set by :

- Train Mean (0.1307)
- Train Standard Deviation (0.3081)

##### Validation Accuracy Reached >= 99.4%

---

#### Extra Spices to the model

- Added Dropout strategy to the model
- Used Batch Normalisation
- Added Adaptive Average Pooling for classification

---

### Model Structure:

`ConvBlock1` ==> `TransitionBlock` ==> `ConvBlock2` ==> `GAP Layer` ==> `Softmax`

##### Convolution Block has:

`Conv` ==> `Relu` ==> `BatchNorm` ==> `Dropout` 

##### Transition Block has:

`Maxpool` ==> `Pointwise Conv ` ==> `Relu` ==> `BatchNorm` 



##### 

