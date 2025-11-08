# 🛒 SUPERMARKET GROCERY STORE - CUSTOMER SEGMENTATION USING MACHINE LEARNING K-MEANS ELBOW METHOD

## Project Overview
This analytical project focuses on segmenting grocery retail customers based on their purchasing behavior and profitability using the **K-Means Clustering** algorithm.  
The goal is to help the company restore and sustain profitability by identifying distinct customer segments that can inform targeted loyalty programs and marketing strategies.  
Data analysis and visualization are performed in **Python** and **Tableau** to provide actionable insights into sales performance and customer behavior.

---

## Dataset
The dataset used is [`grocery_sales.db`](https://drive.google.com/file/d/1HeRKLWVMRnL0FaGlStWT6SZwYZUjmx2f/view), containing transactional data from **2015–2020**.  
It includes detailed information such as customer ID, order date, sales, discount, profit, and product category from a retail store network.

**Source:** Internal project dataset (cleaned and prepared for academic analysis)

**Dataset Highlights:**
- Total transactions: 9,939  
- Total sales: \$14,881,995  
- Total profit: \$3,728,239  

---

## Methodology
This project follows a complete **data analytics and clustering** workflow:

1. **Data Exploration**  
   - Loaded transaction data and examined key metrics (sales, profit, discount).  
   - Identified missing values, duplicates, and outliers.  
   - Visualized initial trends to understand sales and profit fluctuations.

2. **Data Preparation**  
   - Cleaned and transformed data from the `order` table to `order_clean`.  
   - Removed null and duplicate records, and calculated necessary metrics such as average profit margin.  
   - Aggregated customer-level data to prepare for clustering.

3. **Modeling (K-Means Clustering)**  
   - Applied **K-Means** to segment customers based on profitability and purchasing behavior.  
   - Determined the optimal number of clusters using the **Elbow Method**.  
   - Interpreted each cluster based on sales, profit, and margin characteristics.

4. **Visualization and Insights**  
   - Created an interactive **Tableau Dashboard** to visualize monthly sales trends and profit distribution.  
   - Interpreted cluster results into actionable business recommendations for loyalty programs.

---

## Technologies and Tools
**Programming Language:** Python  
**Python Libraries:**
- `pandas`, `numpy` → data cleaning & manipulation  
- `matplotlib`, `seaborn` → data visualization  
- `scikit-learn` → K-Means clustering  
- `sqlite3` → data extraction from database  
- `Tableau` → interactive dashboard and report visualization  

**Environment:** Jupyter Notebook / Google Colab  

---

## Key Results & Insights
- Identified **3 customer segments**:
  - **Cluster 0:** High Profit – High Margin (loyal & premium customers)  
  - **Cluster 1:** High Profit – Low Margin (price-sensitive customers)  
  - **Cluster 2:** Low Profit – Low Margin (low engagement customers)  
- Revealed that higher sales volume doesn’t always translate to higher profit due to margin variation.  
- Provided actionable strategies to improve **profitability and customer retention** through targeted loyalty programs.  
- Developed a **Tableau dashboard** for monthly sales and profit trend analysis.  

📊 [View Tableau Dashboard](https://public.tableau.com/app/profile/fathimah.ella.syarif4669/viz/DashboardGrocerySalesPerformanceOverview/MonthlyTrendofSalesProfit)

---

## How to Run the Notebook
1. Ensure you have Python and the required libraries installed (see `requirements.txt` if provided).  
2. Download:
   - `customer_segmentation.ipynb`
   - `grocery_sales.db`
3. Open the notebook using Jupyter Notebook or Google Colab.  
4. Run all cells sequentially to reproduce the analysis, clustering, and visualizations.  
5. Optionally, explore the results through the linked Tableau dashboard.

---

## Contact
**Author:** Fathimah Ella Syarif
**Affiliation:** Telkom University – S1 Information Systems (Enterprise Data Management)  
**LinkedIn:** [www.linkedin.com/in/fathimahellasyarif]  
**Email:** [faatheellaa@gmail.com]  

---

