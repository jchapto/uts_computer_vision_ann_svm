# uts_computer_vision_ann_svm

This is a comparative study of the performance of 2 classifiers (ANN and SVM) and 3 different types of features (HOG, LBP and Raw inputs), when solving a multi-class classification problem. The following definitions briefly describe the classifiers and features used:
ANN (Artificial Neural Networks): Artificial Neural Networks (ANN) are multi-layered fully-connected neural networks. They have an input layer, multiple hidden layers and an output layer.
SVM (Support Vector Machine): Machine learning algorithm that finds a hyperplane in an N-dimensional space that classifies data points.
HOG (Histogram of Oriented Gradient): Method of extracting features that measures directional change in the intensity or colour in an image.
LBP (Local Binary Pattern): A powerful feature for texture classification, which labels each pixel of an image by thresholding their neighbours.
Raw inputs: Consists of using the individual pixels of an image as features.
Each classifier will be tested with the three different kinds of features. This is to say, both ANN and SVM will be tested using HOG, LBP and raw inputs. All other things will remain constant, in order to successfully compare the performance of each classifier and feature type.
