🧠 Objectives

The goal of this project was to analyze Superstore sales data, uncover performance insights across categories, regions, and segments, and build a robust time series forecasting model to predict future sales and profit trends for the next 12 months.  

⚙️ Tools 

| Tool / Library                 | Purpose                 | Description                                                                                 |
| ------------------------------ | ----------------------- | ------------------------------------------------------------------------------------------- |
| **Python (Jupyter Notebook)**  | Development Environment | Interactive environment for end-to-end data analysis and visualization.                     |
| **Pandas**                     | Data Handling           | Data cleaning, transformation, grouping, and aggregation for structured analysis.           |
| **NumPy**                      | Numerical Computation   | Mathematical and statistical calculations used for metrics like profit margins and RMSE.    |
| **Matplotlib & Seaborn**       | Data Visualization      | Generated bar charts, heatmaps, and trend lines for EDA and forecast visualization.         |
| **Prophet (by Meta/Facebook)** | Forecasting Model       | Time-series model for predicting monthly sales and profit trends with seasonality handling. |
| **Scikit-learn (metrics)**     | Model Evaluation        | Computed forecast accuracy (RMSE, MAPE) to assess model reliability.                        |
| **OpenPyXL**                   | Excel Export            | Exported forecast results and summaries into Excel for reporting.                           |

Exploratory Data Analysis (EDA)

Studied category, region, and segment-wise performance.

Found that Technology and Office Supplies lead profits.

Identified that Furniture suffers low profit due to discounts.

Discovered strong Q4 seasonality in sales.

💡 Key Insights

Focus on Technology & Office Supplies — they drive over 90% of profits.

Reassess Furniture pricing — heavy discounts cause profit erosion.

Increase inventory for Copiers, Phones, Accessories — high ROI products.

Regional strategy:

Expand marketing in South & Central to balance regional contribution.

Strengthen distribution in West & East for sustained dominance.

Demand Planning:

Stock up from September–November to capture Q4 spikes.

Optimize inventory post-December to avoid overstock.

Discount Management:

Moderate discounts (<15%) maintain profitability; deeper cuts reduce margins drastically.

📊 Visuals 

Visual Insights

Forecast Graph: Shows clear upward trend with recurring yearly seasonality.

Confidence Intervals: Narrow → high model certainty.

Profit Trend: Follows sales closely but with higher volatility due to discounts.

🏁 Conclusions & Recommendations# Superstore-EDA-and-SALES-FORECASTING

This project delivered a complete data-driven understanding of Superstore’s performance and a forecasting model that reliably predicts future trends.

In summary:
Clean, accurate, and high-quality dataset.
Strong insights into category, regional, and temporal trends.
Optimized Prophet model delivering <13% error margin.

Practical, actionable business recommendations for profitability growth.
