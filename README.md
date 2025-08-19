# 📊 Supplier Performance & Risk Scoring Analysis

This project aims to **evaluate supplier performance** based on key KPIs and perform **supplier risk classification** to support strategic decision-making in supply chain management.

---

## 🚀 Background
Supplier management often faces challenges:
- Difficulty in distinguishing the best suppliers from risky ones.
- Lack of standardized and consistent evaluation methods.
- Decisions are often subjective and not data-driven.

This project addresses those challenges by building a **Supplier Performance & Risk Scoring System** using data analysis.

---

## 🎯 Business Objectives
1. Develop a **Supplier Score** based on objective KPIs:
   - On-Time Delivery Rate
   - Reliability Score
   - Total Cost
   - Cost Efficiency
   - Production Capacity Score
2. Classify suppliers into categories:
   - **Preferred** (≥85) → Top-performing suppliers
   - **Standard** (70–84) → Average suppliers
   - **High Risk** (<70) → Risky suppliers
3. Provide performance and risk analysis visualizations:
   - Distribution & Boxplot of Supplier Score
   - Supplier Category Composition
   - Heatmap of Top 10 Supplier KPIs
   - Heatmap of Average KPIs per Supplier Category
4. Generate automated insights to support strategic decision-making.

---

## Datasets
- [Original dataset from Kaggle](https://www.kaggle.com/datasets/amirmotefaker/supply-chain-dataset)
- [Cleaned dataset after preprocessing](https://drive.google.com/file/d/1PlCwEBgz7Zd6PNTXUfF0YF6hqhsyZseO/view?usp=drive_link) 

---

## 📂 Project Structure
-'Datasets/':
         - `supply_chain_data.csv` → Raw dataset  
         - `supply_chain_data_cleaned.csv` → Cleaned dataset after preprocessing  
- `Supplier_Performance_&_Risk_Scoring_Analysis.ipynb` → Main notebook for analysis & visualization  
- `images/` → Folder containing output charts (histogram, boxplot, heatmap, etc.)  

---

## 🛠️ Technologies Used
- **Python 3**
- **Pandas, NumPy** → Data preprocessing & feature engineering
- **Matplotlib, Seaborn** → Data visualization
- **Google Colab** → Analysis environment
- **CSV Dataset** (ISO-8859-1 format)

---

## 📊 Key Visualizations
1. **Distribution & Boxplot of Supplier Score**  
   - Shows the distribution of supplier scores and potential outliers.  
2. **Supplier Category Composition**  
   - Most suppliers fall into the *High Risk* category.  
3. **Heatmap of Top 10 Supplier KPIs**  
   - Highlights the strengths and weaknesses of the top suppliers.  
4. **Heatmap of Average KPIs per Supplier Category**  
   - Compares average performance of *Preferred*, *Standard*, and *High Risk* suppliers.  

---

## 💡 Key Insights
- **Preferred** suppliers achieve the highest average score (88.17).  
- Strongest KPI: **Reliability Score** (consistently high across all categories).  
- Weakest KPI: **On-Time Delivery Rate** (especially among *High Risk* suppliers).  
- The supplier with the **best cost efficiency** may differ from the most reliable one.  

---

## 📌 Conclusion
✅ This system helps businesses to:  
- Identify top-performing and risky suppliers.  
- Provide an objective basis for procurement decisions.  
- Enable continuous monitoring of supplier performance.  

---

## 📎 Next Steps (Future Improvements)
- Integration with **BI dashboards (Tableau / Power BI)**.  
- Add predictive models for **supplier risk forecasting**.  
- Automate the analytics pipeline for real-time updates.  

---

## 👨‍💻 Author
**Carmenita Lamba**
[LinkedIn](https://www.linkedin.com/in/carmenita-lamba-6a7555220/)
