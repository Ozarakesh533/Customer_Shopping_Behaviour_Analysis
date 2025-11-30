# 🛍️ Customer Shopping Behaviour Analysis  
### End-to-End Data Analytics Project (Python • SQL • Power BI)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-DB-blue?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

This project explores customer shopping patterns using **Python**, **SQL**, and **Power BI**, uncovering insights into demographics, spending behavior, category performance, shipping preferences, and customer loyalty.  
It covers the complete analytics lifecycle from **raw data → EDA → SQL insights → dashboard → report → presentation**.

---

## 1️⃣ Business Problem  

A retail company is experiencing changes in customer behavior and wants to optimize its marketing strategy, improve customer engagement, and increase revenue.

**Objective:**  
Use customer shopping data to identify trends, understand purchasing behavior, and generate actionable insights.

---

## 2️⃣ Repository Structure  

    📦 Customer_Shopping_Behaviour_Analysis
    │
    ├── customer_shopping_behavior.csv                # Raw dataset (3900 rows)
    ├── Customer_Shopping_Behavio_Analysis.ipynb      # Python EDA & DB load
    ├── customer_behavior_sql_queries.sql             # SQL analysis queries
    ├── customer_behavior_dashboard.pbix              # Power BI Dashboard
    ├── Customer Shopping Behavior Analysis.pdf       # Full report
    ├── Business Problem Document.pdf                 # Requirement doc
    └── Customer-Shopping-Behavior-Analysis.pptx      # Project presentation

---

## 3️⃣ Project Workflow  

    Raw Data → Python Cleaning & EDA → SQL Analysis → Power BI Dashboard → Insights Report → Presentation

---

## 4️⃣ Key Features & Insights  

### ✅ Data Cleaning (Python)
- Imputed missing values  
- Standardized and formatted columns  
- Created new features (`age_group`, `purchase_frequency_days`)  
- Removed redundant columns  

### ✅ Exploratory Data Analysis (EDA)
- Age & gender distribution  
- Category-wise sales patterns  
- Seasonal purchase behavior  
- Review rating analysis  
- High-value customer identification  

### ✅ SQL Business Analysis
- Revenue by Gender  
- Top-Rated Products  
- Subscribers vs Non-Subscribers  
- Shipping Type Impact  
- Discount-Dependent Products  
- Customer Segmentation (New / Returning / Loyal)  
- Top 3 Products per Category  
- Revenue by Age Group  

### ✅ Power BI Dashboard
Includes:
- 📊 Revenue by Category  
- 👥 Customer Segmentation  
- ⭐ Average Review Rating  
- 🚚 Shipping Preference Impact  
- 👨‍🦱 Revenue by Age Group  
- 🛍️ Sales by Category  
- 🔄 Subscription Status  

---

## 5️⃣ Insights Summary  

### ⭐ Revenue Drivers
- Young Adults contribute the highest revenue  
- Express shipping users spend **around 12% more** per order  

### ⭐ Customer Behavior
- ~50% New customers, ~35% Returning, ~15% Loyal  
- Subscribers spend more on average  

### ⭐ Product Trends
- Strong performers: Gloves, Sandals, Boots, Hat, Skirt  
- Clothing & Accessories dominate overall sales  

### ⭐ Discount Insights
- Some product categories are highly discount-dependent  
- Discount users are more likely to become repeat customers  

---

## 6️⃣ Dashboard Preview  

(After uploading an image to the repo, replace the link below)

    ![Dashboard](your_dashboard_image_link_here)

---

## 7️⃣ How to Run This Project  

**1. Clone the repository**

    git clone https://github.com/Ozarakesh533/Customer_Shopping_Behaviour_Analysis.git
    cd Customer_Shopping_Behaviour_Analysis

**2. Install Python dependencies**

    pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary

**3. Run Jupyter Notebook**

    jupyter notebook

**4. Connect to PostgreSQL**

- Update your DB credentials in the notebook.  
- Run the cell that uploads the cleaned data to the database.

**5. Open the Power BI Dashboard**

- Open `customer_behavior_dashboard.pbix` in Power BI Desktop.  
- Click **Refresh** and interact with filters and visuals.

---

## 8️⃣ Architecture Diagram  

    ┌────────────────────┐
    │   Raw CSV Data     │
    └─────────┬──────────┘
              │
              ▼
    ┌────────────────────────────┐
    │ Python Cleaning & EDA      │
    │ (Pandas, Seaborn)          │
    └─────────┬──────────────────┘
              │
              ▼
    ┌────────────────────────────┐
    │ SQL Analysis (PostgreSQL)  │
    └─────────┬──────────────────┘
              │
              ▼
    ┌────────────────────────────┐
    │ Power BI Interactive Dash  │
    └─────────┬──────────────────┘
              │
              ▼
    ┌──────────────────────────────┐
    │ Report + PPT + Recommendations│
    └──────────────────────────────┘

---

## 9️⃣ Author  

**Rakesh Oza**  
Data Analyst • Python Developer • SQL | Power BI | Machine Learning  

- 🔗 LinkedIn: https://www.linkedin.com/in/rakeshoza/  
- 🔗 GitHub: https://github.com/Ozarakesh533  

---

## 🔟 Support the Project  

If you found this project helpful, please give it a **⭐ on GitHub** — it really helps!
