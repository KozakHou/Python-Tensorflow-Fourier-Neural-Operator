# Fourier-Neural-Operator-with-Tensorflow
Implementing Zongyi Li's FNO on image classifcation which he used it through Pytorch.

The work doing in here is to transform Pytorch into Tensorflow.

Later we will show not only Image Classification case, but using pure Data-driven method to fit in the Navier Stokes Theorem and Burger's Equation.


The table shows different Neural Network's achivement in MNIST classification.
|  Model                                   | Train Accuracy | Train Loss | Test Accuracy | Test Loss |
|------------------------------------------|----------------|------------|---------------|-----------|
| Fully connected network - After 5 Epochs |         0.8923 |     0.2935 |        0.8731 |    0.2432 |
| Convolutional network - After 5 Epochs   |         0.8860 |     0.3094 |        0.9048 |    0.1954 |      
| Residual network - After 5 Epochs        |         0.9064 |     0.2610 |        0.8713 |    0.3398 |
| Fourier Neural Operator - After 5 Epochs |         0.9486 |     0.1622 |        0.9455 |    0.1806 |


**Citation**
```
@KozakHou, email:kozak20010716@g.ncu.edu.tw
           Tel : +886-905804898
           Affiliation : Department of Space Science and Engineering, National Central University 
```
