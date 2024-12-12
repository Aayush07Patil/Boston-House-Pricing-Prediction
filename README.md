# Boston House Pricing Prediction
## Using the Boston Housing Dataset we predict the prices of boston houses depending on most effective factors

🛠️ Project Workflow:<br>
1️⃣ Data Cleaning:<br>
Handled missing values and prepared the dataset for analysis. <br>
2️⃣ Feature Selection:<br>
Analyzed feature correlations with the target variable (MEDV: Median value of owner-occupied homes in $1000s) to identify impactful predictors.
Excluded less relevant features like CHAS.<br>
3️⃣ Data Splitting:<br>
Divided the data into an 80:20 train-test split to ensure robust model evaluation.<br>
4️⃣ Model Training and Evaluation:<br>
Trained six machine learning models:<br>
Linear Regression<br>
Decision Tree<br>
Random Forest<br>
GradientBoostv
ADA Boost<br>
XGBoost<br>
Tracked the runtime and evaluated the performance of each model using the R-squared metric.<br>
5️⃣ Model Selection:<br>
Chose the GradientBoost model, which achieved the highest accuracy while maintaining a competitive runtime.<br>

🔑 Key Features in the Dataset:<br>
CRIM: Per capita crime rate by town<br>
ZN: Proportion of residential land zoned for large lots<br>
NOX: Nitric oxide concentration<br>
RM: Average number of rooms per dwelling<br>
LSTAT: Lower status of the population<br>

🚀 Results:
This project not only honed my skills in data cleaning, feature engineering, and model evaluation but also demonstrated the power of GradientBoost as a high-performing algorithm for regression tasks.
