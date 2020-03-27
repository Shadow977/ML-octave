# ML-octave
 This Repository contains the solution to programming assignments of course "Machine Learning" by Stanford University on Coursera

All the codes are done in Ocatve-5.2.0

Installation instructions:

1. First open terminal (Ctrl+Alt+T) and make sure Flatpak support is enabled by running command:

      sudo apt-get install flatpak
      
2. Then add the Flathub repository, the best place to get Flatpak apps:

     flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

3. Finally install GNU Octave 4.4 from the Flathub repository:

    flatpak install flathub org.octave.Octave


Exercise-1

    Linear Regression: Cost function, gradient descent for one variable and multi variables, feature normalization
    Normal equations

Exercise-2

    Logistic Regression: Sigmoid function, cost function and gradient, learning parameters using fminunc, regulariztion.

Exercise-3

    Multi-class CLassification: Regularized logistic regression with cost function and gradient, one-vs-all classification, one-vs-all prediction.
    Neural Networks: Feedforward propagation and prediction.

Exercise-4

    Neural Networks Learning (Hand-written digit recognition): Feedforward and regularized cost function, backpropagation including sigmoid gradient and random initialization, gradient checking, learning parameters using fmincg, visualizing the hidden layer.

Exercise-5

    Regularized Linear Regression: Regularized linear regression cost function and gradient.
    Bias v.s. Variance: Learning curves.
    Polynomial regression: Learning polynomial regression, selecting λ using a cross validation set, computing test set error and plotting learning curves with randomly selected examples.

Exercise-6

    Support Vector Machines: Linear classification, non-linear clasification using Gaussian Kernel.
    Spam Classification: Preprocessing emails, extracting features from emails using vocabulary list, training SVM for Spam Classification and predicting emails as spam or non-spam.

Exercise-7

    K-means Clustering: Finding closest centroids, computing centroid means, random initialization.
    Image Compression with K-means: K-means on pixels.
    Principal Component Analysis: Implementing PCA.
    Dimensionality Reduction with PCA: Projecting the data onto the principal components, reconstructing an approximation of the data, run PCA on Face Image Dataset and reduces dimensions.

Exercise-8

    Anomaly Detection: Estimating parameters for a Gaussian distribution, selecting the threshold 'ε' using cross-validation dataset.
    Recommender Systems (Movie Rating): Collaborative filtering learning algorithm- cost function and gradient with regularization, learning movie recommendations using fmincg.
