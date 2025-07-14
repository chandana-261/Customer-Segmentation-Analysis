# Customer-Segmentation-Analysis
# 👥 Customer Segmentation Analysis

This project applies data analysis and machine learning techniques to segment customers based on their demographics and purchasing behavior. The segmentation helps businesses better understand their customer base and target them more effectively.

## 🎯 Objectives

- Load and explore customer data
- Clean and preprocess data for modeling
- Compute descriptive statistics (e.g., income, spending score)
- Perform customer segmentation using K-Means clustering
- Visualize customer groups using PCA
- Provide actionable business insights for marketing strategies

## 🧾 Dataset Description

The dataset includes 1,000 customer records with the following features:

| Column Name            | Description                                      |
|------------------------|--------------------------------------------------|
| `id`                   | Unique customer ID                               |
| `age`                  | Age of the customer                              |
| `gender`               | Gender of the customer                           |
| `income`               | Annual income                                    |
| `spending_score`       | Score indicating spending behavior (1–100)       |
| `membership_years`     | Number of years as a member                      |
| `purchase_frequency`   | Average monthly purchase frequency               |
| `preferred_category`   | Preferred shopping category                      |
| `last_purchase_amount` | Amount spent in the last purchase                |


## 🧰 Requirements

Install necessary libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn

▶️ How to Run
Clone this repo or download the files

Make sure the dataset is named customer_segmentation_data.csv

Run the Python script:
bash
Copy
Edit
python customer_segmentation_eda.py


📊 Analysis & Visualization
Histogram of customer ages

Scatter plot of Income vs Spending Score by gender

K-Means clustering for segmentation

PCA-based 2D visualization of customer clusters

🔍 Insights
Segments reveal differences in customer spending and loyalty behavior.

Some clusters represent high-income, high-spending individuals—ideal for premium offers.

Other segments may benefit from promotions or loyalty programs to increase retention.

Marketing can be personalized based on segment characteristics.

🧠 Recommendations
Focus premium marketing on high-spending segments.

Offer personalized discounts to medium-income, moderate-spending groups.

Encourage loyalty signups from newer or low-frequency buyers.

Create segment-specific email campaigns or app experiences.

📁 Project Structure
vbnet
Copy
Edit
.
├── customer_segmentation_data.csv
├── customer_segmentation_eda.py
├── README.md
└── visualizations/ (optional, to save plots)
🚀 Future Work
Apply hierarchical clustering for comparison

Add customer lifetime value (CLV) prediction

Build a dashboard with Streamlit or Power BI

👨‍💻 Author
YANAMANDRA LAKSHMI CHANDANA
Email: chandanayanamandra2611@gmail.com

