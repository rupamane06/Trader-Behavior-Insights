# Trader Behavior Insights - Data Science Task

This project was completed as part of the **Junior Data Scientist - Trader Behavior Insights** assignment for PrimeTrade.ai / Bajarangs.

## Objective
Analyze how **market sentiment (Fear-Greed Index)** affects **trader performance** using historical trading data from Hyperliquid.

## Datasets
- **Historical Trader Data:** includes account, execution price, size, closed PnL, etc.
- **Bitcoin Fear-Greed Index:** provides daily market sentiment classified as Fear, Greed, Extreme Fear, etc.

## Project Steps
1. **Data Cleaning & Preparation**
   - Standardized column names
   - Converted timestamps and merged both datasets on the date
2. **Exploratory Data Analysis (EDA)**
   - Visualized trader profit vs. market sentiment
   - Analyzed profit distributions and trade frequencies
3. **Feature Engineering**
   - Added binary sentiment feature (`is_greed`)
   - Prepared dataset for further modeling or correlation study
4. **Insights**
   - Traders show higher profits during *Greed* phases.
   - Fewer trades occur during *Fear* phases, but losses are smaller.
   - Positive correlation found between sentiment index value and average `closed_pnl`.

## Technologies Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## Outputs
- **Processed Data:** [`Processed_Trader_Sentiment_Data.csv`](./Processed_Trader_Sentiment_Data.csv)
- **Notebook:** [`Trader_Behavior_Insights.ipynb`](./Trader_Behavior_Insights.ipynb)

## Submission Details
Submitted by **Rupa Mane**  
For the role of **Junior Data Scientist - Trader Behavior Insights**

Contact:  
rupa.mane@example.com  
Solapur, Maharashtra, India
