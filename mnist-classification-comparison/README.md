# mnist-classification-comparison

Classification of MNIST handwritten digits using Logistic Regression, Multi-class Logistic Regression, and Support Vector Machines, with performance analysis.



\# MNIST Classification with Logistic Regression and SVM



This project implements and compares multiple machine learning algorithms for \*\*MNIST handwritten digit classification\*\*, including:



\- \*\*Logistic Regression with Gradient Descent\*\*

\- \*\*Multi-class Logistic Regression\*\*

\- \*\*Support Vector Machines (SVM)\*\* with Linear and RBF kernels



The goal is to evaluate the performance of these models on training, validation, and testing datasets, and analyze per-class accuracy.



---



\## Results



\### Logistic Regression (Gradient Descent)

\- \*\*Training Accuracy:\*\* 92.67%  

\- \*\*Validation Accuracy:\*\* 91.45%  

\- \*\*Testing Accuracy:\*\* 91.99%



\### Multi-class Logistic Regression

\- \*\*Training Accuracy:\*\* 93.45%  

\- \*\*Validation Accuracy:\*\* 92.47%  

\- \*\*Testing Accuracy:\*\* 92.55%



\### Support Vector Machines

| Model                               | Train Acc | Val Acc  | Test Acc |

|-------------------------------------|-----------|----------|----------|

| Linear SVM                          | 97.18%    | 93.68%   | 93.80%   |

| RBF SVM (gamma = 1)                  | 100%      | 15.48%   | 17.14%   |

| RBF SVM (default gamma)              | 98.96%    | 97.86%   | 97.89%   |



---



\## Key Observations

\- \*\*Multi-class Logistic Regression\*\* slightly outperformed One-vs-All Logistic Regression.

\- \*\*Linear SVM\*\* showed strong generalization with high validation and test accuracy.

\- \*\*RBF SVM with default gamma\*\* achieved the best balance between training and test performance.

\- \*\*RBF SVM with gamma = 1\*\* suffered from severe overfitting.



---



\## Dataset

\- \*\*MNIST\*\* handwritten digit dataset (preprocessed with feature selection \& normalization).

\- Dataset split into Training, Validation, and Testing sets.



---



\## How to Run

1\. Clone this repository:

&nbsp;  ```bash

&nbsp;  git clone https://github.com/<your-username>/<repo-name>.git

&nbsp;  cd <repo-name>



