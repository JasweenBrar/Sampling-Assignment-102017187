# Sampling-Assignment-102017187

🌸 **Name: Jasween Kaur Brar**

🌸 **Roll No: 102017187**

🌸 **Sub-Group: 3CS8**

## 💠 What's in this assignment ?
* Solution of Sampling Assignment of Course UCS654.
* Dataset: Credit Card Fraud Detection
* Used various techniques to balance dataset. 
* Applied different sampling techniques on different ML models.
* Find out which combination of sampling and model has highest accuracy

## 💠 TASKS Performed:

### ⭐ TASK-1 -> Download dataset and convert it into balanced dataset

  * The dataset is highly imbalanced as it contains 763 rows of Class 0 and only 9 rows of Class 1
  * So,I used SMOTE oversampling to balance the dataset
 
### ⭐ TASK-2 -> Create 5 samples(Using sample size detection formula) & 5 Different sampling techniques
  **Techniques Used**
  * Sampling 1 = Simple Random Sampling
  * Sampling 2 = Stratified Sampling
  * Sampling 3 = Cluster Sampling
  * Sampling 4 = Systematic Sampling
  * Sampling 5 = Multi-Stage Sampling

### ⭐ TASK-3 -> Train all 5 samples using 5 different ML Models
  **Models Used**
  * M1 = Decision Tree 
  * M2 = Logistic Regression
  * M3 = Gaussian Naive Bayes
  * M4 = Gradient Boosting Classifier
  * M5 = Random Forest Classifier

### ⭐ TASK-4 -> Find out accuracy score of sampling technique with respective ML model
  **Output Table**

  |  | Sampling 1 | Sampling 2 | Sampling 3 | Sampling 4 | Sampling 5 |
  | --- | --- | --- | --- | --- | --- |
  | M1 = Decision Tree | 0.935065 | 0.967532 | 0.913462 | 0.887097 | 0.961039 |
  | M2 = Logistic Regression | 0.896104 | 0.915584 | 0.913462 | 0.741935 | 0.974026 |
  | M3 = Gaussian Naive Bayes | 0.883117 | 0.850649 | 0.894231 | 0.790323 | 0.818182 |
  | M4 = Gradient Boosting Classifier | 0.961039 | 0.987013 | 0.951923 | 0.935484 | 0.974026 |
  | M5 = Random Forest Classifier | 0.974026 | 0.993506 | 0.980769 | 0.983871 | 0.987013 |

### ⭐ TASK-5 -> Observe: Which sampling technique gives highest accuracy on which model?

  |  | Best ML Model |
  | --- | --- |
  | Sampling 1 = Simple Random Sampling | Random Forest Classifier |
  | Sampling 2 = Stratified Sampling | Random Forest Classifier |
  | Sampling 3 = Cluster Sampling | Random Forest Classifier |
  | Sampling 4 = Systematic Sampling | Random Forest Classifier |
  | Sampling 5 = Multi-Stage Sampling | Random Forest Classifier |
 
 :smile: **We observe that we get best accuracy when we use Stratified Sampling on Random Forest Classifier**

 ## 💠 Learnings:

 🌿 Learnt how to balance imbalanced dataset

 🌿 How to calculate size of sample for a given sampling techniques

 🌿 Explored about 5 different sampling techniques

 🌿 Applied various ML Models to observe when we get best result
