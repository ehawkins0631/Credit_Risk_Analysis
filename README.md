Credit Risk Analysis

Supervised Machine Learning and Credit Risk

Overview of the loan prediction risk analysis:

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:


* Imbalanced-learn
* Scikit-learn
* RandomOverSampler
* SMOTE algorithms
* ClusterCentroids algorithm
* SMOTEENN algorithm
* BalancedRandomForestClassifier (bias reduction model)
* EasyEnsembleClassifier (bias reduction model)

Purpose:

* Explain how a machine learning algorithm is used in data analytics.
* Create training and test groups from a given data set.
* Implement the logistic regression, decision tree, random forest, and Support Vector Machine algorithms.
* Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
* Compare the advantages and disadvantages of each supervised learning algorithm.
* Determine which Supervised Learning algorithm is best used for a given data set.
* Use ensemble and resampling techniques to improve model performance.

Results:


The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:
Naive Random Oversampling

Figure 1:

![image](https://user-images.githubusercontent.com/101227930/183818055-9a5bbf61-b076-4db4-bf22-f9006cd178cb.png)


Balanced Accuracy: 
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = 0.71/0.60
SMOTE Oversampling


Figure 2:

![image](https://user-images.githubusercontent.com/101227930/183818080-bc6d6a1f-2abf-45d3-96b0-e296e7947409.png)


Balanced Accuracy: 
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = 0.60/0.71
Undersampling

Figure 3:

![image](https://user-images.githubusercontent.com/101227930/183818117-a0b0b9f9-0cc7-47c9-a793-e650f9e3653e.png)


Balanced Accuracy: 
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = 0.69/0.40
Combination Under-Over Sampling


Figure 4:

![image](https://user-images.githubusercontent.com/101227930/183818162-b333fa3b-db81-4d2d-9b3d-5710136a1634.png)


Balanced Accuracy: 
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = 0.78/0.58
Balanced Random Forest Classifier



Figure 5:

![image](https://user-images.githubusercontent.com/101227930/183818211-a591995b-b94e-40d3-98ba-19abd139e780.png)


Balanced Accuracy: 
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk =0.36/1.0
Easy Ensemble AdaBoost Classifier



Figure 6:

![image](https://user-images.githubusercontent.com/101227930/183818251-55067370-7577-43e5-bc5c-1962c81b8a50.png)

Balanced Accuracy: 
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = 0.36/1.0



Summary:

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best Machine Learning Model to choose for further credit card analysis.


email:  ehawkins0631@gmail.com

twitter: @evahawkins0630

https://www.linkedin.com/in/eva-hawkins-a9b333147/

