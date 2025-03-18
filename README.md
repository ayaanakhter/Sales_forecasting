# 📊 Sales Forecasting 

## 🚀 Project Overview
This project analyzes **Statewide Contract (Master Contract) Sales Data** to:
- 📈 **Forecast future sales** using **Linear & Polynomial Regression**.
- 📊 **Visualize trends** in state contract spending.

## 📂 Dataset Information
- **Source:** [Master Contract Sales Data](https://catalog.data.gov/dataset/master-contract-sales-data-by-customer-contract-vendor)
- **Updated:** March 8, 2025
- **Description:** Reports sales data by contract and customer, including small business & veteran-owned business status.
- **Access:** Public dataset

## 🛠️ Methodology
### **1️⃣ Sales Forecasting**
- **Models Used:**
  - **Linear Regression:** Assumes a constant rate of sales growth.
  - **Polynomial Regression (Degree 2):** Captures accelerating growth trends.
- **Findings:**
  - **Linear Regression** predicts **$2.83B** in sales for 2025.
  - **Polynomial Regression** predicts **$3.32B**, suggesting an increasing growth rate.

## 📊 Results & Visualization
- 📉 **Trends:** Polynomial Regression shows **faster growth** than Linear Regression.
- 📌 **Key Insight:** Sales growth is **non-linear**, meaning higher-than-expected revenue in future years.
- 📈 **Graphs included** in the notebook for clear visualization.

## 🔧 Installation & Usage
### **Requirements**
- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### **Run the Notebook**
1. Clone the repository:
   ```bash
   git clone https://github.com/ayaanakhter/Sales-Forecasting-Analysis.git
   cd Sales-Forecasting-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook sales_forecasting.ipynb
   ```

## 🏆 Contributing
Feel free to **fork** this repository, submit **pull requests**, or suggest improvements!

## 📜 License
This project follows the **[dataset's terms of use](https://catalog.data.gov/dataset/master-contract-sales-data-by-customer-contract-vendor)**. The dataset is **publicly available** but may have specific usage restrictions.

---
🚀 **If you like this project, don't forget to ⭐ the repository!**

