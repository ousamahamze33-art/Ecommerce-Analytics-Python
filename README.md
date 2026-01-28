# Ecommerce-Analytics-Python
Python-based EDA, regression, classification, and clustering on e-commerce shopper behavior dataset
# E-Commerce Shopper Behavior & Lifestyle Analysis

This project demonstrates **data analysis, regression, classification, and clustering** on an e-commerce shopper behavior dataset using **Python (Jupyter Notebook)** and **Power BI**. The focus is on exploring user demographics, shopping habits, and building predictive models.

---

## **Project Overview**

The dataset includes anonymized shopper information:
- Age, gender, country, urban/rural, income level
- Employment, education, relationship status, children
- Purchase patterns: weekly/monthly purchases, average order value, monthly spend
- Digital behavior: device type, app usage, coupon use, brand loyalty

**Key goals of the analysis:**
1. Perform **exploratory data analysis (EDA)** and visualizations
2. Create **KPIs & distributions** similar to Power BI reports
3. Build **predictive models**:
   - Linear Regression: Monthly Spend
   - Linear Regression: Average Order Value
   - Logistic Regression: Has Children
4. Optional advanced insights:
   - Customer segmentation using **K-Means clustering**
   - Feature importance using **Random Forest**

---

## **Project Structure**

/ecommerce-data-analysis
│
├── ecommerce_analysis.ipynb       # Full Jupyter Notebook with all analysis
├── images/                        # Optional folder with saved plots
├── README.md                       # This project description
└── sample_data.csv (optional)     # Small sample CSV (<1MB) for testing without full dataset

Key Analyses & Visualizations

Exploratory Data Analysis (EDA):

Histograms for age, income, monthly spend

Countplots for gender and top countries

Bar plots showing % of users with children by urban/rural

Predictive Modeling:

Linear Regression: Predict monthly spend and average order value, scatter plots vs actuals

Logistic Regression: Predict has children, predicted probabilities, confusion matrix (% of total)

Advanced Analytics:

Customer Segmentation (Clustering): K-Means with PCA visualization of shopping patterns

Feature Importance (Random Forest): Ranking which features most influence predictions
