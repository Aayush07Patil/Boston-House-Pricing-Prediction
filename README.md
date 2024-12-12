# Boston House Pricing Prediction
## Using the Boston Housing Dataset we predict the prices of boston houses depending on most effective factors

🛠️ Project Workflow:
1️⃣ Data Cleaning:
Handled missing values and prepared the dataset for analysis.
2️⃣ Feature Selection:
Analyzed feature correlations with the target variable (MEDV: Median value of owner-occupied homes in $1000s) to identify impactful predictors.
Excluded less relevant features like CHAS.
3️⃣ Data Splitting:
Divided the data into an 80:20 train-test split to ensure robust model evaluation.
4️⃣ Model Training and Evaluation:
Trained six machine learning models:
Linear Regression
Decision Tree
Random Forest
GradientBoost
ADA Boost
XGBoost
Tracked the runtime and evaluated the performance of each model using the R-squared metric.
5️⃣ Model Selection:
Chose the GradientBoost model, which achieved the highest accuracy while maintaining a competitive runtime.

🔑 Key Features in the Dataset:
CRIM: Per capita crime rate by town
ZN: Proportion of residential land zoned for large lots
NOX: Nitric oxide concentration
RM: Average number of rooms per dwelling
LSTAT: Lower status of the population

🚀 Results:
This project not only honed my skills in data cleaning, feature engineering, and model evaluation but also demonstrated the power of GradientBoost as a high-performing algorithm for regression tasks.
