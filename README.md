
Navigation Menu
New-Zealand-birth-analysis-and-model

Code
Issues
Pull requests
New-Zealand-birth-analysis-and-model
/README .md
0luwanishola
0luwanishola
5 hours ago
139 lines (104 loc) · 4.27 KB

Preview

Code

Blame
New Zealand Births Analysis & Prediction Model (2005-2022)
A comprehensive data analysis and machine learning project exploring birth trends across New Zealand regions from 2005 to 2022.

Birth Trends

Project Overview
This project analyzes 18 years of birth data across New Zealand regions to:

Understand temporal trends and growth rates
Identify key patterns and turning points
Build predictive models using machine learning
Explore regional variations in birth counts
Key Findings
Temporal Trends
Peak Year: 2008 with 64,344 births
Overall Change: +1.9% from 2005 to 2022
COVID-19 Impact: Significant decline in 2020
Recent Recovery: Uptick observed in 2021-2022
Regional Patterns
Auckland dominates: ~36% of national births
Top 3 regions (Auckland, Canterbury, Waikato) account for ~60% of total births
Regional stability: Top regions maintain consistent rankings throughout the period
Model Performance
Best Model: Random Forest Regressor
R² Score: 0.9976 (99.76% accuracy)
Key Predictor: Region (85% importance)
📁 Project Structure
New-Zealand-Births-Model/
│
├── data/                          # Raw data files
│   └── bd-dec22-births-deaths-by-region.csv
│
├── notebooks/                     # Jupyter notebooks
│   ├── 01_exploratory_analysis.ipynb    # EDA & visualizations
│   └── 02_ml_prediction_model.ipynb     # ML modeling
│
├── images/                        # Generated visualizations
│   ├── birth_temporal_trend.png
│   ├── yoy_growth_rate.png
│   └── ... (other charts)
│
└── README.md                      # Project documentation
🔧 Technologies Used
Python 3.x
pandas - Data manipulation and analysis
numpy - Numerical computations
matplotlib & seaborn - Data visualization
scikit-learn - Machine learning models
scipy - Statistical analysis
🚀 Getting Started
Prerequisites
pip install pandas numpy matplotlib seaborn scikit-learn scipy
Running the Analysis
Clone the repository
git clone https://github.com/0luwanishola/New-Zealand-Births-Model.git
cd New-Zealand-Births-Model
Run Exploratory Analysis Open notebooks/01_exploratory_analysis.ipynb in Jupyter Notebook

Run ML Model Open notebooks/02_ml_prediction_model.ipynb in Jupyter Notebook

📈 Analysis Components
1. Exploratory Data Analysis (EDA)
Temporal trend analysis with linear regression
Year-over-year growth rate calculations
Cumulative change from baseline (2005)
Moving averages for trend smoothing
Pre/Post peak period comparisons
2. Machine Learning Model
Feature engineering (region categorization by size)
Train-test split (80-20)
Model comparison: Linear Regression vs Random Forest
Feature importance analysis
Model evaluation (MAE, RMSE, R²)
📊 Key Visualizations
Visualization	Description
Temporal Trend	Birth counts over time with trend line
YoY Growth Rate	Annual percentage changes
Cumulative Change	Change from 2005 baseline
Smoothed Trends	Moving averages (3-year & 5-year)
Period Comparison	Pre-peak vs Post-peak analysis
Model Performance	Actual vs Predicted births
Feature Importance	Key factors driving predictions
🎓 Learning Outcomes
This project demonstrates:

Time series analysis techniques
Feature engineering strategies
Model selection and comparison
Data visualization best practices
Statistical trend analysis
Machine learning fundamentals
📝 Data Source
Data sourced from New Zealand official statistics on births and deaths by region (December 2022).

🤝 Contributing
This is a learning project. Feel free to fork and experiment!

📧 Contact
Questions? Feel free to reach out or open an issue!

📄 License
This project is open source and available for educational purposes.

Note: This project was created as part of my data science learning journey, focusing on real-world demographic data analysis.
