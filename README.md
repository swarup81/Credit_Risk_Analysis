# Credit_Risk_Analysis

# Overview of the analysis

## Purpose:

In this challenge, we apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an unbalanced classification problem, as good loans easily outnumber risky loans. 
This project aims to train and evaluate models with unbalanced classes.

# Results: 

 Naive Random Oversampling

<img width="477" alt="random" src="https://user-images.githubusercontent.com/100738688/176341473-0115eb9b-0e9e-4792-8848-b0b45cf7692c.png">

<img width="706" alt="random1" src="https://user-images.githubusercontent.com/100738688/176341489-0be4ee43-d36d-4a83-b2be-9a57d349966d.png">


* The balanced accuracy score is 64%.
* The high_risk precision is about 1%, with a sensitivity of 70%.
* The low-risk precision is 100% with 59% of sensitivity.

 SMOTE Oversampling

<img width="365" alt="smote" src="https://user-images.githubusercontent.com/100738688/176341069-fe53af4b-e9e5-41ed-9002-fea5ba3561fa.png">

<img width="711" alt="smote1" src="https://user-images.githubusercontent.com/100738688/176341131-045d9b8e-4843-40e7-aea7-eafbe5e08204.png">


* The balanced accuracy score is 66%.
* The high_risk precision is about 1%, with a sensitivity of 63%.
* The low-risk precision is 100% with 69% of sensitivity.

Cluster Centroid Undersampling

<img width="459" alt="cluster" src="https://user-images.githubusercontent.com/100738688/176341335-be854236-47b1-4d75-a448-8aef12f0808f.png">

<img width="719" alt="cluster1" src="https://user-images.githubusercontent.com/100738688/176341357-2deb0ed8-217c-408f-b3aa-50a8312ad9ee.png">



* The balanced accuracy score is 54%.
* The high_risk precision is about 1%, with a sensitivity of 69%.
* The low-risk precision is 100% with 40% of sensitivity.

SMOTEENN 

<img width="594" alt="smoteenn1" src="https://user-images.githubusercontent.com/100738688/176341398-c0e46262-afb0-472a-a90c-c8f46bf6d67d.png">

<img width="746" alt="smoteenn" src="https://user-images.githubusercontent.com/100738688/176341412-38699695-b272-4f8e-bf95-abaad542eac2.png">



* The balanced accuracy score is 65%.
* The high_risk precision is about 1%, with a sensitivity of 73%.
* The low-risk precision is 100% with 57% of sensitivity.

 BalancedRandomForestClassifier model

<img width="371" alt="Screen Shot 2022-06-28 at 10 11 41 PM" src="https://user-images.githubusercontent.com/100738688/176342150-b615bf07-adae-436e-9dfd-268f0ce2f45a.png">

<img width="739" alt="Screen Shot 2022-06-28 at 10 12 01 PM" src="https://user-images.githubusercontent.com/100738688/176342175-7cf0fecc-07c5-44c7-9417-ebc1512328cb.png">



* The balanced accuracy score is 78%.
* The high_risk precision is about 3%, with a sensitivity of 70%.
* The low-risk precision is 100% with 87% of sensitivity.

EasyEnsembleClassifier model

<img width="388" alt="eea1" src="https://user-images.githubusercontent.com/100738688/176342233-02b365ec-04a4-48af-b267-ce5776306b13.png">

<img width="737" alt="eea" src="https://user-images.githubusercontent.com/100738688/176342245-de254c5d-8f47-484c-9629-9aed9b094980.png">


* The balanced accuracy score is 93%.
* The high_risk precision is about 9%, with a sensitivity of 92%.
* The low-risk precision is 100% with 94% of sensitivity.

# Summary:

In credit risk analysis, all the models show low precision and high sensitivity in determining high credit risk.
Based on the analysis, I recommend  Easy Ensemble AdaBoost Classifier model because it has a 0.93 balanced accuracy score. The balanced accuracy score of 0.93 gives us a better idea of how well the model can predict both classes.
