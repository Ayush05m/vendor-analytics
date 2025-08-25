
# 🛒 Vendor Performance Analysis

This project analyzes **vendor performance** using procurement and sales data to identify top-performing suppliers, cost-saving opportunities, and risks associated with procurement dependency.  
It includes **data ingestion, exploratory analysis, and deep vendor performance analytics** using Python (Pandas, NumPy, Matplotlib, Seaborn, and SQL).

---

## 🎯 Objectives
- Understand which vendors/brands generate the highest sales.  
- Identify vendors contributing most to procurement costs.  
- Detect over-dependence on a few vendors.  
- Analyze if bulk purchasing reduces unit price.  
- Highlight vendors with slow-moving stock or low turnover.  
- Estimate capital locked in unsold inventory.  
- Compare profit margins of high- vs low-performing vendors.  

---

## 📂 Project Structure
```

📁 Vendor-Performance-Analysis/
│── Ingestion\_db.ipynb          # Data ingestion & database setup
│── EDA.ipynb                   # Exploratory Data Analysis (sales trends, vendor drilldown)
│── Vendor Performance Analysis.ipynb   # Detailed business insights & vendor evaluation
│── data/                       # Raw datasets (if applicable)
│── README.md                   # Project documentation

````

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scipy, Statsmodels  
- **Database (optional):** SQLite / PostgreSQL for ingestion & queries  
- **Notebook Environment:** Jupyter  

---

## 🔎 Analysis Performed
### 1️⃣ Data Ingestion  
- Loaded procurement and sales data into structured format.  
- Cleaned duplicates, handled missing values, standardized units.  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Monthly and vendor-level sales trends.  
- Drilldown into specific vendors (e.g., Vendor #4466).  

### 3️⃣ Vendor Performance Analytics  
- **Top Vendors by Sales & Purchase Dollars**  
- **Procurement Dependency** (concentration of spend on few vendors)  
- **Bulk Purchase Effect** (analyzing unit price vs. volume)  
- **Inventory Turnover** (fast vs. slow-moving stock)  
- **Capital Locked in Unsold Inventory**  
- **Profitability Analysis** (confidence intervals for profit margins, t-tests between vendors)  

---

## 📊 Sample Insights
- A small group of vendors accounted for a **major share of procurement**, but were not always the most profitable.  
- **Bulk purchasing didn’t always reduce costs** — beyond a point, no significant discount was observed.  
- Certain vendors had **low inventory turnover**, locking large amounts of working capital.  
- Statistical analysis confirmed significant differences in profit margins between vendor groups.  

---

## 🖥️ Example Visuals
*(Add generated plots in your repo for better impact)*

- Sales trends over time  
- Vendor-wise procurement distribution (Pareto analysis)  
- Bulk purchase vs. unit price scatter plot  
- Capital locked in inventory per vendor  
- Confidence intervals for vendor profit margins  

---

## 📌 How to Run
1. Clone this repository:
    ```bash
   git clone https://github.com/your-username/vendor-performance-analysis.git
   cd vendor-performance-analysis
  
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run notebooks in this order:

   * `Ingestion_db.ipynb` → data ingestion
   * `EDA.ipynb` → exploratory data analysis
   * `Vendor Performance Analysis.ipynb` → detailed insights

---

## 🔮 Future Enhancements

* Automate ingestion pipeline with Airflow.
* Deploy dashboards via Streamlit or Power BI.
* Integrate live procurement data via APIs.
* Extend analysis to supplier risk & sustainability metrics.

---

## 👨‍💻 Author

**Ayush**  @ NIT Raipur

* 💼 Data & Analytics Enthusiast
* 🔗 [LinkedIn](https://linkedin.com/ayushmishra-profile)
* 💻 [Portfolio](https://ayushmishra-profile.com)
