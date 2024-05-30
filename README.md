# Credit Risk Resampling 

---

![](./Resources/Loan.png)

---

**Background** In this project, I'll use various techniques to train and evaluate a model based on loan risk. I'll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

I will be using Machine Learning models that include Logistic Regression, Balanced Random Forest, and a variety of resampling techniques such as Oversampling to resample the data. Evaluation metrics like the accuracy score, precision score, and recall score are generated to compare models and determine which suits this particular set of data best.

---

## Credit Risk Analysis Report

---

**Analysis Purpose**

The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the creditworthiness of potential borrowers from peer-to-peer lending services. 

**Description of Machine Learning Model**

- Accuracy Score: "95.20%" Meaning we are taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model. 
- Precision Score: "92%" Meaning the predicted positives were 92 percent correct.
- Recall Score: "95%" Meaning the model was 95 percent precise in measuring the true positive values of the predictions made.

---

## Summary 

---

In this model, we determined which model is best at predicting which loans pose the highest risk. In the next two models, we resampled the data using ensemble classifiers to attempt to predict the risk levels of loans. I would recommend using this model to predict the creditworthiness of borrowers because it achieves over 95% accuracy in predicting the repayment outcome of the initial loan. Such accuracy can be seamlessly integrated into a business risk profile to ensure adequate capital flow for lenders to sustain profitability and remain in business.
