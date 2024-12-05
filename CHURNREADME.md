# Churn Insights

this code attempts to forecast which consumers may depart in the future and explains why customers discontinue using a service (a phenomenon known as "customer churn"). We employ a computer model to identify potential customers based on historical data and trends, allowing businesses to take action to retain satisfied clients.


## Acknowledgements

 The dataset and project objectives were provided by Pace University and Professor Krystyn Gutu as part of the CS675 course, Introduction to Data Science.
 
Open-source libraries that make data exploration easier and produce informative results include SweetViz and pandas-profiling.
For conventional exploratory data analysis and visualization, use NumPy, pandas, matplotlib, seaborn, and statsmodels.

## Installation




```
NumPy: For numerical computations.
pip install numpy

pandas: For data manipulation and analysis
pip install pandas

matplotlib and seaborn: For data visualization.
pip install matplotlib seaborn

statsmodels: For statistical modeling and hypothesis testing
pip install statsmodels

pandas-profiling: For generating comprehensive EDA reports.
pip install ydata-profiling

SweetViz: For creating visual and interactive data reports.
pip install sweetviz

scikit-learn: For dataset splitting and further analysis if needed.
pip install scikit-learn


## Color Reference

Churn Analysis Visualizations

	1.	Churned Customers:
	•	Use Red (#E74C3C) to highlight customers who have churned, representing negative outcomes.
	2.	Retained Customers:
	•	Use Green (#27AE60) to indicate positive outcomes (customers retained).

Payment Method Comparisons

	1.	Bank Transfer:
	•	Use Blue (#3498DB) for better visibility and association with financial services.
	2.	Credit Card:
	•	Use Orange (#E67E22) to differentiate payment methods.

Heatmaps (Correlation Matrices)

	•	Use a diverging color scheme to show correlations:
	•	Negative Correlations: Blue (#5DADE2).
	•	Neutral Values: White (#FFFFFF).
	•	Positive Correlations: Red (#E74C3C).

Bar Chart Categories

	•	Assign distinct and consistent colors for categories:
	•	Gender:
	•	Male: Cyan (#1ABC9C).
	•	Female: Pink (#F1948A).
	•	Senior Citizen:
	•	Yes: Orange (#F39C12).
	•	No: Gray (#BDC3C7).

Confusion Matrices and Metrics

	•	Use a monochromatic blue palette:
	•	Dark Blue (#2C3E50) for high values.
    Light Blue (#AED6F1) for low values.

