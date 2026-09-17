# ₹10,00,000 Diversified Equity Portfolio & DCF Valuation 📈

> **Capstone Project:** Fundamental Analysis Bootcamp  
> **Organised by:** Finance & Economics Club, IIT Guwahati  
> **Author:** Piyush Mahesh Sonawane  

---

## 📌 Executive Summary

This repository hosts the investment thesis, screening framework, asset allocation, and discounted cash flow (DCF) valuation model for a **₹10,00,000 fundamental equity portfolio** deployed across six key sectors of the Indian economy.

### Key Metrics
* **Total Capital Deployed:** ₹10,00,000
* **Asset Allocation:** 7 fundamentally-screened stocks across 6 sectors
* **Portfolio-Weighted Avg. ROE:** ~19%
* **Risk Stratification:** 
  * **Core Defensives (46%):** Power Grid, Sun Pharma, Nestle India
  * **Structural Growth (24%):** Bharat Electronics Ltd., Apollo Hospitals
  * **Cyclical Alpha (25%):** Motilal Oswal Financial Services, HG Infra Engineering

---

## 🏗️ Portfolio Allocation & Screening Data

The portfolio applies a strict multi-metric screening framework:
* **Profitability:** 3–5 year avg. ROE & ROCE > 15%
* **Balance Sheet Health:** Low/zero leverage, high interest coverage
* **Governance & Moat:** High promoter backing / Navratna status, pricing power, multi-year order visibility
* **Cash Conversion:** Operating Cash Flow vs. Reported Net Profit

| Stock | Ticker | Sector | CMP (₹) | Weight | Allocation (₹) | Key Metric | Call |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Power Grid Corp.** | `POWERGRID` | Energy | ₹291 | 20% | ₹2,00,000 | 4.75% Div. Yield, Regulated ROE | **BUY** |
| **Sun Pharma** | `SUNPHARMA` | Healthcare | ₹1,850 | 20% | ₹2,00,000 | 25.1% ROCE, Net cash positive | **BUY** |
| **Bharat Electronics** | `BEL` | Defence | ₹420 | 15% | ₹1,50,000 | ₹74k Cr Order Book, 27.8% ROE | **BUY** |
| **Motilal Oswal** | `MOTILALOFS` | Finance | ₹800 | 15% | ₹1,50,000 | +26% AMC AUM YoY, ARR ~60% | **BUY** |
| **Nestle India** | `NESTLEIND` | FMCG | ₹1,460 | 10% | ₹1,00,000 | 92.3% 3-yr ROE, Zero debt | **HOLD** |
| **Apollo Hospitals** | `APOLLOHOSP` | Healthcare | ₹7,100 | 10% | ₹1,00,000 | 18.4% ROE, +35.9% PAT YoY | **ACCUMULATE** |
| **HG Infra Eng.** | `HGINFRA` | Infrastructure | ₹590 | 10% | ₹1,00,000 | P/E ~9.5x, ₹10,147 Cr Order Book | **ACCUMULATE** |

---

## 🧮 Standalone Valuation Model: Bharat Electronics Ltd. (BEL)

A 5-year **Free Cash Flow to Firm (FCFF)** Discounted Cash Flow model was constructed to evaluate valuation disconnects against market price.

### Valuation Assumptions
* **Base Free Cash Flow ($FCF_0$):** ₹1,195 Cr (OCF: ₹2,017 Cr – Capex: ₹822 Cr)
* **Projected FCF CAGR (Years 1–5):** 20.0% p.a.
* **Weighted Average Cost of Capital (WACC):** 10.0%
* **Terminal Growth Rate ($g$):** 4.0%
* **Shares Outstanding:** ~731 Cr
* **Net Cash on Balance Sheet:** ₹8,058 Cr

### Projections & Valuation Outputs

$$\text{Terminal Value} = \frac{FCF_5 \times (1 + g)}{WACC - g} = \frac{2,974 \times 1.04}{0.10 - 0.04} = \text{₹}51,550\text{ Cr}$$

* **Sum of PV of 5-Yr Cash Flows:** ₹7,818 Cr
* **Present Value of Terminal Value:** ₹32,013 Cr
* **Implied Enterprise Value (EV):** ₹39,831 Cr
* **Implied Equity Value (EV + Net Cash):** ₹47,889 Cr
* **Intrinsic DCF Value per Share:** **₹65.5**
* **Current Market Price (CMP):** **₹420.0**

> **Analysis & Sizing Verdict:**  
> Pure cash-flow DCF marks BEL as overvalued due to heavy debtor days (~170 days) restricting operating cash conversion. However, because the broader market prices in long-term defence indigenisation tailwinds and a ₹74k Cr backlog, the stock was retained but **capped at a 15% weight** to insulate the book from valuation correction.

---

## 📂 Repository Contents
* `Capstone_Presentation.pdf`: Complete 17-slide pitch deck presented to the club.
* `README.md`: Sector breakdown, valuation tables, and thesis summary.

---

## ⚠️ Disclaimer
*This repository and its contents were prepared solely for academic/bootcamp evaluation under the Finance & Economics Club, IIT Guwahati. It does not constitute financial or investment advice.*
