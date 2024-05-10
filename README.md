# Heart_Disease_Predictor
## Data Description
1. S.No. Attribute Code given Unit Data type 
2. age -> in years -> Numeric 
3. sex -> (1,0) -> Binary
4. chest pain type -> 1,2,3,4 -> Nominal
5. resting bp s -> mm Hg -> Numeric
6. cholesterol -> mg/dl -> Numeric
7. fasting blood sugar -> 1,0 > 120 mg/dl -> Binary
8. resting ecg -> 0,1,2 -> Nominal
9. max heart rate -> 71–202 -> Numeric
10. exercise angina ->  0,1 -> Binary
11. ST oldpeak -> depression -> Numeric
12. ST slope -> 0,1,2 -> Nominal
13. target -> 0,1 -> Binary

The goal of this project is to develop a machine learning algorithm that accurately predicts the chances of suffering from a heart disease. Given above are the features mentioned in the dataset

I developed a Logistic Regression, Random Forest and Gradient Boosting model and compared the recall of every model to decide which model is ideal in predicting heart disease suffrage

I also developed a few visualizations as an initial exploratory data analysis. The dataset was taken from Kaggle. Python was used for data visualization model building and testing. I used the sklearn library to split the dataset into training and testing sets , the ML Model libraries like RandomForestClassifier(), GradientBoostingClassifier() and LogisticRegression() to build the models. From sklearn.metrics, I utilized auc_score, precision, recall, classification report and confusion matrix to estimate/quantify model performance
