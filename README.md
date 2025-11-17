Below is a clean, recruiter-friendly **README.md** for your data analytics project.
You can directly copy-paste this as your project’s README.

---

# 📊 Customer Shopping Behavior Analysis — Data Analytics Project

## 📝 **Overview**

This project analyzes customer shopping behavior using a dataset of **3,900 transactions** across multiple product categories. The goal is to understand spending patterns, customer demographics, product trends, and subscription behavior.
The project follows a complete data analytics workflow — from **Python EDA to SQL analysis, Power BI dashboarding, reporting, and a final presentation**.

---

## 📂 **Dataset**

* **Rows:** 3,900
* **Columns:** 18
* **Includes:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase information (Item, Category, Amount, Season, Size, Color)
  * Behavioral attributes (Discount Applied, Previous Purchases, Rating, Shipping Type)
* **Missing Values:** 37 missing entries in *Review Rating*

---

## 🛠️ **Tools & Technologies**

| Task               | Tool                                       |
| ------------------ | ------------------------------------------ |
| Data Loading & EDA | Python (Pandas, NumPy, Matplotlib/Seaborn) |
| Data Cleaning      | Python                                     |
| Database Analysis  | MySQL (or PostgreSQL)                      |
| Dashboard          | Power BI                                   |
| Report             | Word/PDF                                   |
| Presentation       | Gamma App                                  |

---

## 🔍 **Steps in the Project**

### **1. Data Loading (Python)**

* Imported dataset using **pandas**
* Checked structure using `.info()` and `.describe()`
* Converted column names into `snake_case`

### **2. Exploratory Data Analysis (EDA)**

* Explored demographic distributions
* Analyzed purchase amount patterns, categories, and reviews
* Visualized trends using bar charts, boxplots, histograms
* Identified correlations between discount use, shipping type, and spending behavior

### **3. Data Cleaning**

* Imputed missing values in *review_rating* using **median category ratings**
* Removed redundant fields (e.g., *promo_code_used*)
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Verified data consistency and formatting

### **4. SQL Analysis (MySQL)**

Uploaded cleaned data into MySQL for structured querying.

Key SQL insights extracted:

* Revenue comparison across genders, age groups, and subscription status
* Top-rated and best-selling products
* Relationship between discount use and spending
* Shipping type vs. average purchase amount
* Customer segmentation (New, Returning, Loyal)

### **5. Power BI Dashboard**

Built an interactive dashboard showcasing:

* Customer demographics
* Revenue patterns
* Category-wise sales
* Rating insights
* Subscriber vs. non-subscriber comparison
* Purchase frequency & loyalty segments

### **6. Business Report**

A formal report summarizing:

* Key findings
* Trend analysis
* Actionable business recommendations
* Visual insights from Power BI

### **7. Presentation (Gamma)**

A modern, visually appealing presentation was created using **Gamma**, highlighting major insights and recommendations in a recruiter-friendly format.

---

## 📈 **Results & Insights**

Key findings from the project:

* Subscription customers spend significantly more on average
* Express shipping users show higher purchasing power
* Certain categories have strong customer loyalty
* Discounts heavily influence purchase decisions for specific products
* High-rated products consistently drive higher revenue
* 18–35 age group contributes the largest share of total sales

---

## ▶️ **How to Run the Project**

### **1. Clone the Repository**

```bash
git clone <your-repo-url>
cd customer-shopping-behavior-analysis
```

### **2. Install Required Python Libraries**

```bash
pip install -r requirements.txt
```

### **3. Run the EDA Notebook**

Open and execute:

```
EDA_Cleaning.ipynb
```

### **4. Load Data into MySQL**

* Update database credentials in `mysql_connection.py`
* Run SQL scripts inside the `sql_queries/` folder

### **5. Open the Power BI Dashboard**

Download and launch:

```
dashboard.pbix
```

### **6. View Report and Presentation**

* `Final_Report.pdf`
* `Gamma_Presentation.link`

---

## 📮 **Contact**

If you have questions or want to collaborate:
**Email:** [your-email@example.com](mailto:your-email@example.com)
**LinkedIn:** your-linkedin-profile

---

If you'd like, I can also write:
✅ GitHub repository description
✅ A one-line project summary for your resume
✅ A polished project title
Just tell me!
