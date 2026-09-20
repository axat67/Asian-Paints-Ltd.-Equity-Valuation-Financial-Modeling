# 📊 Project Dashboard

![Dashboard](screenshots/dashboard.png)

---

# 📌 Project Overview

This project builds an end-to-end equity valuation model for **Asian Paints Ltd.** using consolidated financial statements for FY23–FY26 and forecasts for FY27E–FY31E.

The model combines fundamental financial analysis with valuation techniques commonly used in equity research, investment analysis, financial planning, and corporate finance.

### The project covers:

- Historical Income Statement Analysis
- Historical Balance Sheet Analysis
- Historical Cash Flow Analysis
- Financial Ratio Analysis
- Financial Forecasting
- Assumption Building
- Working Capital Modeling
- Capital Expenditure Modeling
- WACC / CAPM
- Free Cash Flow to Firm (FCFF)
- Discounted Cash Flow (DCF) Valuation
- Comparable Company Analysis
- Sensitivity Analysis
- Valuation Summary
- Equity Research Dashboard

---

# 🎯 Project Objective

The objective was to build a complete financial model capable of:

1. Analyzing historical financial performance
2. Evaluating profitability, liquidity, leverage and efficiency
3. Forecasting future financial performance
4. Estimating the company's cost of capital
5. Calculating intrinsic value using a DCF model
6. Valuing the company using comparable-company multiples
7. Testing valuation sensitivity to key assumptions
8. Comparing intrinsic and market-based valuation
9. Presenting the analysis through an equity research-style dashboard

---

# 🏢 Company

**Asian Paints Ltd.**

| Item | Details |
|---|---|
| Industry | Paints & Coatings |
| Historical Period | FY23–FY26 |
| Forecast Period | FY27E–FY31E |
| Financial Statements | Consolidated |
| Currency | ₹ Crore |
| Modeling Tool | Microsoft Excel |

---

# 📁 Model Structure

The Excel workbook contains the following sections:

| Sheet | Purpose |
|---|---|
| Cover | Project identification |
| Company Overview | Company and industry context |
| Historical Financials | FY23–FY26 financial statements |
| Financial Ratios | Profitability, liquidity, leverage and efficiency analysis |
| Assumptions | Forecast and valuation assumptions |
| Forecast | FY27E–FY31E projections |
| WACC | Cost of capital calculation |
| DCF Valuation | Intrinsic value calculation |
| Comparable Companies | Relative valuation |
| Sensitivity Analysis | WACC vs. terminal growth analysis |
| Valuation Summary | Consolidated valuation outputs |
| Dashboard | Equity research-style visual summary |

---

# 📑 Historical Income Statement Analysis

The model analyzes Asian Paints' consolidated income statement from FY23 to FY26.

The analysis includes:

- Revenue
- Operating Revenue
- Other Income
- Material Costs
- Employee Costs
- Other Expenses
- EBITDA
- Finance Costs
- Depreciation & Amortization
- EBIT
- Profit Before Tax
- Tax
- Profit After Tax
- Earnings Per Share

### FY26 Income Statement Highlights

| Metric | FY26 |
|---|---:|
| Revenue | ₹35,583.54 Cr |
| EBITDA | ₹7,419.72 Cr |
| EBITDA Margin | 20.85% |
| PAT | ₹4,394.69 Cr |
| Diluted EPS | ₹45.11 |

### Key Observation

Asian Paints experienced a decline in profitability during FY25 followed by a recovery in FY26.

EBITDA increased from **₹6,578.82 Cr in FY25 to ₹7,419.72 Cr in FY26**, while PAT increased from **₹3,709.71 Cr to ₹4,394.69 Cr**.

![Income Statement](screenshots/income-statement.png)

---

# 🏦 Historical Balance Sheet Analysis

The consolidated balance sheet was analyzed across FY23–FY26 to evaluate the company's asset base, capital structure and liabilities.

The model includes:

### Assets

- Property, Plant & Equipment
- Right-of-Use Assets
- Capital Work-in-Progress
- Goodwill
- Intangible Assets
- Investments
- Trade Receivables
- Inventories
- Cash & Cash Equivalents
- Other Current and Non-Current Assets

### Equity & Liabilities

- Equity Share Capital
- Other Equity
- Non-Controlling Interest
- Borrowings
- Lease Liabilities
- Trade Payables
- Other Financial Liabilities
- Provisions
- Tax Liabilities

### FY26 Balance Sheet Highlights

| Metric | FY26 |
|---|---:|
| Total Assets | ₹34,534.49 Cr |
| Total Equity | ₹22,014.98 Cr |
| Non-Current Liabilities | ₹3,382.48 Cr |
| Current Liabilities | ₹9,137.03 Cr |
| Debt-to-Equity | 0.10x |

The balance sheet remained relatively conservatively leveraged, with debt-to-equity of approximately **0.10x** in FY26.

![Balance Sheet](screenshots/balance-sheet.png)

---

# 💵 Historical Cash Flow Analysis

The cash flow statement analyzes operating, investing and financing cash flows for FY23–FY26.

The model covers:

- Operating Profit
- Working Capital Changes
- Cash Generated from Operations
- Income Taxes Paid
- Net Cash from Operating Activities
- Capital Expenditure
- Asset Sales
- Investing Activities
- Interest & Dividend Receipts
- Financing Activities
- Net Change in Cash

### Net Cash From Operating Activities

| Year | Net CFO |
|---|---:|
| FY23 | ₹4,193.43 Cr |
| FY24 | ₹6,103.60 Cr |
| FY25 | ₹4,423.96 Cr |
| FY26 | ₹7,088.18 Cr |

FY26 operating cash flow increased to **₹7,088.18 Cr**, reflecting a significant recovery in cash generation compared with FY25.

![Cash Flow Statement](screenshots/cash-flow.png)

---

# 📈 Financial Ratio Analysis

The model calculates key profitability, liquidity, leverage and efficiency ratios.

### Ratios Covered

- Revenue Growth
- EBITDA Margin
- EBIT Margin
- Net Profit Margin
- ROE
- ROCE
- Debt-to-Equity
- Current Ratio
- Asset Turnover
- Interest Coverage

### FY26 Ratio Snapshot

| Ratio | FY26 |
|---|---:|
| Revenue Growth | 4.95% |
| EBITDA Margin | 20.85% |
| EBIT Margin | 17.40% |
| Net Profit Margin | 12.35% |
| ROE | 20.88% |
| ROCE | 25.93% |
| Debt-to-Equity | 0.10x |
| Current Ratio | 2.21x |
| Asset Turnover | 1.03x |
| Interest Coverage | 31.68x |

![Financial Ratios](screenshots/financial-ratios.png)

---

# 🔮 Financial Forecast

The model forecasts Asian Paints from FY27E to FY31E.

Forecast assumptions include:

- Revenue Growth
- EBITDA Margin
- D&A as % of Revenue
- Tax Rate
- Accounts Receivable as % of Revenue
- Inventory as % of Revenue
- Accounts Payable as % of Revenue
- Capex as % of Revenue

## Revenue Forecast

| Year | Revenue |
|---|---:|
| FY26A | ₹35,583.54 Cr |
| FY27E | ₹37,362.72 Cr |
| FY28E | ₹39,230.85 Cr |
| FY29E | ₹40,996.24 Cr |
| FY30E | ₹42,636.09 Cr |
| FY31E | ₹44,341.53 Cr |

## EBITDA Forecast

| Year | EBITDA |
|---|---:|
| FY26A | ₹7,419.72 Cr |
| FY27E | ₹7,846.17 Cr |
| FY28E | ₹8,434.63 Cr |
| FY29E | ₹9,019.17 Cr |
| FY30E | ₹9,379.94 Cr |
| FY31E | ₹9,755.14 Cr |

The model assumes moderate revenue growth of approximately **4–5% annually**, with EBITDA margins gradually improving toward **22%** during the forecast period.

---

# 💰 WACC Calculation

The Weighted Average Cost of Capital is calculated using a CAPM-based cost of equity and an after-tax cost of debt.

## Key Assumptions

| Parameter | Assumption |
|---|---:|
| Risk-Free Rate | 6.50% |
| Equity Risk Premium | 6.00% |
| Beta | 0.90x |
| Pre-Tax Cost of Debt | 7.00% |
| Tax Rate | 25.00% |
| Terminal Growth Rate | 5.00% |
| **WACC** | **11.83%** |

### Cost of Equity

The model uses:

`Cost of Equity = Risk-Free Rate + Beta × Equity Risk Premium`

The resulting cost of equity is **11.90%**.

---

# 🧮 DCF Valuation

The DCF model uses a **Free Cash Flow to Firm (FCFF)** approach.

### Valuation Process

The model:

1. Forecasts EBIT
2. Calculates NOPAT
3. Adds back D&A
4. Deducts capital expenditure
5. Adjusts for changes in working capital
6. Calculates FCFF
7. Discounts future FCFF using WACC
8. Calculates terminal value
9. Converts enterprise value into equity value
10. Calculates intrinsic value per share

## DCF Output

| Metric | Value |
|---|---:|
| WACC | 11.83% |
| Terminal Growth | 5.00% |
| Enterprise Value | ₹72,754.28 Cr |
| Less: Debt | ₹2,293.26 Cr |
| Add: Cash | ₹672.83 Cr |
| Equity Value | ₹71,133.85 Cr |
| Shares Outstanding | 95.92 Cr |
| **DCF Intrinsic Value** | **₹741.60/share** |

![DCF Valuation](screenshots/dcf-valuation.png)

---

# 🏭 Comparable Company Analysis

Asian Paints is compared with selected industry peers:

- Berger Paints
- Kansai Nerolac
- Indigo Paints

The analysis uses:

- P/E
- EV/EBITDA
- EV/Sales

## Implied Valuation

| Method | Implied Value/Share |
|---|---:|
| P/E | ₹1,600.66 |
| EV/EBITDA | ₹1,454.45 |
| EV/Sales | ₹1,262.61 |
| **Average Comparable Value** | **₹1,439.24** |

![Comparable Companies](screenshots/comparable-companies.png)

---

# 📉 Sensitivity Analysis

The DCF valuation is tested across different combinations of:

- WACC
- Terminal Growth Rate

### WACC Range

**10.83% – 12.83%**

### Terminal Growth Range

**4.00% – 6.00%**

The sensitivity analysis demonstrates how changes in discount rate and terminal growth assumptions can materially affect the estimated intrinsic value.

![Sensitivity Analysis](screenshots/sensitivity-analysis.png)

---

# 📊 Valuation Summary

| Valuation Method | Implied Value/Share |
|---|---:|
| DCF | ₹741.60 |
| P/E | ₹1,600.66 |
| EV/EBITDA | ₹1,454.45 |
| EV/Sales | ₹1,262.61 |
| **Average Comparable Value** | **₹1,439.24** |
| Modeled Market Price | ₹1,620.00 |

### Valuation Observation

The DCF and comparable-company approaches produce materially different valuation outcomes.

The DCF produces a substantially lower value than the peer-based approaches, while the comparable-company methods produce values closer to the modeled market price.

This difference highlights the importance of:

- Cash-flow assumptions
- Working-capital assumptions
- WACC
- Terminal growth
- Industry valuation multiples

when interpreting an equity valuation.

---

# 🔍 Key Findings

### 1. Profitability Recovery

Asian Paints experienced a decline in profitability during FY25 followed by a recovery in FY26.

PAT increased from:

**₹3,709.71 Cr → ₹4,394.69 Cr**

while EBITDA increased from:

**₹6,578.82 Cr → ₹7,419.72 Cr**

---

### 2. Strong Balance Sheet Metrics

FY26 balance-sheet and coverage metrics include:

- Debt-to-Equity: **0.10x**
- Current Ratio: **2.21x**
- Interest Coverage: **31.68x**
- ROCE: **25.93%**

---

### 3. Moderate Growth Forecast

Revenue is projected to increase from:

**₹35,583.54 Cr in FY26A**

to:

**₹44,341.53 Cr in FY31E**

The forecast represents a moderate growth scenario rather than an aggressive expansion case.

---

### 4. Valuation Divergence

The largest difference in the model is between the DCF and relative valuation approaches.

**DCF:** ₹741.60/share

**Average Comparable Value:** ₹1,439.24/share

The difference demonstrates how valuation outcomes can vary depending on methodology and underlying assumptions.

---

### 5. Sensitivity of DCF Valuation

The sensitivity analysis demonstrates that the DCF valuation is particularly dependent on WACC and terminal growth assumptions.

Changes in these inputs can materially affect estimated intrinsic value.

---

# 💼 Skills Demonstrated

This project demonstrates practical skills relevant to **Financial Analyst, Equity Research, Investment Banking, Asset Management and Wealth Management** roles.

## Financial Modeling

- Integrated Financial Statement Modeling
- Historical Financial Analysis
- Financial Forecasting
- Assumption Building
- Working Capital Modeling
- Capital Expenditure Modeling
- FCFF Modeling

## Valuation

- Discounted Cash Flow (DCF)
- WACC
- CAPM
- Cost of Equity
- Cost of Debt
- Terminal Value
- Comparable Company Analysis
- P/E Valuation
- EV/EBITDA Valuation
- EV/Sales Valuation
- Sensitivity Analysis

## Financial Analysis

- Income Statement Analysis
- Balance Sheet Analysis
- Cash Flow Analysis
- Profitability Analysis
- Liquidity Analysis
- Leverage Analysis
- Efficiency Analysis
- Ratio Analysis
- ROE & ROCE Analysis

## Excel

- Cross-Sheet Referencing
- Financial Modeling Formulas
- Scenario & Sensitivity Modeling
- Conditional Formatting
- Financial Data Visualization
- KPI Design
- Dashboard Development
- Model Structuring

## Investment Analysis

- Intrinsic Valuation
- Relative Valuation
- Peer Benchmarking
- Market vs. Intrinsic Value Analysis
- Valuation Interpretation
- Equity Research

---

# 🖥️ Dashboard

The final dashboard consolidates the major outputs of the model into an equity research-style view.

It includes:

- Market Price
- DCF Intrinsic Value
- Comparable Valuation
- DCF Upside/Downside
- Revenue Forecast
- EBITDA Forecast
- Historical Profitability
- DCF Sensitivity Analysis
- Key Valuation Assumptions

---

# 🛠️ Tools Used

- **Microsoft Excel**
---

# 🛠️ Tools & Skills Demonstrated

## Tools

- Microsoft Excel

## Financial Modeling Skills

- Integrated Financial Statement Modeling
- Historical Financial Analysis
- Financial Forecasting
- Assumption Building
- Working Capital Modeling
- Capital Expenditure Modeling
- Free Cash Flow to Firm (FCFF) Modeling

## Valuation Skills

- Discounted Cash Flow (DCF) Valuation
- WACC Calculation
- CAPM
- Cost of Equity & Cost of Debt
- Terminal Value Calculation
- Comparable Company Analysis
- P/E Valuation
- EV/EBITDA Valuation
- EV/Sales Valuation
- Sensitivity Analysis

## Financial Analysis Skills

- Income Statement Analysis
- Balance Sheet Analysis
- Cash Flow Analysis
- Profitability Analysis
- Liquidity Analysis
- Leverage Analysis
- Efficiency Analysis
- Ratio Analysis
- ROE & ROCE Analysis

## Excel Skills Demonstrated

- Advanced Excel Formulas
- Cross-Sheet Referencing
- Financial Model Structuring
- Scenario & Sensitivity Modeling
- Data Tables
- Conditional Formatting
- Financial Data Visualization
- Dashboard Development
- KPI Design

## Investment Analysis Skills

- Intrinsic Valuation
- Relative Valuation
- Peer Benchmarking
- Market vs. Intrinsic Value Analysis
- Valuation Interpretation
- Investment Research

---
⚠️ Disclaimer

This project was created for educational and portfolio purposes only.

The valuation outputs are based on assumptions and estimates developed for this financial modeling exercise and should not be interpreted as investment advice or a recommendation to buy or sell securities.

Actual financial performance and market valuations may differ materially from the assumptions and projections used in this model.

---
👤 Author

Akshat Tiwari

B.Com (Hons) — University of Delhi

Areas of Interest
Investment Banking
Equity Research
Asset Management
Wealth Management
Financial Analysis

---
# 📂 Project Files

```text
Asian_Paints_Equity_Valuation.xlsx
