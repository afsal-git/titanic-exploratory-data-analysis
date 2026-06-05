# Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Objective
The objective of this project is to perform a rigorous visual and statistical exploratory data analysis (EDA) on the classic Titanic dataset. By leveraging Python's scientific computing stack, this workflow uncovers hidden patterns, extracts distribution properties, isolates structural anomalies, and evaluates the multi-variable demographic relationships that directly influenced survival outcomes during the disaster.

## Key Technical Workflows

### 1. Structural Audit & Descriptive Statistics
* Utilized `.info()` to analyze data types and map missing data profiles across feature columns.
* Deployed `.describe()` to isolate central tendencies, positional ranges, and deviations for numerical fields.
* Used `.value_counts()` to audit categorical balances for features like target survival, gender, and passenger classes.

### 2. Statistical Data Visualizations
* **Histograms:** Formulated continuous distributions with Kernel Density Estimate (KDE) curves to evaluate passenger age groups and ticket fare skewness.
* **Boxplots:** Isolated price dispersion across socioeconomic tiers and analyzed median age spreads filtered by survival status.
* **Scatterplots:** Mapped multiple data axes simultaneously (Age vs. Fare vs. Class) to identify spatial survival clusters.
* **Correlation Heatmaps:** Computed a linear coefficient matrix to measure feature relationships and dependency weights.
* **Pairplots:** Structured a comprehensive multi-variable grid layout to observe dual-axis data variations at a glance.

## Tools and Libraries Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## Summary of Core Insights
* **The Gender Interaction Rule:** Gender served as a primary binary separator of survival variance. Cross-tabulations reveal that female passengers achieved a 74.20% survival rate, whereas male mortality reached 81.11%.
* **Socioeconomic Stratification:** Clear structural advantages were visible based on ticket tier. First-class passengers achieved a 62.96% survival rate, while third-class passengers faced a 24.24% survival baseline, indicating a strong link between economic status, cabin depth, and evacuation priority.
* **Data Integrity Anomalies:** The presence of $0.00 ticket values represents a clear baseline data anomaly. Furthermore, the extreme maximum fare outlier of $512.33 introduces steep mathematical right-skewness, highlighting the need for log-scaling transformations prior to distance-based machine learning deployment.

## Project Deliverables
* **`Exploratory_Data_Analysis.ipynb`:** The complete Jupyter Notebook containing the written code segments, cell executions, and inline markdown observations for every visual plot.
* **`titanic_eda_report.pdf`:** A clean, executive-ready PDF document compiling the data findings, statistical distribution summary charts, and final analytical conclusions.
