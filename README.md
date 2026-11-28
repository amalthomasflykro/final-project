# 💳 Credit Risk Data Analysis Using Python

## 📌 Project Overview

This project focuses on analysing customer financial information to understand credit profiles, loan characteristics and borrowing behaviour.

The analysis uses Python to perform data cleaning, preprocessing, feature engineering, statistical analysis and exploratory data analysis (EDA). Different visualizations are used to explore relationships between financial variables and understand customer borrowing patterns.

## 🎯 Project Objectives

- Understand and explore the credit dataset.
- Identify and remove duplicate records.
- Handle missing values.
- Standardize inconsistent categorical values.
- Detect and handle outliers using the IQR method.
- Perform feature engineering.
- Conduct statistical and exploratory data analysis.
- Visualize financial patterns and customer distributions.
- Generate meaningful insights from credit-related data.

## 📂 Dataset Information

| Description | Details |
|---|---|
| Dataset | Credit Test Dataset |
| Total Rows (Initial) | 10,353 |
| Total Columns | 18 |
| Domain | Banking & Finance |
| File Format | CSV |

### Important Features

- Loan ID
- Customer ID
- Current Loan Amount
- Term
- Credit Score
- Annual Income
- Years in Current Job
- Home Ownership
- Monthly Debt
- Years of Credit History
- Current Credit Balance
- Maximum Open Credit
- Bankruptcies
- Tax Liens
- Months Since Last Delinquent

## 🛠️ Technologies & Libraries

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Development environment

## 🧹 Data Cleaning & Preprocessing

The following operations were performed:

1. Loaded the dataset using Pandas.
2. Examined rows, columns, data types and statistical summaries.
3. Identified and removed 5 duplicate records.
4. Standardized categorical values using string operations.
5. Renamed selected columns for consistency.
6. Identified the special value `99999999` in the loan amount column and replaced it with a missing value.
7. Detected and filtered outliers using the Interquartile Range (IQR) method.
8. Examined missing values and their percentages.
9. Filled selected missing categorical and numerical values using the mode.
10. Created a `Delinquency_Data_Missing` feature to identify missing delinquency information.
11. Exported the cleaned dataset as `Cleaned_Credit_Data.csv`.

## 📊 Exploratory Data Analysis & Visualization

The project includes the following visualizations:

| Analysis | Visualization |
|---|---|
| Current Loan Amount Distribution | Histogram |
| Customer Distribution by Loan Term | Area Chart |
| Credit Score Distribution | Histogram |
| Annual Income Distribution | Doughnut/Pie Chart |
| Monthly Debt by Home Ownership | Heatmap |
| Years of Credit History | Line Chart |
| Customer Distribution by Home Ownership | Pie Chart |
| Loan Applications by Purpose | Bar Chart |
| Average Annual Income by Home Ownership | Bar Chart |
| Annual Income vs Credit Score | Scatter Plot |

## 🔍 Key Insights

The analysis explores:

- Customer borrowing patterns across loan terms.
- Distribution of customer credit scores.
- Annual income distribution among borrowers.
- Monthly debt patterns across home ownership categories.
- Differences in customer credit history.
- Common loan application purposes.
- Average annual income across home ownership groups.
- Relationships between annual income and credit scores.

These visualizations help identify customer segments, financial patterns and areas that may require further credit risk investigation.

## 💡 Recommendations

- Evaluate credit scores when assessing customer credit profiles.
- Consider annual income and monthly debt together when examining repayment capacity.
- Analyse credit history and delinquency information.
- Monitor loan amounts in relation to customer financial profiles.
- Use customer segmentation to understand different borrowing patterns.
- Explore machine learning techniques for future credit risk prediction.

## 📝 Conclusion

This project demonstrates how Python can be used to transform raw financial data into meaningful information through data cleaning, preprocessing, feature engineering and visualization.

The analysis provides an understanding of customer financial characteristics, loan distributions, credit scores and borrowing behaviour.

It also strengthens practical skills in Python programming, Pandas, statistical analysis, data visualization and exploratory data analysis.

## ⚠️ Limitations & Considerations

- The analysis is limited to the available dataset.
- Removing outliers may exclude some legitimate financial records.
- Missing-value imputation may influence statistical results.
- The project focuses on exploratory analysis rather than a predictive machine learning model.
- Correlation between financial variables does not establish causation.
- Customer financial information should be handled responsibly and confidentially.
- Further validation is required before using the findings for actual lending decisions.

## 🚀 Future Improvements

- Develop a machine learning model for credit risk prediction.
- Perform deeper statistical analysis.
- Build an interactive Power BI dashboard.
- Compare high-risk and low-risk customer segments.
- Evaluate model performance using appropriate classification metrics.

## 👨‍💻 Author

**Amal Thomas**

Aspiring Data Analyst

Skills: Python | Pandas | NumPy | Matplotlib | Seaborn | Data Cleaning | EDA | Data Visualization



---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.

**Project Type:** Data Analysis | Python | Banking & Finance | Credit Risk Analysis
