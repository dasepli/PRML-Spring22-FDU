In this assignment, you will use what you have learned to tackle some pratical problems. Fashion MNIST dataset[1] is the MNIST-like fashion product database for image classification you will play with this time. It originally consists of a training set of 60000 examples and a test set of 10000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

To make this task more realistic (and harder:)), we selected 14600 labeled examples from the training set and did a little processing. You have to do this image classifictaion task with our new dataset. Besides, we provide you with the rest of examples (45400 examples) but with no labels, and you can consider how to use it in your experiment if needed.

You have to impletement several standard classification methods in the './fudanPRML' folder:
- K-nearest Neighbor (10 points)
- Decision Tree (15 points, optional)
- Softmax (10 points)
- SVM (15 points, optional)
- Neural Network (20 points)    


and then do your exploration (50 points).

You can only use some basic python libraries in your experiment like numpy, paddle(can not use the paddle.nn), matplotlib and so on. And please write down the version with them in the './requirements.txt' file.

Please MAKE SURE you followed a standard ML process, like do not use the test dataset for choosing hyperparameters.

[1] Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms. Han Xiao, Kashif Rasul, Roland Vollgraf. arXiv: https://arxiv.org/abs/1708.07747, GitHub: https://github.com/zalandoresearch/fashion-mnist
