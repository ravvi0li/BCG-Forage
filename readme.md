
# BCG Forage – GenAI Financial Analysis

## Project Overview

This project is part of the BCG Forage GenAI virtual experience.

The objective is to analyse the financial performance of Microsoft, Tesla and Apple using their annual 10-K filings from 2023 to 2025.

## Objectives

- Extract key financial information from SEC 10-K filings.
- Clean and organise financial data using Python.
- Calculate year-over-year financial growth.
- Identify trends in revenue, profitability, assets, liabilities and operating cash flow.
- Generate insights that could support the development of an AI-powered financial chatbot.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Visual Studio Code
- Git & GitHub

## Project Structure

```text
BCG-Forage/
│
├── data/
│   └── financial_data.csv
│
├── financial_analysis.ipynb
├── README.md
└── .gitignore
```

## Financial Metrics

The analysis covers:

1. Total Revenue
2. Net Income
3. Total Assets
4. Total Liabilities
5. Cash Flow from Operating Activities

All financial figures are in USD millions.

## Data Sources

Financial data was manually extracted from the SEC EDGAR database:

- [Microsoft](https://www.sec.gov/edgar/browse/?CIK=789019&owner=exclude)
- [Tesla](https://www.sec.gov/edgar/browse/?CIK=1318605&owner=exclude)
- [Apple](https://www.sec.gov/edgar/browse/?CIK=320193&owner=exclude)

## Analysis

The Jupyter Notebook contains the data preparation, validation, year-over-year growth calculations and financial trend analysis.


