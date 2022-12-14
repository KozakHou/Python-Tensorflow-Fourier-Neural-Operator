# Fourier-Neural-Operator-with-Tensorflow
Implementing Zongyi Li's FNO on image classifcation which he used it through Pytorch.

The work doing in here is to transform Pytorch into Tensorflow.

Later I will show not only Image Classification case, but using pure Data-driven method to fit in the Navier Stokes Theorem and Burger's Equation.


---
The table shows different model's evaluation in MNIST classification. Though FNO has highest accuracy, it takes the longest time to compute.
(Your results may be slighty different.)

|  Model                                   | Train Accuracy | Train Loss | Test Accuracy | Test Loss |
|------------------------------------------|----------------|------------|---------------|-----------|
| Fully connected network - After 5 Epochs |         0.8923 |     0.2935 |        0.8731 |    0.2432 |
| Convolutional network - After 5 Epochs   |         0.8860 |     0.3094 |        0.9048 |    0.1954 |      
| Residual network - After 5 Epochs        |         0.9064 |     0.2610 |        0.8713 |    0.3398 |
| Fourier Neural Operator - After 5 Epochs |         0.9486 |     0.1622 |        0.9455 |    0.1806 |


Zhogyi Li's FNO Model
![alt text for screen readers](https://github.com/KozakHou/Python-Tensorflow-Fourier-Neural-Operator/blob/main/ZY_FNO.png "Text to show on mouseover")


---
self-construct Model Flow
![alt text for screen readers](https://github.com/KozakHou/Python-Tensorflow-Fourier-Neural-Operator/blob/main/FNO_Model_CF.png "Text to show on mouseover")


---
**Citation**
```
@code{Fourier Neural Operator with Tensorflow, 
           author = "Kozak Hou"
           email = "kozak20010716@g.ncu.edu.tw"
           Tel : +886-905804898
           Affiliation = "Department of Space Science and Engineering, National Central University"
     }      
```


