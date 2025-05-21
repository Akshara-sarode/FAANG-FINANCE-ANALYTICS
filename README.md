## 📊 FAANG Finance Analytics Dashboard – README

## 📌 Overview
- This Power BI dashboard provides an end-to-end financial analysis of the FAANG companies — Facebook, Apple, Amazon, Netflix, and Google — using key performance metrics from 2005 to 2024. It supports data-driven decision-making by visualizing trends, comparing company performance, and identifying financial strengths and risks.

## 🎯 Objective
- To design a dynamic and interactive analytics dashboard that showcases:
- Historical and comparative financial performance
- Key metrics like EPS, Net Income, Free Cash Flow, and Market Cap
- Company contributions and financial ratios
- Time-based trend analysis
- Risk vs. return evaluation

## 🧾 Dataset Description

## 📁 Source: Kaggle FAANG Finance Dataset 
https://www.kaggle.com/datasets/rudraprasadbhuyan/faang-finance-dataset/data

## 🔢 Fields Include

Company, Date, Market Cap, Net Income, Free Cash Flow, Dividends Paid, EPS, Beta (5Y), Debt to Equity, Operating Income, Volume

## 🕒 Time Period
- 2005 to 2024

## 🧹 Preprocessing
- Cleaned and filtered for latest snapshots and relevant KPIs; appropriately applied aggregation (sum, average).

## 📌 Key Visuals & Insights
## 📈 1. Stock Price Trend Over Time
- Line chart showing the average Close price from 2005–2024
- Highlights growth trajectories for each FAANG company

## 📉 2. Volume Analysis Over Time
- Area chart depicting trading volume fluctuations
- Notable peak around 2009–2010 (Apple/Google)

## 💰 3. Dividends Paid vs Free Cash Flow
- Bar chart comparing payout vs available capital
- Apple leads in both metrics, followed by Amazon and Google

## 🏛️ 4. Market Capitalization Comparison
- Horizontal bar chart of total market cap by company
- Apple holds the highest market valuation

## 🧮 5. Net Income Contribution (Matrix)
- Matrix shows each company’s percentage share of net income year-over-year
- Totals adjusted to 100% using column % feature (no DAX)

## 🧭 6. Risk vs Return (Scatter Plot)
- Beta (5Y) on X-axis, Net Income on Y-axis, bubble size = Market Cap
- Allows visual identification of high-return vs low-volatility companies

## 🧠 7. EPS Benchmark
- Card visual highlighting average EPS across all companies
- Great snapshot for investment performance

## 🍰 8. Company’s Contribution to Net Income (Pie Chart)
- Distribution of total net income shares is visually broken down by company

## ⏳ 9. Free Cash Flow Comparison (Funnel Chart)
- Shows how much capital flows through each company
- Ranked from Apple (429T) to Facebook (100T)

## 📌 Technical Highlights
## 🛠 Tools: Power BI, Kaggle Dataset, built-in aggregation

## 📊 Visualizations: Bar, Line, Area, Matrix, Pie, Funnel, Card, Gauge, KPI, Scatter

## 🧠 Analytical Features:

- "Show value as → % of column total"
- Conditional formatting and hierarchy usage
- Legend-based interactivity and slicers

## 🧪 FAANG Financial Analysis Summary
- Apple dominates in Market Cap, Free Cash Flow, and EPS
- Amazon shows consistent Net Income and Dividend growth
- Netflix lags in profitability but remains steady in earnings
- Google and Facebook contribute significantly to risk-adjusted returns
- EPS across FAANG averaged 19.56, reflecting strong profitability
- Risk vs Return reveals Facebook and Google as relatively efficient performers
