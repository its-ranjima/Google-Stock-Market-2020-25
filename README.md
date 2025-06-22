# Google-Stock-Market-2020-25
This project provides a detailed exploratory data analysis (EDA) of **GOOGL (Google) stock prices** from 2020 to 2025 using Python. It includes data cleaning, feature engineering, and insightful visualizations to uncover trends, volatility, and stock behavior over time.


## 📊 Project Steps

1. **Data Cleaning**  
   - Removed rows with null values in critical columns.
   - Converted date format and parsed numerical data types.
2. **Feature Engineering**
   - Extracted `Year` and `Month` from date.
   - Calculated `MA7`, `MA21` (moving averages).
   - Computed `Price_Range` as `High - Low`.
3. **Visualizations (10 Professional Graphs)**
   - Time series plots, moving averages, boxplots, histograms, heatmaps, scatter plots, and more.
4. **Statistical Insights**
   - Correlation matrix, distribution analysis, and trend behavior across years and months.



## 📌 Key Insights

- GOOGL stock showed a **consistent upward trend** over 2020–2025, with only minor dips during high-volatility periods.
- **Moving averages (MA7 & MA21)** offered insights into market direction and potential buy/sell points.
- Strong correlation among `Open`, `High`, `Low`, and `Close` prices (>0.98), indicating price stability.
- **Volume surges** did not always correspond with price spikes, indicating independent trading activity.
- **Highest volatility** was observed in 2021 and 2024 as per boxplot analysis.
- **Right-skewed price distribution**, with most closing prices below the mean but few high outliers.
- Monthly averages demonstrated **sustained long-term growth**, reinforcing GOOGL as a strong investment candidate.

---

## Tools & Libraries Used

- Python, Pandas, NumPy
- Seaborn & Matplotlib (visualizations)
- Plotly (interactive plots)
- Jupyter Notebook


