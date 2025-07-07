# Blinkit Data Analysis Project

## Overview
This project analyzes Blinkit's sales and operational data to uncover actionable insights for optimizing business performance. Blinkit, an Indian quick-commerce platform, focuses on rapid delivery of groceries and essentials. The analysis uses Python for data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling to identify sales patterns, customer behavior, and inventory trends.

## Objectives
- Identify top-performing products and cities for revenue generation.
- Analyze customer spending patterns and identify inactive customers.
- Optimize inventory and delivery processes using data-driven insights.
- Build predictive models to forecast sales and evaluate influencing factors.

## Dataset
The dataset includes Blinkit's sales and operational data with fields like:
- **Item_Identifier**: Unique product ID.
- **Item_Weight**: Product weight.
- **Item_Fat_Content**: Low fat or regular.
- **Item_Visibility**: Display area percentage.
- **Item_Type**: Product category (e.g., Fruits and Vegetables).
- **Item_MRP**: Maximum retail price.
- **Outlet_Identifier**: Unique store ID.
- **Outlet_Establishment_Year**: Store establishment year.
- **Outlet_Size**: Store size (Small, Medium, Large).
- **Outlet_Location_Type**: City type (Tier 1, Tier 2, Tier 3).
- **Sales**: Revenue from product sales.

Data is preprocessed to handle missing values, standardize labels, and ensure consistency.

## Tools and Technologies
- **Python**: Core language for analysis and modeling.
- **Libraries**:
  - Pandas: Data manipulation.
  - NumPy: Numerical computations.
  - Matplotlib/Seaborn: Visualizations.
  - Scikit-Learn: Machine learning models.
- **Jupyter Notebook**: For interactive analysis.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kajal53/Data-Analysis-Python-Project---Blinkit-Analysis.git
   cd Data-Analysis-Python-Project---Blinkit-Analysis

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   
3. Install dependencies: 
   ```bash
   pip install -r requirements.txt

3. Or install manually:: 
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   

4. Run Jupyter Notebook:
   ```bash
   jupyter notebook 

## Key Findings
Top Categories: Fruits and Vegetables and Snack Foods drive ~30% of sales.
Customer Trends: High demand for low-fat products.
Outlet Performance: Medium-sized outlets in Tier 3 cities are most profitable.
Customer Satisfaction: Average rating of 4.0, with room for loyalty improvements.
Model Accuracy: Decision Tree models achieved up to 88.9% accuracy.

## Recommendations
Expand high-demand product categories.
Invest in Tier 3 cities and medium-sized outlets.
Implement promotions to boost customer retention.
Optimize pricing and visibility using model insights.

## Project Structure

Data-Analysis-Python-Project---Blinkit-Analysis/
├── dataset/
│   └── blinkit_data.xlsx        # Raw dataset
├── notebooks/
│   └── blinkit_analysis.ipynb   # Analysis notebook
├── scripts/
│   └── preprocess.py           # Data cleaning scripts
├── visualizations/
│   └── (generated plots)       # Visualizations
├── requirements.txt            # Dependencies
└── README.md                   # Documentation


## Contributions
Fork the repository.
Create a branch: git checkout -b feature-branch.
Commit changes: git commit -m "Add feature".
Push: git push origin feature-branch.
Open a pull request.
   
 







   

