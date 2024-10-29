# Project-6: Demand Forecasting for a Retail Store

## Overview
This project aims to forecast future product demand in the retail sector using historical sales data. The goal is to develop a model that helps optimize inventory management, reduce overstock, and minimize product shortages.

## Objectives
- Analyze historical sales data to identify trends and patterns.
- Use predictive modeling techniques to forecast future product demand.
- Provide actionable insights for better inventory management and restocking strategies.

## Dataset
The dataset contains simulated sales data, including daily sales, product categories, promotions, and pricing. It is saved in the `data` folder as a CSV file (`historical_sales_data.csv`).

## Methodology
1. **Data Simulation:** Generate synthetic sales data representing typical retail sales trends.
2. **Data Cleaning:** Handle missing values and convert categorical variables to numerical form for analysis.
3. **Exploratory Data Analysis (EDA):** Use statistical analysis and visualizations to understand sales trends, patterns, and relationships between variables.
4. **Modeling:** Implement a Random Forest Regressor to predict future demand for retail products.
5. **Evaluation:** Evaluate model performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Requirements
To run this project, you need the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib fpdf
```

## How to Run
1. Clone this repository: `git clone https://github.com/JeanSalgadoAI/Project-6---Demand-Forecasting-Retail.git`
2. Navigate to the project folder: `cd Project-6---Demand-Forecasting-Retail`
3. Ensure that the dataset is in the `data` folder.
4. Run the main Python script: `python main.py`

## Results
- The demand forecasts are visualized using line plots, showing trends and patterns over time.
- Model performance is evaluated using metrics like MAE and RMSE, with results provided in the final report.

## Files and Folders
```bash
Project-6---Demand-Forecasting-Retail
│   README.md
│   LICENSE
│   .gitignore
│
├───data
│    └── historical_sales_data.csv (contains sales data)
│
├───models
│    └── random_forest_model.pkl (contains trained model)
│
├───notebooks
│    └── Demand_Forecasting_Retail.ipynb (Jupyter Notebook with analysis)
│
├───reports
│    └── Demand_Forecasting_Report.pdf (final report)
│
└───scripts
     └── demand_forecasting.py (Python script for running analysis)
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

