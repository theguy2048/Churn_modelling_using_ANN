# The Customer Churn
In this project "The customer churn", also known as customer attrition, refers to the phenomenon whereby a customer leaves a company. Some studies confirmed that acquiring new customers can cost five times more than satisfying and retaining existing customers. As a matter of fact, there are a lot of benefits that encourage the tracking of the customer churn rate, for example:

Marketing costs to acquire new customers are high. Therefore, it is important to retain customers so that the initial investment is not wasted;
It has a direct impact on the ability to expand the company;

In this project our goal is to predict the probability of a customer is likely to churn using machine learning techniques.
To make this project further more interesting I have crated 3 juypter notebook each with there own uniqueness. The churn_modelling_using_ann has been made with an effort to get the required results with fixed hyperparameters and fixed dataset. The k-fold notebook is made with the effort that sometimes deep learning models can perform well for test set and give a different result on other test set. So here i have used k-fold cross validation to make sure that the accuracy is not certain to only one training set rather taking the mean of the accuracy obtained by the k-fold cross validation about which i will discuss more below. In the hyperparameters notebook I have not fixed the parameters here but rather wanted to know which parameter suited more to this dataset and the result can be seen separately.

Talking about the accuracy you can see that the accuracy in churn_modelling_using_ann notebook is highest and that the hyperparameters file where you see that i wanted to find the best parameters to calculate the highest accuracy has its accuracy less than this. Well there can be multiple reasons for the but as I have mentioned above sometimes the model becomes so accurate for a particular test set that it gives a huge accuracy for that one and less for others. Even if you run that file multiple times it is seen that we get different accuracy so that is why I have used k-fold cross validation method which trains on different datasets and gives different accuracies. So i calculated the mean of it and that can be considered as the optimum accuracy of that model also you can see the variance of it. In the last notebook it is evident that if you use the best parameters that I have calculated will be the best accuracy that the model can predict.

### Link for the dataset : https://www.kaggle.com/adammaus/predicting-churn-for-bank-customers
