# Optional project for Machine Learning Course
This project is about `churn prediction`.
### Data Source 
Dataset is given by the professor of `Intro to Data Science` Course.
### What we do in this project
We seperated the whole project into several different parts, like 'Preprocessing' 'feature extraction' 'feature selection' 'estimation' and 'postprocessing'. When we focused on this `churn prediction` topic, we abandoned 'feature extraction' and 'postprocessing' in that they were not suitable for this problem.<br> 
<br> 
In the 'preprocessing' part, since this pronblem is a binary classificatoin problem, we checked whether the distribution of labels is balanced or not at first. Then the distribution of several features were showed out just for visualization. After that we chose 'LabelEncoder()' to transform the categorical values. For numerical values we used 'mean' to fillna.<br> 
<br> 
In the 'feature selection' part, we used PCA to find out the principle components to avoid overfitting caused by using all features.<br>
<br> 
In the 'estimation' part, we tryed several models such as 'Logistic Regrssion' 'Randomforest Classifier' and 'XGBClassifier'. What's more, 'GridSearchCV' and 'K Fold Cross Validation' were also implemented.<br> 
<br> 
It turned out that we could achieve the best perfomance via 'Randomforest Classifier'. Because it handles categorical data as is and naturally captures non-linearity and interactions. And the overfitting can be alleviated by ensembled methods at the same time. <br> 
<br> 
