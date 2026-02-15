# 📞 Call Centre Performance Analysis using Python (Pandas)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a Call Centre dataset using Python (Pandas, NumPy) to generate actionable business insights related to:

- Agent performance and KPI metrics  
- Call outcomes and handling time  
- Customer demographics and repeat behavior  
- Follow-up and abandoned call tracking  

The objective is to improve operational efficiency, agent productivity, and customer satisfaction through data-driven decision making.

---

## 🎯 Business Problem
Call centres handle a high volume of customer interactions daily.  
This analysis helps to:

- Identify top-performing and low-performing agents  
- Detect long-duration and abandoned calls  
- Track follow-up requirements  
- Understand customer patterns by age, gender, and location  

These insights support training planning, workload balancing, and process optimization.

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  
- Matplotlib / Seaborn *(optional for visualization)*  

---

## 📂 Dataset Features
The dataset contains the following fields:

- Agent Full Name  
- Call Duration (Minutes)  
- Call Outcome (Resolved, Abandoned, etc.)  
- Agent Rating  
- Customer Age  
- Customer Gender  
- State  
- Repeat Customer (Yes/No)  
- Follow-up Required (Yes/No)  
- Abandon Call Reason  

---

## 🔎 Data Analysis Workflow

### 1️⃣ Data Understanding
- Checked dataset shape, columns, and data types  
- Used `head()`, `info()`, and `describe()` for initial exploration  

### 2️⃣ Data Quality Assessment
- Calculated total missing values  
- Computed missing value percentage  
- Identified columns with highest null values  

### 3️⃣ Exploratory Analysis
- Unique value analysis for categorical features  
- Calls per state distribution  
- Call outcome distribution  
- Product discussion frequency  

### 4️⃣ Customer Segmentation
Filtered data to analyze:
- Customers aged 25–35  
- Repeat customers  
- Female repeat customers from California  
- Calls requiring follow-up  
- Abandoned calls  

### 5️⃣ Agent KPI Analysis
Generated agent-level performance metrics:
- Total calls handled  
- Average agent rating  
- Average call duration  

### 6️⃣ Top Performers
- Identified Top 10 agents based on highest average rating  

---

## 📊 Key Insights
- High-rated agents handle calls more efficiently  
- Short-duration resolved calls indicate better performance  
- Abandoned calls highlight operational gaps  
- Repeat customers reveal loyalty patterns  
- Follow-up tracking improves service workflow  

---

## 📈 Business Impact
This project enables:

- Data-driven agent training programs  
- Reduced call handling time  
- Optimized workforce allocation  
- Improved customer retention strategies  
- KPI-based service quality monitoring  

---

## 🚀 Future Enhancements
- Add interactive dashboards using Power BI / Tableau  
- Implement predictive models for call outcome forecasting  
- Agent performance scoring system  
- Real-time KPI monitoring  

---

## 📎 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/call-centre-analysis.git

# Navigate to project folder
cd call-centre-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run Jupyter Notebook
jupyter notebook
