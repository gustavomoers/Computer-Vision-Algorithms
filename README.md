# Computer-Vision-Algorithms
 Some Computer Vision algorithms for comparison and learning purposes.
 
 You can check de algorithms and the results on each of the jupyter notebooks.
 
 - 1st: Basic image recognition model using **SVM and PCA**. To test this model the dataset "Labeled Faces in the Wild Home" was used, which can be seen on http://vis-www.cs.umass.edu/lfw/. Got 84% of accuracy on test.
 
 - 2nd: Deep learning model using Keras and Tensorflow with 2 dense layers using Relu activation and the output layer with Softmax function. The loss function was sparse_categorical_crossentropy and the optimzer was SGD. For test this model the Fashon MNIST dataset was used. For 50 epochs got 88.77% accuracy on test.
 
 ![image](https://user-images.githubusercontent.com/69984472/202846301-7de9c668-ae82-4a02-a7e4-153d70979f6a.png)
 
 - 3rd: Convolutional neural network model using PyTorch and training on GPU.The parameters and explanations can be seen on the jupyter. For test this model CIFAR-10 dataset was used. For 30 epochs got 72% of accuracy on test, training more epochs would definetly get better results.

