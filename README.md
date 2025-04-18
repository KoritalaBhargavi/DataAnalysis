# Diwali Sales Data Analysis

## Project Overview

This project performs a detailed analysis of Diwali sales data to extract meaningful insights about customer purchasing behaviors based on demographics and product categories. Using Python libraries such as Pandas, Matplotlib, and Seaborn, the analysis reveals trends across various factors including gender, age group, marital status, state, occupation, and product preferences.

**Objective**:  
- To analyze and visualize customer buying behavior.
- To understand demographic trends and their influence on purchasing power.
- To categorize products and analyze sales based on customer attributes.

---

### **1. Data Collection and Preprocessing**

The dataset used in this project contains customer orders during the Diwali season. The key attributes in the dataset include:

- **Gender**
- **Age Group**
- **State**
- **Marital Status**
- **Occupation**
- **Product Category**
- **Amount Spent**
- **Number of Orders**

The raw data is available in the file: [Diwali Sales Data](https://github.com/KoritalaBhargavi/DataAnalysis/blob/main/Diwali%20Sales%20Data.xls).

**Data Preprocessing Steps**:
1. **Loading Data**: Data was loaded using `pandas.read_excel()` into a DataFrame.
2. **Handling Missing Values**: Missing data was removed using `dropna()`.
3. **Removing Irrelevant Columns**: Non-relevant columns such as `Status` and `unnamed1` were removed.
4. **Data Type Conversion**: The `Amount` column was converted to integer type for consistency.
5. **Renaming Columns**: Columns like `Marital_Status` were renamed to more meaningful names (e.g., `Shaadi`).

---

### **2. Exploratory Data Analysis (EDA)**

#### **Gender Analysis**:
- **Visualization**: Countplot was used to visualize the gender distribution.
- **Insight**: Female buyers make up the majority of customers, and their total purchase amount exceeds that of male customers.

#### **Age Group Analysis**:
- **Visualization**: Countplot and barplot were used to analyze purchases by age group.
- **Insight**: The age group 26-35 years shows the highest purchasing activity, with females leading the sales.

#### **State Analysis**:
- **Visualization**: Bar charts were created to visualize the total orders and total sales by state.
- **Insight**: Uttar Pradesh, Maharashtra, and Karnataka are the leading states for both order count and total sales.

#### **Marital Status**:
- **Visualization**: Countplot and grouped bar chart analyzed marital status against total spending.
- **Insight**: Married women tend to spend more, especially in higher-value purchases.

#### **Occupation Analysis**:
- **Visualization**: Countplot and barplot were used to visualize the sales distribution across occupations.
- **Insight**: IT, Healthcare, and Aviation sectors show higher purchase amounts.

#### **Product Category Analysis**:
- **Visualization**: Countplot and barplot visualized the most popular product categories by sales.
- **Insight**: Food, Clothing, and Electronics categories lead in total sales.
  
### **Key Insights**
- Gender: Females tend to make more purchases with higher spending.
- Age Group: Most buyers are in the 26-35 age range, with females being the dominant group.
- State: Uttar Pradesh, Maharashtra, and Karnataka have the highest number of orders and sales.
- Marital Status: Married women make higher-value purchases.
- Occupation: IT, Healthcare, and Aviation sectors lead in sales.
- Product Category: Food, Clothing, and Electronics are the top-selling categories.


## Data Files

- **Diwali Sales Data**: You can access the raw dataset for analysis [here](https://github.com/KoritalaBhargavi/DataAnalysis/blob/main/Diwali%20Sales%20Data.xls).
- **Analysis Notebook**: The Jupyter notebook for this analysis can be found [here](https://github.com/KoritalaBhargavi/DataAnalysis/blob/main/Diwali_Sales_Analysis.ipynb).

## Requirements

To run this project, you'll need Python and the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install them via `pip`:

```bash
pip install pandas numpy matplotlib seaborn


