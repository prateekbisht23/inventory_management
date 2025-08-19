# 📦 Inventory Management System

This project is an **Inventory Management System** built using **Python (Pandas, NumPy, SciPy)** and **Jupyter Notebook**.  
It allows efficient tracking of stock, performing data analysis, and generating useful statistical insights (mean, standard error, confidence intervals) to support better decision-making.

---

## 📂 Project Structure

```plaintext
├── shoe_sale_data.csv            # Dataset
├── inventory_management.ipynb    # Jupyter Notebook with analysis & implementation
├── requirements.txt              # Project dependencies
└── README.md                     # Project documentation
```

---

## 🛠️ Tech Stack
- **Python 3**
- **Jupyter Notebook**
- **Pandas** → Data handling
- **NumPy** → Numerical operations
- **SciPy** → Statistical calculations (t-values, errors)
- **Matplotlib / Seaborn** → Data visualization (optional)

---

## 📈 Features
- 📊 **Stock Analysis** – Tracks product quantities and demand trends  
- 📉 **Error & Confidence Interval Calculation** – Computes mean, standard error, margin of error, and 95% confidence intervals for inventory data  
- 📦 **Size & Category-based Aggregation** – Groups items by categories (e.g., product size, type, or SKU)  
- 📑 **Reports** – Summarizes inventory data in structured tables  
- 📊 **Visualization Support** – Can generate graphs for trends and comparisons  

---

## 🧮 Statistical Analysis
For each product/category, the system computes:
- **Mean stock/demand**
- **Standard Error**
- **Margin of Error (using t-distribution)**
- **95% Confidence Interval**

This helps in identifying **which products are overstocked or understocked** and making better restocking decisions.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/prateekbisht23/inventory-management.git
   cd inventory-management
   ```
2. Install dependencies:
```bash
pip install requirements.txt
```
3. Open the notebook:

```bash
jupyter notebook notebook.ipynb
```


## 📌 Example Use Cases
- 📦 Identify fast-moving and slow-moving items

- 📊 Forecast demand with confidence intervals

- 🔎 Track stock variations month-to-month

- 🏭 Support purchase/reorder decisions
