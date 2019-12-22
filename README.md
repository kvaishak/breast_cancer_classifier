# Breast_cancer_classification  - A Case study
Using the power of Machine learning to train a model, which can accurately classify the tumors as Malignant or Benign.

Model is trained on a dataset which contains around 30 Feature data points grabbed from snapshots of images of Tumor cells, which are collected by a process called as Fine needle Aspirate(FNA Technique). The resulting trained model will have a high degree of accuracy and can be used to accurately predict the class of tumour on the test data set as well as any future genaralized dataset.

### Tools Used
* Jupiter Notebook - for coding and visualizing the data

### Packages used
* Pandas - for Manipulation of data frames
* Numpy - for Statistical analysis
* Matplot - for Data visualization
* Seaburn - for Statistical Data visualization

### Source of Training data-set
* Sklearn Library

### Optimization Techniques used to improve the model
* Data Normalization
* SVM Parameter Optimization(C Param + Gamma Param)- using GridSearchCV

### Accuracy Obtained
After deploying the above mentioned optimization techniques, an accuracy of 97% was obtained, with a classification error only in the Type - 1 Error plane of the Confusion matrix.
