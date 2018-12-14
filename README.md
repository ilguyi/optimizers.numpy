# Various Optimizers based on Gradient Descent
* Final update: 2018. 12. 15.
* All right reserved @ Il Gu Yi 2018

## Educational Purpose
* Implementation various optimization algorithms based on gradient descent
* Only use **numpy**, don't use deep learning framework like [TensorFlow](https://www.tensorflow.org)
* Low level coding in each algorithm


## Getting Started

### Prerequisites
* Python 3.6
  * `numpy`, `matplotlib`
* Jupyter notebook
* OS X and Linux (Not validated on Windows but probably it might work)


## Contents

### Linear Regression using Gradient Descent
* Gradient Descent
  - [01.gradient.descent.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/01.gradient.descent.ipynb)
* Stochastic Gradient Descent
  - [02.stochastic.gradient.descent.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/02.stochastic.gradient.descent.ipynb)
* Coordinate Gradient Descent
  - [03.coordinate.gradient.descent.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/03.coordinate.gradient.descent.ipynb)
* Linear Regression with 5 optimizers
  - [regression.all.opt.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/regression.all.opt.ipynb)


### Optimization of Beale Function using Various Gradient Descent Algorithms
* Gradient Descent
  - [04.1.sgd.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/04.1.sgd.ipynb)
  - [04.2.sgd.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/04.2.sgd.ipynb)
* Momentum
  - [05.momentum.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/05.momentum.ipynb)
* Nesterov Momentum
  - [06.1.Nesterov.momentum.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/06.1.Nesterov.momentum.ipynb)
  - [06.2.Nesterov.momentum.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/06.2.Nesterov.momentum.ipynb)
* Adagrad [(paper link)](http://jmlr.org/papers/v12/duchi11a.html)
  - [07.adagrad.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/07.adagrad.ipynb)
* RMSprop [(Tieleman and Hinton's Lecture slide, 2012)](https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf)
  - [08.RMSprop.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/08.RMSprop.ipynb)
* Adam optimizer [(arXiv:1412.6980)](https://arxiv.org/abs/1412.6980)
  - [09.adam.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/09.adam.ipynb)
* optimizer implemented by TensorFlow
  - [optimizer.tf.version.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/optimizer.tf.version.ipynb)
* optimizer implemented by TensorFlow for plot
  - [optimizer.tf.all.opt.plot.ipynb](https://nbviewer.jupyter.org/github/ilguyi/optimizers.numpy/blob/master/optimizer.tf.all.opt.plot.ipynb)


### Results

#### Optimization of Linear Regression using Various Gradient Descent Algorithms
<div align="center">
<img width="440px" alt="regression_all" src="https://user-images.githubusercontent.com/11681225/50016565-e4d0af80-000c-11e9-8d8d-fe75f8f0bc38.jpg">
<img width="440px" alt="regression_all.gif" src="https://user-images.githubusercontent.com/11681225/50016682-39742a80-000d-11e9-81da-ab0406610b9c.gif">
</div>

#### Optimization of Beale Function using Various Gradient Descent Algorithms
<div align="center">
<img width="440px" alt="all_test_optimizers" src="https://user-images.githubusercontent.com/11681225/49284813-08f2a380-f4d9-11e8-9216-f96335da67a8.png">
<img width="440px" alt="all_test_optimizers.gif" src="https://user-images.githubusercontent.com/11681225/49325458-fc785480-f585-11e8-8d2a-9012d6024c6e.gif">
</div>



## References
* S. Ruder, An overview of gradient descent optimization algorithms [(arXiv:1609.04747)](https://arxiv.org/abs/1609.04747)
* S. Ruder's blog: [An overview of gradient descent optimization algorithms](http://ruder.io/optimizing-gradient-descent/) (the same content as above)
* Louis Tiao's blog: [Visualizing and Animating Optimization Algorithms with Matplotlib](http://louistiao.me/notes/visualizing-and-animating-optimization-algorithms-with-matplotlib/)
  * Some codes for 3D plot and contour plot are borrowed from this blog




## Author
Il Gu Yi
