## **Project Name**: Machine Learning-based Classification and Principal Component Analysis of Turkish Dry Bean Varieties  
**Course Name**: Advanced Statistical Approaches to Quality (INSE 6220)

## Abstract
Dry beans are among the most commonly consumed legume crops, with various types cultivated globally. Proper classification of dry beans is crucial for improving crop management and supporting market distribution. In this study, a dataset of 9,954 dry bean samples is used to classify the five most commonly produced and consumed dry bean varieties in Turkey. Initially, Principal Component Analysis (PCA) is applied to reduce the original 16 features to three principal components. Several machine learning models are then tested on both the original and PCA-transformed datasets, with performance evaluated using accuracy, F1-Score, and other metrics. Light Gradient Boosting Machine, Random Forest Classifier, and Extreme Gradient Boosting demonstrate the highest performance on the original dataset. After applying PCA, Logistic Regression emerges as the top-performing model with an accuracy of 92.15%, followed by Gradient Boosting Classifier at 91.92% and K-Nearest Neighbors at 91.84%. These results demonstrate the models’ capability to accurately distinguish between the dry bean varieties found in Turkey.

## Dataset
The dry beans dataset contains information about dry beans commonly consumed in Turkey and includes over 13,000 samples. It consists of 16 features (12 dimensions and 4 shape form attributes), all extracted from the grains. These were collected using a computer vision system that extracts shape features from images of the beans. The original dataset consists of seven classes and 16 features. For our project, we selected five classes of dry beans that are more widely consumed in Turkey: **BARBUNYA, BOMBAY, DERMASON, HOROZ, and SIRA**. The resulting dataset contains a total of 9,954 observations.

## Experimental Results
**PCA Transformation:** PCA was applied in our dataset to reduce the dimensionality of the dataset from p = 16 to 3 features. The three PCs together account for 89.50% of the total variance in the original dataset. Specifically, the first PC explains 52.23% of the variance (l1 = 52.23%), the second PC explains 28.10% (l2 = 28.10%), and the third PC explains 9.16% (l3 = 9.16%).

**Before Applying PCA:** The top three models with the highest accuracies on the modified dry beans dataset are Light Gradient Boosting Machine (LightGBM) at 93.21%, Random Forest Classifier (RF) at 93.06%, and Extreme Gradient Boosting (XGBoost) at 92.95%.

**After Applying PCA:** The top three models with the highest accuracy on the PCA_transformed dataset are Logistic Regression (LR) at 92.15%, Gradient Boosting Classifier (GBC) at 91.92%, and K-Nearest Neighbors (kNN) at 91.84%.
