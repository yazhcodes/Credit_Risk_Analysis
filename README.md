# Credit Risk Analysis

## Overview: 
   The purpose of this project is to build a Machine Learning Model to **Predict the Credit Risk of Loan Applications**. A wide variety of models are built and their performance parameters like accuracy, precision, recall and f1-score are compared to pick the best model that serves the purpose.

## Results: 
  Here's a comparison of how well the different models fared in predicting Low Risk and High Risk Loan Applications.
<p align='center'>
<img src='https://github.com/yazhcodes/Credit_Risk_Analysis/blob/main/Resources/Images/Performance%20Chart.png' height=250 width=1000></img> 
<br><br>
<img src='https://github.com/yazhcodes/Credit_Risk_Analysis/blob/main/Resources/Images/High%20Risk%20Loans.png' height=350 width=450></img>       
<img src='https://github.com/yazhcodes/Credit_Risk_Analysis/blob/main/Resources/Images/Low%20Risk%20Loans.png' height=350 width=450></img>
</p>

## Summary: 
   It is evident that **_Easy Ensemble Classifier_** is the most efficient model with the best accuracy, precision, recall and f1-score.
   
   However, we should be wary about the 9% precision it offers for High Risk Loans, although it is much better than the precision offered by the other models. This means that we are picking a model that is highly prone to predict False Positives of High Risk category. 
   
   In other words, if the Easy Ensemble Classifier model identifies a Loan as High Risk, there is only a 9% probability that it is actually a High Risk Loan and there is a 91% chance that it is actually a Low Risk Loan which is falsely flagged as High Risk.
