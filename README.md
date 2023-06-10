# Brain-Tumor-Detection

Link of dataset:- https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection

Link of jupyter notebook containing code and outputs of implementation of ml and dl:- https://github.com/premanshsharma/Brain-Tumor-Detection/blob/main/Brain_Tumor_Detection_Latest.ipynb
Link of jupyter notebook containing code and outputs of image processing functions:- 
https://github.com/premanshsharma/Brain-Tumor-Detection/blob/main/BrainTumorPreImgProcessing.ipynb
## Overview
Brain Tumor Detection is a project that focuses on the identification and classification of brain tumors using image processing and machine learning techniques. It utilizes a combination of image resizing, feature extraction algorithms (HoG, SIFT, ORB), thresholding, connected component analysis, and PCA for dimensionality reduction. The project employs a variety of machine learning algorithms including Support Vector Machines (SVM) with different kernel functions (linear, poly, sigmoid), Gaussian Naive Bayes, Logistic Regression with various solvers (lbfgs, liblinear, newton-cg), and k-Nearest Neighbors (KNN) with k values ranging from 1 to 5. Additionally, deep learning architectures such as VGG16, VGG19, and Inception V3 are used to enhance the detection accuracy. The performance of the machine learning algorithms is evaluated using k-fold cross-validation with k set to 3, ensuring reliable and robust model assessment.

## Image Feature Extraction Outputs
### Normal image containing tumor
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/82e57b53-89c0-44db-a643-87d713a19f6c)
### HOG Image
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/5482a058-d3fa-4eff-ac42-702aa1d64259)
### SIFT Image
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/5a8a7e67-4284-43ba-b344-a1f274a13031)
### ORB Image
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/586920af-f1aa-45ab-bf70-befea97847f7)
### Image after Thresholding
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/e6f10e5f-68d1-4b54-bfbf-18578d00ea13)
### Connected Component Analysis
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/079a28fa-c14b-43a6-b338-007ed707b3ac)
### Image after PCA
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/92cfb34b-4047-4e1d-a489-7fcacb26ff75)


## Machine learning and Deep Learning algorithm Outputs:-
### Deep Learning:- Best Architecture = Inception V3 with an accuracy of 0.9733333587646484
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
#### Combined outputs of all machine learning algorithms
![image](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/ebb5a5ea-2443-42d6-9a0e-97cf09c65dff)

#### Detailed Outputs
##### Normal Image
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/82b5ce41-8a68-4afa-8832-5af7eba6e442)
###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/011ab180-ec34-4c97-9b6c-d97db4f1e5c2)
###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/9fec6c4f-108a-4c29-92f9-7789a8af78e3)
###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/197ab95c-d22a-4552-baad-a4152551075b)

##### Normal Image with HOG
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/b3e1aa37-294b-40ff-a613-d55f66b8f8ce)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/c912b28a-f2a2-4cbf-84b8-d8440f4b9098)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/c6d7d305-1023-4c4b-baa2-6328d9455c4c)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/fff18565-681f-4946-bc41-b2d1b87423b8)


##### Normal Image with SIFT
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/cd58520b-ff8d-46fc-ae4e-14e7308f954c)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/0829b726-8bbb-405c-b9ff-0a3f8ac92797)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/fc778971-93b8-48ab-845e-2ec02bf0ae8c)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/05df5cff-11d8-44ab-8f6d-133e687a4afc)

##### Normal Image with ORB
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/7f802e14-ee73-4f8a-b93f-aada35619b80)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/61f00714-aacb-4e65-a242-0753eccfe2c0)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/21d6a528-c9df-487f-8163-adcb4a28cd2c)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/a25329aa-27b9-40c0-9a62-3b757776efb2)

##### Normal Image with HOG+SIFT
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/f78a56c5-db96-4368-813d-593d8c67c734)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/90615a9e-b287-411d-9ff5-4ac01a68e8ee)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/933cae7d-051c-4a19-b4c8-734f073dcc0e)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/711f3db6-ac75-4e92-adec-e97bc757d1cf)

##### Normal Image with SIFT+ORB
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/d1fb7ee1-3eff-44d8-ab34-1c0af0202be7)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/10d923e6-83b2-48c4-9a2d-b187118471d3)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/e9a8364e-0fa4-474f-b9a8-d25989951df6)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/20ff180b-b463-4642-b5ad-7c6074e0b45d)

##### Normal Image with HOG+ORB
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/2972125d-63f2-4761-8918-b6f9397e8764)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/4ac5efc8-1e3a-4421-a0bc-177cadb5e898)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/5d497807-da07-4b62-b054-0651ad8fc34c)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/f8af46a0-b322-4eba-ae88-e94fefda206f)

##### Normal Image with HOG+SIFT+ORB
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/ca66149a-871e-49ad-b5bc-f8f5f0a5be2e)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/d30dd116-0999-4a39-9014-bde33a1d22e6)


##### Normal Image with THRESHOLDING
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/7c1c20d5-6ae3-4eee-a5a6-05a2c55e79eb)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/d26b258f-600b-411c-a341-833e9b0ef29a)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/7452a518-0c32-4dbf-9a9f-1071fadf505d)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/0644b9af-8478-4570-9359-91c6a29bbf9a)

##### Normal Image with CONNECTED COMPONENT ANALYSIS
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/56962ccf-b346-481a-a746-e7d6d5d94471)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/1f166c16-d1c4-4755-97cb-b57a63ffeee8)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/ad90ff9d-7281-4383-ac34-5e48790beb4d)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/43b16e4f-6de6-4e44-9966-00775ed3cbbe)

##### Normal Image + PCA
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/e042ace4-8ee4-4aae-8230-ee71c69c92bb)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/e03572df-5cfe-4c79-aaf2-7a626b7fb76a)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/862c9839-6590-450d-877b-fa78b3c48bcd)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/c98305d6-fb8f-49d1-8643-ffb3263d7d02)

##### Normal Image + PCA + Connected Component Analysis
###### kNN
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/d6c54269-6483-404f-9bdb-fb886aad6703)

###### SVM
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/19a2e686-7ef3-43aa-acce-8d8ad920388b)

###### Naive Bayes
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/dfc56968-3e39-4b0b-85a0-65f5bd98b7f2)

###### Logistic Regression
![download](https://github.com/premanshsharma/Brain-Tumor-Detection/assets/71265310/db683fea-174a-4eff-bc7f-cb677e4349ac)
