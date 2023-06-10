# Brain-Tumor-Detection

Link of dataset:- https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection

## Overview
Brain Tumor Detection is a project that focuses on the identification and classification of brain tumors using image processing and machine learning techniques. It utilizes a combination of image resizing, feature extraction algorithms (HoG, SIFT, ORB), thresholding, connected component analysis, and PCA for dimensionality reduction. The project employs a variety of machine learning algorithms including Support Vector Machines (SVM) with different kernel functions (linear, poly, sigmoid), Gaussian Naive Bayes, Logistic Regression with various solvers (lbfgs, liblinear, newton-cg), and k-Nearest Neighbors (KNN) with k values ranging from 1 to 5. Additionally, deep learning architectures such as VGG16, VGG19, and Inception V3 are used to enhance the detection accuracy. The performance of the machine learning algorithms is evaluated using k-fold cross-validation with k set to 3, ensuring reliable and robust model assessment.





## Outputs:-
### Deep Learning:- Best Architecture = Inception V3
#### VGG 16
accuracy: 0.9317
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/5e633651-3dab-4e6c-8272-116f67b266e8)

#### VGG 19
accuracy: 0.9516666531562805
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/67b2e339-f026-43d7-a65e-1111ee4da09d)

#### Inception V3
accuracy: 0.9733333587646484![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/d2dc8011-dc36-46eb-a09c-d443e7fd45f6)

Combined Training and Validation accuracy of above 3 architectures
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/df807b58-4c5c-49fb-9cae-a024cf190a15)


### Machine Learning:- Best Algorithm = Logistic Regression with solver as lbfds give an accuracy of 95.26666667
Combined outputs of all machine learning algorithms
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/ebb5a5ea-2443-42d6-9a0e-97cf09c65dff)
