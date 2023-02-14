# Image Classification README

This Python code is for classifying images using machine learning algorithms. The algorithms used in this code are Random Forest, Support Vector Machines (SVM), and Multi-layer Perceptron (MLP). The code uses the libraries matplotlib, seaborn, pandas, numpy, sklearn, and metrics.

The image data is loaded from the file C:\\Users\\gonza\\AprendizajeMaquina\\Proj-4\\combinedDataOGChar.csv using the pandas library. The data is then split into training and testing sets, with a test size of 0.3 and random state of 1. The class labels are stored in img_Y and the feature set is stored in img_X.

Each of the three machine learning algorithms is trained using the GridSearchCV function from sklearn.model_selection library. This function performs a grid search over specified parameter values for each algorithm, and outputs the best set of parameters for each algorithm. The parameters for each algorithm are specified in a dictionary format.

The best models for each algorithm are then selected based on their mean test accuracy scores and are stored in the variables img_forest_v1, img_forest_v2, img_svc_v1, img_svc_v2, img_mlp_v1, and img_mlp_v2.

Finally, the code outputs a summary of the accuracy scores and parameters of the best models for each algorithm.

Note: This code is intended to be used as a starting point for image classification and can be modified as needed. The performance of the models will depend on the quality of the input data and the specific requirements of the image classification task.
