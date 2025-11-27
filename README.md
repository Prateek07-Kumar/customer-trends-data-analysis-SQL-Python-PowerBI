## Customer Shopping Behavior Analysis
### Project Overview
This project analyzes customer shopping behavior data through comprehensive exploratory data analysis (EDA) and data preprocessing. The cleaned and enhanced dataset is then loaded into a PostgreSQL database, making it ready for advanced analytics, business intelligence, and data-driven decision-making.

### Dataset Information
- **Source File:** **customer_shopping_behavior.csv**
- **Total Records:** 3,900 customer transactions
- **Original Features:** 18 columns covering demographics, purchase details, and behavioral patterns
- **Final Features:** 19 columns (after feature engineering)

## Project Workflow
### 1. Environment Setup
The project utilizes Python with key data science libraries, including Pandas for data manipulation, NumPy for numerical operations, Matplotlib and Seaborn for visualization, and SQLAlchemy with psycopg2 for database connectivity.

### 2. Data Loading & Initial Exploration
The dataset was imported from a CSV file and thoroughly examined to understand its structure, data types, and initial quality. The exploration revealed 3,900 customer transactions with 18 original features, identifying that only the Review Rating column had missing values (37 records).

### 3. Exploratory Data Analysis (EDA)
#### Data Profiling

A comprehensive statistical analysis was conducted to understand the characteristics of the dataset. The customer age distribution ranged from 18 to 70 years, with an average of 44 years. Purchase amounts varied between $20 and $100, averaging $59.76. Review ratings fell between 2.5 and 5.0 with a mean of 3.75, and customers had between 1 and 50 previous purchases, averaging 25 transactions.
