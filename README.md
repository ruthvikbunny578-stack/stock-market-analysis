# stock-market-analysis
Analyzed 22 years of Indian NIFTY index data across 5 sectors using Excel, Tableau and Power BI

📈 Indian Stock Market Analysis

📋 Project Overview
An end-to-end Indian Stock Market Analytics project analyzing 22+ years of NIFTY index data across 5 major sectors — NIFTY50, BANK, ENERGY, FMCG and AUTO. The project uncovers sector performance trends, volatility patterns and price movements to support investment decision-making.

🎯 Business Questions Answered

Which Indian market sector gave the best returns over 22 years?
Which sector is the most volatile and risky for investors?
What are the monthly and seasonal price trends across sectors?
How much have Indian indices grown from their all-time lows to highs?
Which months consistently show positive or negative returns?


🛠️ Tools Used
ToolPurposeExcelData cleaning, formatting, Daily Return % calculation and Summary analysisTableau4-chart interactive dashboard with price trends and heatmapsPower BIKPI cards, interactive report with slicer filtering

📊 Data Overview

Source: Kaggle — Indian Stock Market Index Dataset
Period: 2000 — 2022 (22+ years)
Indices Covered: NIFTY50, NIFTY BANK, NIFTY ENERGY, NIFTY FMCG, NIFTY AUTO
Total Records: 18,335+ trading days across all indices
Columns: Date, Open, High, Low, Close, Daily Return %


🔍 Analysis Performed
Excel

Imported 5 raw CSV files from Kaggle dataset
Applied Text to Columns to fix CSV formatting
Handled 1,368 missing rows in BANK dataset
Calculated Daily Return % using formula: =((Close-PrevClose)/PrevClose)*100
Created MASTER sheet consolidating all 5 indices
Built Summary sheet with MAX, MIN, AVG, STDEV formulas per index
Applied conditional formatting on Summary sheet

Tableau Dashboard (4 Charts)

Closing Price Trend — Multi-line chart showing price history
Average Daily Return — Bar chart comparing sector returns
Volatility Heatmap — Monthly return heatmap (Red/Green)
High & Low Prices — Dual bar chart showing all-time high vs low

Power BI Report

KPI Cards — Avg Daily Return, All Time High Price, Total Trading Days, Market Volatility
Yearly Price Trend — Line chart with year-wise closing prices
Avg Return by Index — Bar chart with conditional green/red colors
Monthly Average Close — Area chart showing seasonal patterns
Volatility by Index — Column chart using Standard Deviation
Index Slicer — Interactive filter to drill down by sector


💡 Key Insights
MetricFindingBest ReturnBANK (0.073% avg daily return)Most StableFMCG (lowest volatility: 1.09 std dev)Most VolatileBANK (highest std dev: 1.85)Biggest GrowthFMCG (grew from ₹8,157 to ₹42,978)All Time HighFMCG at ₹42,978Most DataNIFTY50 with 5,645 trading days

👤 Author
Ruthvik | Data Analyst
