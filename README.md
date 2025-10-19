# 📱 Surf vs. Ultimate: Revenue Insights for Megaline Telecom

## 📌 Introduction
This project analyzes customer behavior and plan performance for **Megaline Telecom**, focusing on two prepaid tariffs: **Surf** and **Ultimate**.  
The goal is to determine which plan generates higher average revenue and whether customer region impacts revenue differences.  

---

## 📂 Dataset

**Cloud Services:** AWS S3 (data hosting and retrieval). 
The analysis uses five CSV files with customer and usage data:

1. **megaline_users.csv** – customer demographics and tariff plan  [Download](https://code.s3.yandex.net/datasets/megaline_users.csv)
2. **megaline_calls.csv** – call records with durations  [Download](https://code.s3.yandex.net/datasets/megaline_calls.csv)
3. **megaline_messages.csv** – SMS activity  [Download](https://code.s3.yandex.net/datasets/megaline_messages.csv)
4. **megaline_internet.csv** – web sessions and data usage  [Download](https://code.s3.yandex.net/datasets/megaline_internet.csv)
5. **megaline_plans.csv** – tariff plan details  [Download](https://code.s3.yandex.net/datasets/megaline_plans.csv)

---

## ⚙️ Methodology
The project follows five main steps:

1. **Data Exploration**  
   - Reviewed dataset structure and quality  
   - Verified consistency of IDs, dates, and ranges  

2. **Data Preprocessing**  
   - Converted datatypes (IDs, dates, numerical fields)  
   - Treated missing values and errors  
   - Aggregated monthly activity per user (calls, SMS, data usage, revenue)  

3. **Exploratory Data Analysis (EDA)**  
   - Customer behavior across tariffs (minutes, SMS, data usage)  
   - Mean, variance, and standard deviation of usage metrics  
   - Histograms and distribution analysis  

4. **Hypothesis Testing**  
   - **H₀ vs H₁**: Average revenue of Surf vs Ultimate customers is equal/different  
   - **H₀ vs H₁**: Average revenue of NY–NJ region vs other regions is equal/different  
   - Applied statistical tests with chosen significance level (α)  

5. **Conclusion**  
   - Summarized insights on which tariff is more profitable  
   - Business implications for marketing and budget allocation  

---

## 📊 Key Analyses
- Average monthly usage of **minutes, SMS, and data** by plan  
- Distribution of customer behavior and spending  
- Revenue contribution of each tariff plan  
- Statistical evidence on revenue differences between plans and regions  

---

## ✅ Conclusion
The project demonstrates proficiency in:  
- **Python (pandas, matplotlib, seaborn, scipy)**  
- **Data cleaning and aggregation**  
- **Statistical hypothesis testing**  
- **Revenue-focused analytics for business strategy**  

The findings provide actionable insights into customer behavior and tariff profitability, supporting marketing and budget decisions.  

---

## 💻 Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- SciPy  
- Jupyter Notebook  

---

## 🤝 Contact
Created by **Diana Paola Ayala Roldán**  
🔗 [LinkedIn](https://www.linkedin.com/in/dianisay/) | [Portfolio](https://github.com/dianisay)
