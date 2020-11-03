# Restaurant Reviews Classification
1. This project uses Natural Language Processing and various Classification models to analyze and learn from the dataset consisting of past reviews of a restaurant. These reviews are classified as being positive or negative. The models can then be used to predict if any future review for that restaurant is a positive review or a negative one. 

2. The dataset consists of 1000 rows and 2 columns; where each row is a single review for a particular restaurant. The first column has the review and the second column classifies the review as either 0 or 1, 0 representing negative review and 1 representing positive review.

3. The data analysis for this project followed the following sequential steps:
* Remove punctuations and stop words from each review.    
* Convert all words to lowercase.    
* Created a sparse matrix of the dataset.    
* Divided the dataset into training and testing data.    
* Applied the Classification model.    
* Present the Data Analysis results: Confusion Matrix and Classification Report.    

4. Logistic Regression Classification model performed best in this project and can be used to classify any future reviews for this restaurant as positive or negative.   

5. Listed below are the Confusion Matrix and Classification Report of the various Classification models used in this project, arranged in order of decreasing accuracy:    

## Logistic Regression

**Confusion Matrix**    
![](Figures/logistic_cm.png)

**Classification Report**    
![](Figures/logistic_classification_report.png)

## K Nearest Neighbors Classifier   

**Confusion Matrix**    
![](Figures/knn_cm.png)

**Classification Report**    
![](Figures/knn_classification_report.png)    

## Support Vector Machine    

**Confusion Matrix**    
![](Figures/svm_cm.png)  

**Classification Report**    
![](Figures/svm_classification_report.png)    

## Random Forest    

**Confusion Matrix**    
![](Figures/random_forest_cm.png)  

**Classification Report**    
![](Figures/random_classification_report.png)    

## Kernel SVM    

**Confusion Matrix**    
![](Figures/kernel.png)  

**Classification Report**    
![](Figures/kernel_classification_report.png)    

## Decision Tree    

**Confusion Matrix**    
![](Figures/decision_cm.png)  

**Classification Report**    
![](Figures/decision_classification_report.png)    

## Naive Bayes    

**Confusion Matrix**    
![](Figures/naive_cm.png)  

**Classification Report**    
![](Figures/naive_classification_report.png)
