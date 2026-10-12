# Indian Banking Performance & Financial Benchmarking 


### HDFC Bank | ICICI Bank | State Bank of India (SBI)

**A Financial Analysis & Excel Dashboard Project | FY 2025–26**

---

## 1. Project Overview

This project compares the financial performance of three major Indian banks — **HDFC Bank, ICICI Bank, and State Bank of India (SBI)** — using financial information extracted from their official FY 2025–26 annual reports.

The objective is to evaluate and compare their reported profitability, asset quality, operating efficiency, and business scale through eight key performance indicators (KPIs).

The project uses standalone financial figures to establish a consistent reporting basis and presents the results through a formula-driven Excel workbook containing comparative analysis, visual dashboards, analyst insights, and quality-control checks.

**Project classification:** Financial Statement Analysis | Banking Sector Benchmarking | Excel Dashboard | Financial Research

**Reporting period:** FY 2025–26, year ended 31 March 2026  
**Preparation date:** 12 October 2026  
**Analysis basis:** Standalone financial statements  
**Primary tool:** Microsoft Excel / LibreOffice Calc

> **Important:** This is a financial benchmarking exercise for academic and portfolio purposes. It is not a formal valuation, credit rating, or investment recommendation.

---

## 2. Project Objectives

The project aims to:

- Compare the reported profitability of HDFC Bank, ICICI Bank, and SBI.
- Evaluate asset quality using Gross NPA and Net NPA ratios.
- Assess operating efficiency using the cost-to-income ratio.
- Compare year-end advances and deposits to understand business scale.
- Examine differences between the banks using percentage-point calculations.
- Build an Excel dashboard with formula-driven findings and charts.
- Document data sources, calculation conventions, limitations, and verification status.
- Apply quality checks to improve the reliability and transparency of the analysis.

---

## 3. Banks Covered

### HDFC Bank

HDFC Bank is a major private-sector bank in India. The analysis examines its reported profitability, asset quality, operating efficiency, and lending and deposit balances.

### ICICI Bank

ICICI Bank is a major private-sector bank offering retail, corporate, and other banking services. It is assessed against the same eight KPI categories to identify differences in reported performance.

### State Bank of India (SBI)

SBI is a major public-sector bank in India with a large banking network and customer base. Its financial indicators provide a comparison of scale, profitability, asset quality, and operating efficiency against the two private-sector banks.

*The project uses the standalone figures reported by each bank rather than consolidated group figures.*

---

## 4. Key Performance Indicators

The workbook analyses eight KPIs across four major financial dimensions.

| Dimension | KPI | Unit |
|---|---|---|
| Profitability | Return on Assets (ROA) | % |
| Profitability | Return on Equity (ROE) | % |
| Profitability | Net Interest Margin (NIM) | % |
| Asset Quality | Gross Non-Performing Asset Ratio (GNPA) | % |
| Asset Quality | Net Non-Performing Asset Ratio (NNPA) | % |
| Operating Efficiency | Cost-to-Income Ratio | % |
| Business Scale | Year-end Advances | ₹ crore |
| Business Scale | Year-end Deposits | ₹ crore |

### KPI Definitions

- **ROA:** Reported net profit relative to average assets.
- **ROE:** Reported net profit relative to average equity.
- **NIM:** Net interest income relative to the relevant average interest-earning asset base, where specified.
- **GNPA:** Gross non-performing assets as a percentage of gross advances.
- **NNPA:** Net non-performing assets as a percentage of net advances.
- **Cost-to-Income Ratio:** Operating expenses relative to the income measure specified by the bank.
- **Advances:** Total year-end advances recorded on a standalone basis.
- **Deposits:** Total year-end deposits recorded on a standalone basis.

**Methodological note:** The banks' reported definitions and calculation conventions are preserved in the Sources sheet. ROA, ROE, NIM, and cost-to-income ratios may not be perfectly comparable because their underlying conventions differ.

---

## 5. Data Sources

The analysis uses text extracts of the following official annual reports:

1. **HDFC Bank Limited** — Integrated Annual Report 2025–26.
2. **ICICI Bank Limited** — Annual Report 2025–26.
3. **State Bank of India** — Annual Report FY 2025–26.

The source files inspected were:

- `HDFC_Bank_IR26__1_.pdf.txt`
- `icici-bank-annual-report-2025-26__1_.pdf.txt`
- `Annual_Report_FY2026.pdf.txt`

The workbook's Sources sheet records the extracted observations, available page references, KPI definitions, and verification status.

### Data Verification Status

The workbook contains 24 core KPI observations and six supplementary prior-year source records.

- **Verified against original PDF page images:** 0 of 24 core observations.
- **Partially verified using report text extracts:** 24 of 24 core observations.
- **PDF page-image inspection:** Not completed.

The figures were located and cross-checked within the available text extracts. However, the original PDF tables were not inspected visually. Therefore, the observations should not be described as fully verified against the original PDFs.

---

## 6. Key Findings

The following findings are based on the values currently recorded in the workbook.

### 6.1 Profitability

| KPI | HDFC Bank | ICICI Bank | SBI |
|---|---:|---:|---:|
| ROA | 1.94% | 2.32% | 1.12% |
| ROE | 14.29% | 15.97% | 18.57% |
| NIM | 3.50% | 4.32% | 2.91% |

**Observations:**

- ICICI Bank reports the highest ROA at 2.32%.
- SBI reports the highest ROE at 18.57%.
- ICICI Bank reports the highest stored NIM at 4.32%.
- SBI's reported ROE leadership does not coincide with ROA leadership.

NIM comparisons require caution because the denominator is not consistently specified across the banks.

### 6.2 Asset Quality

| KPI | HDFC Bank | ICICI Bank | SBI |
|---|---:|---:|---:|
| GNPA | 1.15% | 1.44% | 1.49% |
| NNPA | 0.38% | 0.35% | 0.39% |

**Observations:**

- HDFC Bank reports the lowest GNPA ratio at 1.15%.
- ICICI Bank reports the lowest NNPA ratio at 0.35%.
- SBI reports the highest GNPA ratio at 1.49%.

Lower NPA ratios generally indicate better reported asset quality. However, provisioning coverage, write-off policies, and differences in reporting conventions can also affect comparisons.

### 6.3 Operating Efficiency

| KPI | HDFC Bank | ICICI Bank | SBI |
|---|---:|---:|---:|
| Cost-to-Income Ratio | 38.00% | 39.75% | 50.11% |

**Observations:**

- HDFC Bank reports the lowest cost-to-income ratio.
- ICICI Bank is close to HDFC Bank on this measure.
- SBI reports the highest cost-to-income ratio among the three banks.

A lower ratio generally indicates that a bank uses a smaller proportion of its defined income measure to cover operating expenses. Because the banks use slightly different income definitions, the comparison is directional rather than exact.

### 6.4 Business Scale

| Metric (₹ crore) | HDFC Bank | ICICI Bank | SBI |
|---|---:|---:|---:|
| Year-end Advances | 2,937,166 | 1,553,893 | 4,877,895 |
| Year-end Deposits | 3,105,250 | 1,794,625 | 5,975,642 |

**Observations:**

- SBI reports the largest year-end advances and deposits.
- HDFC Bank reports larger advances and deposits than ICICI Bank in the recorded data.
- Business scale does not automatically translate into the highest reported ROA.

These figures represent year-end balances rather than average balances.

### Overall Interpretation

No single bank leads across all eight KPIs. ICICI Bank leads on reported ROA and stored NIM, HDFC Bank reports the lowest GNPA and cost-to-income ratios, and SBI reports the highest ROE and largest advances and deposits.

These observations describe reported financial performance for one year; they do not establish an overall winner or an investment preference.

---

## 7. Excel Workbook Structure

The workbook is organised into seven sheets.

| Sheet | Purpose |
|---|---|
| `README` | Project overview, methodology, sources, definitions, and limitations |
| `Raw_Data` | Input table containing the eight KPIs for each bank |
| `Sources` | Source register, page references, definitions, and verification status |
| `Analysis` | Formula-driven comparisons, high/low values, differences, and growth calculations |
| `Dashboard` | Summary cards, five native Excel charts, and formula-driven findings |
| `Insights` | Analyst report separating reported facts from interpretation |
| `QA_Checks` | 27 quality checks with PASS, WARNING, or FAIL status and corrective actions |

### Workbook Design Principles

- Raw inputs are separated from calculations and presentation.
- Formula-driven analysis is used where appropriate.
- Percentage ratios are stored as percentage-point numbers and displayed with percentage formatting.
- Ratio differences are expressed in percentage points (pp), not relative percentage changes.
- Missing values are intended to remain blank or display as N/A rather than being replaced with zero.
- Source definitions and comparability limitations are documented.

---

## 8. Methodology

The project follows a structured financial-analysis workflow.

1. **Source collection:** Identify the three banks' FY 2025–26 annual reports.
2. **Data extraction:** Locate the required KPI observations in the available report text extracts.
3. **Basis standardisation:** Use standalone figures and a common financial year.
4. **Unit conversion:** Convert reported balances into ₹ crore where necessary.
5. **Data organisation:** Enter the eight KPIs for each bank into the Raw_Data sheet.
6. **Comparative analysis:** Calculate high/low values, pairwise differences, and supported growth measures.
7. **Visualisation:** Present selected comparisons through dashboard cards and charts.
8. **Interpretation:** Separate reported facts from analyst commentary.
9. **Quality assurance:** Use checks to identify formula, data, and documentation issues.
10. **Documentation:** Record sources, assumptions, verification status, and limitations.

### Calculation Conventions

- Ratio differences are expressed in percentage points.
- Year-end advances and deposits are not treated as average balances.
- Reported definitions are retained instead of silently imposing a common formula.
- Missing or unavailable values should not be interpreted as zero.
- Growth is reported only where suitable prior-year observations are available.

---

## 9. Quality Assurance

The `QA_Checks` sheet contains 27 quality checks designed to support workbook integrity.

The checks are intended to cover areas such as:

- Completeness of required inputs.
- Validity of KPI values and units.
- Formula consistency.
- Correct use of percentage-point differences.
- Source-register completeness.
- Consistency between the dashboard, analysis, and raw data.
- Missing-value treatment.
- Documentation and verification warnings.

Each check uses a status such as **PASS**, **WARNING**, or **FAIL**, with corrective actions where applicable.

**Important:** The existence of a QA framework does not mean every check has passed. Refer to the actual `QA_Checks` sheet for the recorded outcomes. Formula recalculation and testing do not independently verify the accuracy of source figures.

---

## 10. Limitations

The results must be interpreted in light of the following limitations.

1. **Source verification:** Original annual-report PDF page images were not inspected. All 24 core observations remain partially verified rather than fully verified against the original PDFs.
2. **Single-year analysis:** The project covers FY 2025–26 and does not establish long-term performance trends.
3. **Definition differences:** ROA, ROE, NIM, and cost-to-income ratios may use different averaging conventions or denominators.
4. **NIM comparability:** HDFC Bank's stored NIM is 3.50% using average interest-earning assets, rather than its 3.34% headline measure using average total assets. SBI's denominator was not confirmed in the reviewed sections.
5. **Asset-quality comparability:** NPA ratios alone do not capture provisioning coverage, recoveries, or write-off policies.
6. **Growth analysis:** Growth could not be computed for all banks using the currently recorded data.
7. **Standalone basis:** The analysis excludes the broader consolidated group view, including subsidiaries.
8. **No valuation:** The workbook does not estimate intrinsic value, target prices, or risk-adjusted investment returns.
9. **No composite ranking:** The project does not assign an overall score or declare a universally superior bank.

### Recommended Improvements

- Inspect each original annual report's relevant PDF page images.
- Replace inferred page references with verified printed and PDF page numbers.
- Reconcile every observation with the original financial statement or KPI table.
- Add verified FY 2024–25 values for consistent year-on-year analysis.
- Include capital adequacy, liquidity, provisioning coverage, and additional risk indicators.
- Extend the analysis to multiple years and clearly document any normalisation choices.

---

## 11. Tools and Skills Demonstrated

**Tools**
- Microsoft Excel / LibreOffice Calc
- Formula-driven financial analysis
- Native Excel charts and dashboard design
- Official annual-report text extraction and source tracking
- Spreadsheet quality assurance

**Skills**
- Financial statement analysis
- Banking KPI interpretation
- Cross-company benchmarking
- Data cleaning and unit standardisation
- Formula development and validation
- Financial dashboard development
- Evidence-based reporting
- Documentation of assumptions and limitations

---

## 12. Conclusion

This project demonstrates a structured approach to comparing the reported financial performance of HDFC Bank, ICICI Bank, and SBI.

The analysis highlights differences in profitability, asset quality, operating efficiency, and business scale while recognising that a single financial ratio cannot fully explain a bank's overall performance.

The formula-driven workbook connects raw inputs, source documentation, comparative analysis, visualisation, and analyst interpretation in one place. Its most important next step is independent verification of all source observations against the original annual-report PDF tables.

The result is an academic financial-analysis project that demonstrates spreadsheet modelling, banking-sector understanding, data transparency, and analytical communication.

---

## 13. Disclaimer

This project is prepared for academic learning, financial-analysis practice, and portfolio demonstration. The figures are based on the source extracts documented in the workbook and have not been fully verified against original PDF page images.

The analysis is descriptive and should not be used as the sole basis for investment, lending, credit, or other financial decisions. Readers should consult the original annual reports and relevant disclosures before relying on any observation.

---

**Project:** Indian Banking Financial Performance Benchmarking & Strategic Assessment  
**Banks:** HDFC Bank | ICICI Bank | State Bank of India  
**Financial Year:** FY 2025–26  
**Prepared:** 12 October 2026
