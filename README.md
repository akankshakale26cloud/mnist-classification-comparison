**MNIST Digit Classification Comparison**
This repository presents a comparative study of several machine learning models applied to the classification of MNIST handwritten digits. 
The models include Logistic Regression, Multi-class Logistic Regression, and Support Vector Machines (SVM), with detailed performance evaluations.

##Overview
The project explores the following algorithms:

**Logistic Regression optimized via Gradient Descent**

**Multi-class Logistic Regression**

**Support Vector Machines (SVM) using both Linear and RBF kernels**

The objective is to assess and compare the models’ accuracy on training, validation, and test datasets, along with a per-class performance analysis.

##Performance Summary
Logistic Regression (Gradient Descent)
Training Accuracy: 92.67%

Validation Accuracy: 91.45%

Testing Accuracy: 91.99%

##Multi-class Logistic Regression
Training Accuracy: 93.45%

Validation Accuracy: 92.47%

Testing Accuracy: 92.55%

##Support Vector Machines
Model	                  Training Accuracy	    Validation Accuracy	    Testing Accuracy
Linear SVM	            97.18%	              93.68%	                93.80%
RBF SVM (gamma = 1)	    100%                	15.48%	                17.14%
RBF SVM (default gamma)	98.96%	              97.86%	                97.89%

##Insights
Multi-class Logistic Regression slightly outperforms the One-vs-All Logistic Regression approach.

Linear SVM demonstrates strong generalization, reflected in high validation and test accuracies.

RBF SVM with the default gamma value achieves the best overall balance between training and testing performance.

RBF SVM configured with gamma = 1 shows clear signs of overfitting, leading to poor validation and test results.

##Dataset Details
Utilizes the MNIST handwritten digit dataset.

Data preprocessing includes feature selection and normalization.

Dataset is divided into training, validation, and test subsets for evaluation.
