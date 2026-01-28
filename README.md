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

##Key Visualizations & Insights

Age Distribution: “Majority of shoppers are aged 30–50, indicating a strong presence of mid-age consumers in the dataset.”

Income Distribution: “Most users earn between $20k–$100k, but a small segment exceeds $150k, representing high-value customers.”

Monthly Spend Distribution: “A large portion of users spend under $50k monthly, while top 10% of spenders account for a disproportionate share of revenue.”

Gender Count: “Female users slightly outnumber males, with non-binary and other genders present but minimal.”

Top 10 Countries: “USA, Japan, Germany, and France dominate the dataset, covering over 60% of users.”

% With Children by Urban/Rural: “Suburban users are more likely to have children (approx. 55%), whereas urban users have fewer (around 45%).”

Monthly Spend Regression: “Predicted monthly spend closely matches actual spend, with some high-spending outliers slightly underestimated by the model.”

Average Order Value Regression: “Model captures trends well; users with frequent purchases tend to have higher average order values, and predictions align with actual values.”

Has Children Logistic Regression: “Probability predictions show clear separation; age and relationship status strongly influence likelihood of having children.”

Has Children Confusion Matrix: “Model correctly classifies about 65% of users with children and 70% without, indicating moderate predictive performance.”

Customer Segmentation (K-Means + PCA): “Four distinct shopper clusters emerge: low-spend casual shoppers, mid-spend regular buyers, high-spend loyal customers, and occasional impulse buyers.”

##Key Analyses & Visualizations

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
