# Day 3 — Exploratory Data Analysis (EDA) — Titanic Dataset

## Dataset
Titanic dataset with columns:
`pclass`, `name`, `sex`, `age`, `sibsp`, `parch`, `ticket`, `fare`, `cabin`, `embarked`, `survived`.

Input file: `titanic.csv`

## Deliverables Completed
- EDA notebook
- Dataset shape, data types, missing values, duplicates
- Descriptive and summary statistics
- Correlation heatmap
- 8 meaningful visualizations
- Distribution and outlier analysis
- Relationship analysis
- Top 5 analytical insights
- Interview question answers

## Visualizations
1. Survival distribution
2. Passenger class distribution
3. Age histogram
4. Fare boxplot for outliers
5. Survival rate by passenger class
6. Survival rate by gender
7. Age by survival status
8. Numeric correlation heatmap

## How to Run
Keep `titanic.csv` in the same folder as `Day3_Titanic_EDA.ipynb`.

Install:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open the notebook in Jupyter or VS Code and select **Run All**.

## Key Insights
- Survival is associated with passenger class.
- Survival rates differ substantially by gender.
- Fare is strongly right-skewed and contains potential high-value outliers.
- Passenger ages have a broad distribution and should be examined alongside survival.
- `sibsp` and `parch` can be combined into `family_size` to explore family-related survival patterns.
