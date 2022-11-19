# Computer-Vision-Algorithms
 Some Computer Vision algorithms for comparison and learning purposes.
 
 You can check de algorithms and the results on each of the jupyter notebooks.
 
 - 1st: I created a basic image recognition model using **SVM and PCA**. To test this model I used the dataset "Labeled Faces in the Wild Home" which can be seen on http://vis-www.cs.umass.edu/lfw/. I got 84% of accuracy on test.
 
 - 2nd: I created a deep learning model using Keras and Tensorflow with 2 dense layers using Relu activation and the output layer with Softmax function. The loss function was sparse_categorical_crossentropy and the optimzer was SGD. For 50 epochs I got 88.77% accuracy on test.
 
 ![image](https://user-images.githubusercontent.com/69984472/202846301-7de9c668-ae82-4a02-a7e4-153d70979f6a.png)
 
 - 3rd: I created a convolutional neural network model using PyTorch and training on GPU.The parameters and explanations can be seen on the jupyter. For 30 epochs I got 72% of accuracy on test, training more epochs would definetly get better results.

