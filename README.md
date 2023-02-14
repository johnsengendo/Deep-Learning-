# Deep-Learning image classification.

Image recognisition and classification has become a leading application in deeplearning which has found applications in Medical diagnosis, self driving cars , car number plate reading in self operated parkings. Applications of Deep learning are still growing exponentially. 
In this project, I performed an Image recognisition task on a CIFAR100 [dataset](https://www.cs.toronto.edu/~kriz/cifar.html) 

The task involved developing and training a neural network to perform image recognision and classification. The network built was a Convolutional Neural Network which was fine tuned with these hyper parameters;

* Regularisation
* Batch normalization
* Convolution and pooling layers.
* Augmentation.

In this repository, I attach a full python script that accurately performed the recognition & classification task with an accuracy of over 97% measured using two classification approaches;

* confussin matrix.
* Precision, recall and F1 Score.
![Precision](precision.JPG)<br>
![Precision](recall.JPG)

### Requirements:
* Run in colab with a GPU enabled.
* The algorithm can also be run in a Jupyter notebook.
