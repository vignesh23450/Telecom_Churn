# Telco Customer Churn Analysis

This project analyzes customer churn in a telecommunications company using the Telco Customer Churn dataset. The dataset contains information about customers, their characteristics, and whether they churned or not. The analysis involves data preprocessing, visualization, and exploring potential patterns related to customer churn.

## Dataset

The dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) includes the following columns:

- `customerID`: Customer ID
- `gender`: Gender of the customer
- `SeniorCitizen`: Whether the customer is a senior citizen (1 for yes, 0 for no)
- `Partner`: Whether the customer has a partner (Yes/No)
- `Dependents`: Whether the customer has dependents (Yes/No)
- `tenure`: Number of months the customer has stayed with the company
- `PhoneService`: Whether the customer has a phone service (Yes/No)
- `MultipleLines`: Whether the customer has multiple lines (Yes/No/No phone service)
- `InternetService`: Type of internet service (DSL/Fiber optic/No)
- ... (and more)

## Data Preprocessing

- The data is loaded into a Pandas DataFrame (`df`).
- The `Churn` column is encoded using Label Encoding.
  
## Exploratory Data Analysis (EDA)

- The correlation matrix is visualized using a heatmap to identify relationships between numerical features.
- Countplots are created to visualize the distribution of categorical variables.
- Pie charts and bar charts are used to show the distribution of payment methods, gender, and senior citizens.

## Visualizations

- Multiple countplots are created to explore the distribution of various categorical features.
- Line plots are used to visualize the relationship between churn and gender, partner status, and dependents.

## How to Use

1. Ensure you have the necessary Python libraries installed (`pandas`, `matplotlib`, `seaborn`).
2. Download the Telco Customer Churn dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) and place it in the same directory as your Jupyter Notebook or Python script.
3. Copy and paste the provided code into your Jupyter Notebook or Python script.
4. Run the code to perform data analysis and generate visualizations.

Feel free to modify and customize the code based on your specific analysis requirements.

## Additional Notes

- This analysis assumes the dataset is clean, and no missing values or outliers are present. If needed, further data cleaning steps can be added.
- Adjust visualization parameters and styles according to your preferences.

Happy analyzing!
