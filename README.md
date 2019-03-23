# Paper-Implementation-Overview-Gradient-Descent-Optimization-Algorithms  

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) [![MIT Licence](https://badges.frapsoft.com/os/mit/mit-150x33.png?v=103)](https://opensource.org/licenses/mit-license.php)


## arXiv paper :   
## An Overview of Gradient Descent Optimization Algorithms - Sebastian Ruder  

## Python 2.7  

Links to Original Paper published on arXiv.org>cs>arXiv:1609.04747  : [[1]](https://arxiv.org/abs/1609.04747), [[2]](https://arxiv.org/pdf/1609.04747.pdf)   

Link to Blog with Paper Explanation : [[3]](http://ruder.io/optimizing-gradient-descent/index.html)  

Implemented following Gradient Desent Optimization Algorithms from Scratch:  

1. Vanilla Batch/Stochastic Gradient Descent [[4]](https://en.wikipedia.org/wiki/Stochastic_gradient_descent) : **batch_gradient_descent.py**   

2. Momentum [[5]](https://www.cs.toronto.edu/~fritz/absps/momentum.pdf) : **momentum.py**  
3. NAG : Nesterov Accelarated Gradient  [[6]](https://www2.cs.uic.edu/~zhangx/teaching/agm.pdf) : **nesterov_accelarated_gradient.py**
4. AdaGrad : Adaptive Gradient Algorithm [[7]](http://www.jmlr.org/papers/volume12/duchi11a/duchi11a.pdf) : **adagrad.py**
5. AdaDelta : Adaptive Learning Rate Method [[8]](https://arxiv.org/abs/1212.5701) : **adadelta.py**
6. RMS Prop  [[9]](https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) : **rms_prop.py**   
7. Adam : Adaptive Moment Estimation [[10]](https://arxiv.org/abs/1412.6980) [[11]](https://arxiv.org/pdf/1412.6980.pdf) : **adam.py**  
8. AdaMax : Infinity Norm based Adaptive Moment Estimation [[12]](https://arxiv.org/pdf/1412.6980.pdf) : **adamax.py**  
9. Nadam : Nesterov-accelarated Adaptive Moment Estimation [[13]](http://cs229.stanford.edu/proj2015/054_report.pdf) : **nadam.py**  
10. AMSGrad [[14]](http://www.satyenkale.com/papers/amsgrad.pdf) : **amsgrad.py**   

### Time and Error Analysis : 
Minimized dummy Cost Function f(x) = x^2 using default values as initial approximation = 1, error tolerance = 0.0001, learning rate = 0.1, gamma = 0.9, beta_1 = 0.9, beta_2 = 0.999  

![alt text](https://github.com/harshraj11584/Paper-Implementation-Overview-Gradient-Descent-Optimization-Algorithms/blob/master/error_chart.png)
