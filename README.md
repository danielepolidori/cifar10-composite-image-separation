# CIFAR-10 Composite Image Separation

_This project was developed as part of the Machine Learning course, during my Master's degree in Computer Science at the University of Bologna._
 
## Task
 
The task consists in classifying the two components of a composite image obtained as the pixel-wise mean of two CIFAR-10 samples. The first component is drawn from the first five categories (airplane, automobile, bird, cat, deer), while the second is drawn from the remaining five (dog, frog, horse, ship, truck). The model receives the composite image as input and returns two labels, each within its respective range of five categories.
 
## Evaluation
 
The model is evaluated using the mean classification accuracy across the two predicted labels. The metric is computed over 10,000 randomly generated test images, and the procedure is repeated ten times to report the mean accuracy alongside its standard deviation.
 
## Requirements
 
```
tensorflow
numpy
matplotlib
```
