**Summary of Modeling approach**

Below are the key findings and insights gained from this exercise:

**Problem**: We have to predict the likelihood of a borrower defaulting on a loan using a machine learning model based on variety of factors given. This is an imbalanced dataset, hence the ML approach taken here is to build a robust model which is fully compatible with imbalanced dataset.

**Approach**: When dealing with imbalanced data, such as our loan default classification task with a majority of "not default" instances, I have used ensemble methods like gradient boosting algorithms - LightGBM and XGBoost which are robust to imbalance datasets. We have used another technique like Synthetic Minority Over-sampling Technique (SMOTE) to generate synthetic examples of the minority class and compared the results at the end.

**Evaluation Metric**: Accuracy is not an appropriate metric for imbalanced data. Instead, we have consider metrics as F1-score, and area under the ROC curve (AUC-ROC) that provide a more comprehensive evaluation of model performance on both classes. 

**Limitations and future directions**: As potential future enhancements, these models can be fine-tuned further by employing further feature engineering and hyper parameter optimization techniques. They can also be trained for longer EVALS and more Stratified Cross validation splits. Also, incorporating additional public/private data sources, exploring alternative algorithms, or refining the existing models will be a good idea.

**Conclusion**: LightGBM model worked well as compared to XGBoost and SMOTE in terms of training time and AUC-ROC score.

![image](https://github.com/akashmathur-2212/Loan-Default-Prediction/assets/63149422/23b004d4-8c62-4846-b8a2-87f804c7ecc5)

![image](https://github.com/akashmathur-2212/Loan-Default-Prediction/assets/63149422/ac658333-6a14-42a5-a113-3595a0152260)

![image](https://github.com/akashmathur-2212/Loan-Default-Prediction/assets/63149422/a65611b0-7eeb-4dfe-8b3c-94c435708ddf)

![image](https://github.com/akashmathur-2212/Loan-Default-Prediction/assets/63149422/7290531b-d24d-419b-9291-2ac9b143d3bb)

![image](https://github.com/akashmathur-2212/Loan-Default-Prediction/assets/63149422/7b0b48cd-eb81-4405-ac64-82048dcb8e00)

![image](https://github.com/akashmathur-2212/Loan-Default-Prediction/assets/63149422/a5486453-1a57-4a24-9819-4554c0e6f028)



