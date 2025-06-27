# Breast Cancer Prediction using Logistic Regression

This project demonstrates how to build a binary classification model using Logistic Regression. The goal is to predict whether a breast tumor is malignant or benign based on features in the Breast Cancer Wisconsin dataset from Kaggle.
## Project Tasks
1. **Load and Prepare the Dataset**  
   - Loaded the dataset and dropped unnecessary columns  
   - Encoded the target variable (`diagnosis`) as 0 (Benign) and 1 (Malignant)  
   - Selected the top 10 most informative features for modeling  
2. **Split Data into Train-Test Sets**  
   - Split the data into 80% training and 20% testing sets  
   - Standardized the feature values using `StandardScaler`  
3. **Fit a Logistic Regression Model**  
   - Trained the model using `sklearn.linear_model.LogisticRegression`  
   - Predicted labels and probabilities for the test data  
4. **Evaluate the Model**  
   - Evaluated performance using confusion matrix, precision, recall, and ROC-AUC score  
   - Generated classification report and visualized the ROC curve  
5. **Tune Threshold and Explain Sigmoid Function**  
   - Adjusted classification threshold to study its effect on precision and recall  
   - Explained how logistic regression uses the sigmoid function to output probabilities  
## Tools Used
- Python  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
## Conclusion
The logistic regression model achieved high accuracy and excellent ROC-AUC performance. It successfully distinguishes between benign and malignant tumors and demonstrates the effectiveness of logistic regression in binary medical classification tasks.
