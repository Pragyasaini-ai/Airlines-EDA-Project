# Airlines Exploratory Data Analysis (EDA)

## Project Overview
This project analyzes airline passenger data to understand customer satisfaction across travel classes and explore flight delay patterns.

## Objectives
- Clean and prepare the airline passenger dataset.
- Analyze overall passenger satisfaction.
- Compare satisfaction across Business, Eco, and Eco Plus classes.
- Examine departure and arrival delays.
- Identify business insights and recommend service improvements.

## Dataset
- **Total records:** 103,904
- **Columns after cleaning:** 24
- **Dataset file:** `data/train.csv`
- **Missing values:** Missing arrival-delay values were filled using the median.
- **Duplicate records:** No duplicate rows were found.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings
1. 43.33% of passengers were satisfied, while 56.67% were neutral or dissatisfied.
2. Business Class had the highest satisfaction rate at 69.43%.
3. Eco Class had the lowest satisfaction rate at 18.61%.
4. Average departure delay was 14.82 minutes.
5. Average arrival delay was 15.13 minutes.

## Visualizations
The `visualizations/` folder contains:
- `satisfaction_distribution.png`
- `class_satisfaction.png`
- `flight_delay_distribution.png`

## Recommendations
- Investigate factors associated with low satisfaction in Eco Class.
- Review service ratings, including online boarding, seat comfort, and in-flight entertainment.
- Monitor flight delays and investigate long-delay cases.
- Collect additional loyalty-program and delay-reason data for future analysis.

## Project Structure
```text
Airlines_EDA_Project/
├── data/
│   └── train.csv
├── visualizations/
│   ├── satisfaction_distribution.png
│   ├── class_satisfaction.png
│   └── flight_delay_distribution.png
├── Airlines_EDA.ipynb
└── README.md
```

## Conclusion
This analysis highlights differences in passenger satisfaction across travel classes and summarizes departure and arrival delay patterns. The findings can help guide further investigation into passenger experience and airline punctuality.