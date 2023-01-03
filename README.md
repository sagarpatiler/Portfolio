![White Minimalist Corporate Personal Profile LinkedIn Banner](https://user-images.githubusercontent.com/115975748/210289626-9a43d116-95d4-4e02-b0eb-7b23e159e062.png)

## Data Science Project Notebook

### [Project : Mall customers Predictions](https://github.com/sagarpatiler/machine_learning/blob/main/clustering_mall_customers_pyc.ipynb) 
* Dataset had 5 columns ie. CustomerID,Gender,Age,Annual Income (k$),Spending Score (1-100). Dataset was much cleaned.
* Pycaret,Pandas,seaborn,matplotlib libraries were used.
* EDA was performed for preliminary insights.
* K-means clustering model was used for the purpose of clustering problem.
* With the help of elbow plot 4 clusters were chosen.
* Silhoutte score graph was plotted.
* ![combined (1)](https://user-images.githubusercontent.com/115975748/208020818-671d2c79-43bb-4414-ad2d-fb01a07a10cc.jpg)

### [Project : Diabetes Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/health_proj_1_diabetes_prediction.ipynb) 
* Dependent features were Pregnancies,Glucose,BloodPressure,SkinThickness,Insulin,BMI,DiabetesPedigreeFunction,Age .
* Target feature was balanced.
* Standard Scaler was used for scaling purpose.
* Two models were used - Support vector machine and XGBClassifier
  * SVC-
    * Accuracy score of the training data :  0.7866449511400652
    * Accuracy score of the test data :  0.7727272727272727
  * XGBClassifier Model -
    * Accuracy score of the training data :  0.9543973941368078 
    * Accuracy score of the test data :  0.7467532467532467
* Pandas,sklearn,seaborn,matplotlib libraries were used.
* ![combined](https://user-images.githubusercontent.com/115975748/207767068-383517fa-4fd9-4fed-9319-e4d696b9c48b.jpg)

### [Project :Sales Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/Sales_Prediction.ipynb) 
* Created a model that can predict sales with help of XgboostRegressor.
* feature columns were Item_Identifier, Item_Weight, Item_Fat_Content, Item_Visibility,Item_Type, Item_MRP,Outlet_Identifier,Outlet_Establishment_Year, Outlet_Size, Outlet_Location_Type,Outlet_Type, Item_Outlet_Sales
* Missing value treatment with mean value for numerical columns and with mode with categorical columns.
* Used python libraries like Sklearn,pandas,seaborn,matplotlib.pyplot
* Evaluation with the help of R2.
* ![merge_from_ofoct](https://user-images.githubusercontent.com/115975748/207768079-f7716e8f-e94b-4cff-8f2d-75c6730018a6.jpg)


### [Project :Bank Loan Status Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/Banks_1_loan_status_prediction.ipynb) 
* Created a model that can predict loan status with help of XgboostRegressor.
* feature columns selected  were -Gender,Married,Dependents,Education,Self_Employed,ApplicantIncome,CoapplicantIncome,LoanAmount,Loan_Amount_Term,Credit_History,Property_Area, Loan_Status.
* As missing values were less in number just dropped those values.
* Plotting was done with the help of libraries such as seaborn,matplotlib.
* Parameter tuning was done with help of GridSearchCV
* Accuracy was found to be  0.833333
* ![merge_from_ofoct (1)](https://user-images.githubusercontent.com/115975748/207770005-d91022ee-654c-4c52-86c8-be43d03d8e03.jpg)


### [Project :Car Price Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/car_price_prediction_.ipynb) 
* Linear Regression Model was created.
* R squared score  was found to be  0.8833249177813693.
* Dependent features were - Car_Name,Year,Selling_Price,Present_Price,Kms_Driven,Fuel_Type,Seller_Type,Transmission 
* Dataset did not have missing values.
* Libraries such as sklearn,seaborn,matplotlib were used.

### [Project :Gold Price Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/gold_price_prediction.ipynb) 
* RandomForestRegressor Model was used for the purpose of linear regression problem.
* Shape of the data was (2290, 6)
* R squared score  was found to be 0.9872775170838556.
* Dependent features were - SPX,USO,SLV,EUR/USD 
* Libraries such as sklearn,seaborn,matplotlib were used.

### [Project :Diamond Price Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/diamond_price_pred_pyc.ipynb) 
* RandomForestRegressor Model was used for the purpose of linear regression problem.
* Shape of the data was (2290, 6)
* R squared score  was found to be 0.9872775170838556.
* Dependent features were - SPX,USO,SLV,EUR/USD 
* Libraries such as sklearn,seaborn,matplotlib were used.

### [Project :Heart Disease Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/health_proj_2_heart_disease_prediction.ipynb) 
* Logistic Regression Model was used for the purpose of classification problem.
* Age,sex,cholesterol,BMI were some of the important dependent features.
* Accuracy on Test data :  0.819672131147541. 
* Pandas,sklearn,seaborn,matplotlib libraries were used.

### [Project :Breast cancer Prediction](https://github.com/sagarpatiler/machine_learning/blob/main/health_3_breast_cancer_prediction.ipynb) 
* Dataset had 30 dependent features. Dataset was much cleaned.
* EDA was performed for preliminary insights.
* Pandas,sklearn,seaborn,matplotlib libraries were used.
* Xgboost Model was used for the purpose of classification problem.
* Accuracy on test data =  0.973684210526315
* AUC-ROC curve was plotted.
![auc-roc](https://user-images.githubusercontent.com/115975748/207398872-d8e3e525-2c85-4a16-88a8-db30167c8484.jpeg)























