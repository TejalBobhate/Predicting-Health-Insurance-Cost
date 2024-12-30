Objective: Develop a predictive model to accurately forecast customer charges for an insurance company. This will enable the company to price policies appropriately, ensuring profitability and competitiveness while maintaining fairness to customers.
Key Steps in the Process

Data Collection:
The dataset used for this analysis was downloaded from Kaggle. It contains information on customer demographics, medical history, and previous claims, including variables such as age, gender, BMI, number of children, smoking status, and region.

Data Preprocessing:
Cleaning: Missing values were handled, data inconsistencies corrected, and duplicates removed.

Encoding: Categorical variables (e.g., sex, region, smoking status) were converted into numerical format using techniques like one-hot encoding or label encoding.

Exploratory Data Analysis (EDA):
Visualization: Histogram and Barplot were used to understand distributions and regression plot to analyse relationships between variables.

Correlation Analysis: Significant correlations between variables were identified to understand their impact on charges.

Model Selection:
Linear Regression was initially applied, followed by Polynomial Regression for better performance.

Model Training and Validation:
Train-Test Split: The data was divided into training and testing sets to evaluate the model's performance.

Model Evaluation:
Metrics: The model was evaluated using performance metrics such as Mean Squared Error (MSE) and R² Score to understand its accuracy and reliability.





