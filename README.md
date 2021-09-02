# Credit_Risk_Analysis
## Overview of Project
### Background

The client asked for a credit card risk analysis. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. The client asked for different techniques to train and evaluate models with unbalanced classes.

### Purpose

The purpose of this project is to analyze credit card risk.

## Results

Image 1 shows the Naive Random Oversampling results:
- Balanced Accuracy Score: 65.13%
- Precision Score - High Risk: 0.01
- Precision Score - Low Risk: 1.00
- Recall Score- High Risk: 0.67 
- Recall Score- Low Risk: 0.64

*Image 1: Naive Random Oversampling*

![Naive random oversampling](https://user-images.githubusercontent.com/78306719/121437074-4c021d00-c947-11eb-995e-42f939ac6680.PNG)

Image 2 Shows the SMOTE Oversampling results:
- Balanced Accuracy Score: 62.66%
- Precision Score - High Risk: 0.01
- Precision Score - Low Risk: 1.00
- Recall Score- High Risk: 0.61
- Recall Score- Low Risk: 0.64

*Image 2: SMOTE Oversampling*

![SMOTE Oversampling](https://user-images.githubusercontent.com/78306719/121437167-76ec7100-c947-11eb-8920-8369498a22b9.PNG)

Image 3 shows the Undersampling results:
- Balanced Accuracy Score: 65.13%
- Precision Score - High Risk: 0.01
- Precision Score - Low Risk: 1.00
- Recall Score- High Risk: 0.60
- Recall Score- Low Risk: 0.43

*Image 3: Undersampling*

![Undersampling](https://user-images.githubusercontent.com/78306719/121437209-879ce700-c947-11eb-8b5b-2e7f3931aded.PNG)

Image 4 shows the Combination results:
- Balanced Accuracy Score: 65.13%
- Precision Score - High Risk: 0.01
- Precision Score - Low Risk: 1.00
- Recall Score- High Risk: 0.70
- Recall Score- Low Risk: 0.67

*Image 4: Combination*

![Combination](https://user-images.githubusercontent.com/78306719/121437306-ae5b1d80-c947-11eb-820d-ec7bffbf36fa.PNG)

Image 5 shows the Balanced Ramble Forest Classifier results:
- Balanced Accuracy Score: 78.77%
- Precision Score - High Risk: 0.04
- Precision Score - Low Risk: 1.00
- Recall Score- High Risk: 0.67
- Recall Score- Low Risk: 0.91

*Image 5: Balanced Ramble Forest Classifier*

![Balanced Ramble Forest Classifier](https://user-images.githubusercontent.com/78306719/121437349-c7fc6500-c947-11eb-8d51-2d06427a4d71.PNG)

Image 6 shows the Easy Ensembled Adaboost results:
- Balanced Accuracy Score: 92.54%
- Precision Score - High Risk: 0.07
- Precision Score - Low Risk: 1.00
- Recall Score- High Risk: 0.91
- Recall Score- Low Risk: 0.94

*Image 6: Easy Ensembled Adaboost*

![Easy Ensembled Adaboost](https://user-images.githubusercontent.com/78306719/121437432-f24e2280-c947-11eb-9f2f-f93f6ec09226.PNG)

## Summary

The results show that the Easy Ensembled Adaboost is the most effective method with a 92.54% balanced accuracy score while the SMOTE Ovversampling is the list effective at 62.66%. It is recommended for the client to use the  Easy Ensembled Adaboost technique to determine credit card risk.
