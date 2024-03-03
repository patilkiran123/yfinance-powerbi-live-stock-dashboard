# Stock Analysis with Power BI and Yahoo Finance

This repository contains the code and resources for a Power BI dashboard that displays live stock data from Yahoo Finance.

![Power BI dashboard](artifacts/stocks%20historical%20+%20live_page.jpg)

## Description

This project uses Power BI to visualize and analyze real-time stock data. It leverages the following components:

- **Data Source:** Yahoo Finance
- **Data Access:** Through their website https://finance.yahoo.com/lookup/
- **Local Data:** "stockquotes.xlsx" containing company names and their sectors.
- **Visualization Tool:** Power BI
- **Access Management:** Row-Level Security (RLS) based on user expertise in specific sectors.

Getting Started

1. **Download the repository:** Clone or download this repository locally.
2. **Set up Power BI Desktop:** Install and launch the latest version of Power BI Desktop.
3. **Import data:**
   - **Live data:** In Power BI Desktop, connect to the "Yahoo Finance" data source and utilize the URL mentioned to access specific stock information.
   - **Local data:** Import the "stockquotes.xlsx" file into Power BI Desktop.
4. **Create your reports and visualizations:** Utilize Power BI's features to create insightful dashboards and reports for stock analysis.
5. **Configure RLS (optional):** Enable RLS in Power BI Desktop to restrict user access to data based on their expertise in specific sectors categorized in the "stockquotes.xlsx" file.

## Disclaimer

This project is for educational purposes only and does not constitute financial advice. Users are advised to conduct their own research and due diligence before making any investment decisions.
