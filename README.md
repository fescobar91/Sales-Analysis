# Sales Analysis - Australian Apparel Q4 2020

**Author:** Francisco Escobar Rivas

## 📊 Project Overview

This project performs a comprehensive sales analysis of Australian apparel sales data for Q4 2020. The analysis covers data wrangling, normalization, exploratory data analysis, and visualization to provide actionable insights for Sales & Marketing teams.

## 📁 Dataset

- **File:** `AusApparalSales4thQrt2020.csv`
- **Time Coverage:** Q4 2020 (October - December)
- **Grain:** Transaction-level records
- **Geographic Coverage:** Australian states (VIC, NSW, SA, QLD, WA, NT, TAS)
- **Demographics:** Kids, Women, Men, Seniors

## 🔍 Analysis Sections

### 1. Data Wrangling
- Data quality audit (null values, duplicates)
- Normalization using IQR-based winsorization + Min-Max scaling
- GroupBy operations for state and demographic analysis

### 2. Data Analysis
- **Descriptive Statistics:** Sales and unit distributions
- **State Analysis:** Revenue performance across Australian states
- **Demographic Analysis:** Performance by customer groups
- **Temporal Analysis:** Daily, weekly, monthly, and quarterly trends

### 3. Visualizations
- State × Group heatmaps (absolute and relative performance)
- Grouped bar charts by demographics
- Day-of-week revenue patterns
- Time series analysis (daily, weekly, monthly, quarterly)

## 📈 Key Findings

- **Top States:** VIC (A$102.47M), NSW (A$74.97M), SA (A$58.86M)
- **Demographics:** Balanced performance across all groups (~25% each)
- **Temporal Patterns:** Peak days are Tuesday-Thursday; steady growth through December
- **Revenue Drivers:** State scale matters more than demographic mix

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical computations
- **Matplotlib:** Base plotting
- **Seaborn:** Statistical visualizations
- **Jupyter Notebook:** Interactive analysis environment

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis

1. Clone this repository
2. Ensure `AusApparalSales4thQrt2020.csv` is in the project directory
3. Open `SalesAnalysis.ipynb` in Jupyter Notebook or VS Code
4. Run all cells sequentially

## 📊 Outputs

The notebook generates:
- Descriptive statistics tables
- State and demographic rankings
- Heatmaps for state × group analysis
- Time series visualizations
- Day-of-week performance charts

## 💡 Business Recommendations

1. **Scale States (VIC, NSW, SA):** Protect and extend market share through inventory optimization and localized campaigns
2. **Recovery States (WA, NT, TAS):** Focus on unit uplift through bundles and cross-sell strategies
3. **Demographic Strategy:** Prioritize unit-per-order increases, especially for Seniors segment
4. **Timing:** Launch high-conversion campaigns on Tuesday-Thursday

## 📝 License

This project is available for educational and analytical purposes.

## 👤 Contact

**Francisco Escobar Rivas**

---

*Analysis completed as part of sales performance evaluation for Australian apparel market Q4 2020*
