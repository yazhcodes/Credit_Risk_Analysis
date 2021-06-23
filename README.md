# Credit Risk Analysis

## Overview: 
   The purpose of this project is to build a Machine Learning Model to predict the credit risk of Loan Applications. A wide variety of models were built and their performance parameters like accuracy, precision, recall and f1-score were compared to pick the best model that serves the purpose.

## Results: 
  Here's a comparison of how well the different models fared in predicting Low Risk and High Risk Loan Applications.
<p align='center'>
<img src='https://github.com/yazhcodes/Credit_Risk_Analysis/blob/main/Resources/Images/Performance%20Chart.png' height=250 width=1000></img> 
<br>
<img src='https://github.com/yazhcodes/Credit_Risk_Analysis/blob/main/Resources/Images/High%20Risk%20Loans.png' height=350 width=400></img> 
<img src='https://github.com/yazhcodes/Credit_Risk_Analysis/blob/main/Resources/Images/Low%20Risk%20Loans.png' height=350 width=400></img>
</p>

## Summary: 
   It is evident that Easy Ensemble Classifier is the best model with the best accuracy, precision, recall and f1-score. So we are picking it as our obvious choice as the most efficient model.
   However, we should be wary that the Easy Ensemble Classifier has a very low precision of 9% for High Risk Loans, although it is much better than the precision offered by the other models. This means that we are picking a model that it is highly prone to predict False Positives for High Risk Loans. In other words, if the model predicts a Loan as High Risk, there is only a 9% probability that it is actually a High Risk Loan and there is a 91% chance that it is actually a Low Risk Loan which is falsely identified as High Risk.
