
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/44a88baa-bf74-4ee4-b538-9fa4c4e388b7" />

# **Fashion Retail Demand Analysis & Forecasting**

### **Ironhack Data Analytics Bootcamp – Final Project**

---

## **📌 Project Overview**

This project analyzes historical sales data from a global fashion retail business to understand demand drivers and support better inventory and stock planning decisions.

By combining data cleaning, exploratory analysis, forecasting models, and interactive dashboards, the project aims to provide actionable insights for demand forecasting, category management, and promotional strategy optimization.

## **Objectives**

The main objectives of this project are:

* Analyze historical sales trends and seasonality patterns  
* Identify key demand drivers across categories and countries  
* Evaluate the impact of discounts on sales performance  
* Build and validate a demand forecasting model  
* Create interactive dashboards for business decision support

## **Dataset Description**

The dataset from Kaggle *“Global Fashion Retail Sales”* includes transactional and product-level information, such as:

* Invoice and transaction details  
* Product and category information  
* Sales quantity and pricing  
* Discount levels  
* Store and country location  
* Date and time variables

Multiple CSV files were merged using primary keys.

## **Tools & Technologies**

* **Python** (Pandas, NumPy, Matplotlib, Prophet)  
* **Tableau Desktop** (Data visualization & dashboards)  
* **Jupyter Notebook** (Analysis & modeling)  
* **GitHub** (Version control & documentation). Raw & Clean Data saved in .gitignore folders due to large database.

## **Project Workflow**

### **1\. Data Preparation**

* Data cleaning and formatting  
* Handling missing values and duplicates  
* Feature engineering (date fields, discount normalization)

### **2\. Exploratory Data Analysis (EDA)**

* Trend and seasonality analysis  
* Category and country performance  
* Discount vs demand analysis  
* KPI computation

### **3\. Forecasting Model**

* Time-series forecasting using Prophet  
* Time-based cross-validation  
* Performance evaluation using SMAPE  
* Bias detection and correction

### **4\. Data Visualization**

* Interactive Tableau dashboard  
* KPI overview  
* Demand trends  
* Category and regional analysis  
* Promotion impact visualization

---

## **📈 Key Findings**

* Demand shows strong seasonal patterns, especially in Q4  
* Sales growth is driven by a limited number of categories  
* Discounting increases demand but with diminishing returns  
* Significant differences exist between countries  
* Forecast model achieved \~23% SMAPE at category level

---

## **📊 Dashboard Description**

The Tableau dashboard provides:

* Executive KPI overview  
* Daily and monthly demand trends  
* Category growth analysis  
* Promotion effectiveness analysis  
* Geographic demand distribution  
* Interactive filters and parameters

The dashboard supports data-driven stock planning decisions.

---

## **💡 Business Impact**

This analysis enables retailers to:

* Improve demand forecasting accuracy  
* Reduce overstock and stockouts  
* Optimize promotional strategies  
* Apply differentiated inventory policies  
* Support localized supply chain planning

---

## **📌 Limitations**

* Forecast accuracy depends on historical data quality  
* External factors (weather, trends, competition) not included  
* Limited long-term prediction reliability  
* Promotion effects may vary by category

---

## **🔮 Future Improvements**

* Integrate external data (weather, social trends)  
* Develop SKU-level forecasts  
* Apply machine learning models (LSTM, XGBoost)  
* Automate data pipelines  
* Deploy dashboard online

---

## **👤 Author**

**\[Chiara Lanzi\]**  
Ironhack Data Analytics Bootcamp

---

## **📜 Acknowledgements**

Special thanks to Ironhack instructors and classmates for guidance and feedback throughout the project.

---

