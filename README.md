# Loan Business Profitability Analysis

An Excel-based business analysis project that evaluates a loan portfolio
from a profitability, pricing, tenure, product, and regional
perspective.

The main purpose of this project is not just to calculate loan metrics,
but to identify **where the business is losing money and what management
can do about it**.

------------------------------------------------------------------------

## 1. Project Overview

This project analyzes a portfolio of **500 loans** across four products:

-   Car
-   Bike
-   Laptop
-   Mobile Phone

The analysis uses Excel PivotTables, PivotCharts, KPIs, slicers, and a
dashboard/reporting structure to convert raw loan data into business
decisions.

The portfolio is currently **loss-making**, with a net bank loss of
approximately **₹36.05 lakh** and a profit margin of approximately
**−2.83%**.

The analysis shows that the largest issue is concentrated in **Car
loans**, particularly when lower interest rates and longer tenures are
involved.

------------------------------------------------------------------------

## 2. Business Objective

The project aims to answer the following business questions:

1.  Which loan product is contributing most to the loss?
2.  Are the current interest-rate segments generating enough return?
3.  Which product and interest-rate combinations are creating losses?
4.  Is loan tenure affecting profitability?
5.  Which regions have the largest profitability losses?
6.  Where should management focus corrective action first?

The final goal is to support decisions around **pricing, loan approval,
tenure, portfolio mix, exposure control, and regional review**.

------------------------------------------------------------------------

## 3. Dataset

The dataset contains 500 loan records and includes information related
to:

-   Loan ID
-   Product / Device Category
-   Loan Amount / Principal
-   Interest Rate
-   Interest Rate Segment
-   Tenure
-   Tenure Segment
-   Loan Status
-   Region
-   Processing Fee
-   Revenue / Total Interest Income
-   Cost of Funds
-   Default Loss
-   Net Bank Profit
-   Loan Size Segment

The additional segmentation fields make it possible to perform more
useful business analysis instead of relying only on raw numerical
values.

------------------------------------------------------------------------

## 4. Key KPIs

The project uses the following portfolio-level KPIs:

  KPI                             Value
  ---------------------- --------------
  Total Loans                       500
  Total Loan Principal        ₹12.74 Cr
  Total Revenue                ₹3.32 Cr
  Cost of Funds                ₹3.52 Cr
  Default Loss              ₹15.86 Lakh
  Total Cost                   ₹3.68 Cr
  Net Bank Profit          −₹36.05 Lakh
  Profit Margin                  −2.83%

### KPI Interpretation

The most important result is the **negative Net Bank Profit**.

Revenue is approximately ₹3.32 crore, while total cost is approximately
₹3.68 crore. Therefore, the business is operating at a loss.

This means that simply increasing loan volume is not a good strategy
under the current loan economics.

------------------------------------------------------------------------

## 5. Business Analysis Visuals

The report/dashboard uses five main decision-focused visuals.

### 1. Net Bank Profit by Product

**Purpose:** Identify which product is responsible for the largest
profitability problem.

The analysis shows that:

-   Car: approximately **−₹37.41 lakh**
-   Laptop: approximately **+₹1.64 lakh**
-   Bike: approximately **+₹0.46 lakh**
-   Mobile Phone: approximately **−₹0.74 lakh**

### Business Decision

Car loans should be reviewed separately before expanding the segment.

Management should investigate the **interest rate, tenure, and loan-size
mix** inside Car loans rather than applying the same policy to every
product.

------------------------------------------------------------------------

### 2. Net Bank Profit by Interest Rate Segment

**Purpose:** Evaluate whether the current pricing structure is
generating enough return.

The analysis shows:

-   High Rate: approximately **+₹2.50 lakh**
-   Medium Rate: approximately **−₹11.85 lakh**
-   Low Rate: approximately **−₹26.69 lakh**

### Business Decision

Low-rate lending requires immediate review.

The bank should establish a practical pricing floor based on funding
cost and expected loss instead of simply increasing rates for every
customer.

------------------------------------------------------------------------

### 3. Product × Interest Rate

**Purpose:** Find the specific product-pricing combinations responsible
for the loss.

The strongest negative combination is:

-   **Car + Low Rate: approximately −₹26.69 lakh**
-   **Car + Medium Rate: approximately −₹10.72 lakh**

### Business Decision

The pricing problem is concentrated in Car loans.

Management should consider:

-   Repricing low-rate Car loans
-   Applying stricter approval rules
-   Reviewing expected return before approval
-   Avoiding a blanket rate increase across profitable products

------------------------------------------------------------------------

### 4. Product × Tenure

**Purpose:** Understand whether loan duration is affecting
profitability.

The analysis shows that:

-   **Car + Long Term: approximately −₹33.82 lakh**
-   Car + Medium Term: approximately −₹3.59 lakh
-   Car + Short Term: approximately −₹2.97 lakh

### Business Decision

Long-term Car loans require particular attention.

Management could consider:

-   Reducing the maximum tenure
-   Applying additional pricing to longer-tenure loans
-   Reviewing long-term loans during credit approval
-   Checking whether the additional interest compensates for the funding
    cost

------------------------------------------------------------------------

### 5. Regional Profitability / Loss

**Purpose:** Identify which region contributes most to the overall
profitability problem.

The regional results are:

-   East: approximately **−₹11.71 lakh**
-   South: approximately **−₹10.79 lakh**
-   West: approximately **−₹8.35 lakh**
-   North: approximately **−₹5.18 lakh**

### Business Decision

All regions are loss-making, so the issue is not isolated to one
geography.

East has the largest loss and should receive the closest review.
However, management should first investigate the **product, rate, and
tenure mix within each region** rather than simply reducing lending in
one region.

> **Important:** The regional visual in the project is a **Net Bank
> Profit/Loss by Region** chart. It should not be described as Default
> Loss by Region unless the PivotChart is changed to use Default Loss.

------------------------------------------------------------------------

## 6. Main Business Findings

The five visuals together tell a consistent story:

### Finding 1 --- Car loans are the main problem

Car loans generate approximately **₹37.41 lakh of loss**, which is large
enough to eliminate the profit generated by the other products.

### Finding 2 --- Low-rate loans are performing poorly

The Low Rate segment contributes approximately **₹26.69 lakh of loss**.

### Finding 3 --- The pricing problem is concentrated in Car loans

Car + Low Rate and Car + Medium Rate are responsible for most of the
product-rate losses.

### Finding 4 --- Long-term Car loans are particularly damaging

Car + Long Term contributes approximately **₹33.82 lakh of loss**.

### Finding 5 --- The problem exists across all regions

Every region is loss-making. Therefore, the business should focus on
improving the economics of the loan portfolio rather than treating the
issue as a single-region problem.

------------------------------------------------------------------------

## 7. Recommended Business Actions

The recommended priority is:

### Priority 1 --- Fix Car-loan economics

Review Car loans independently for:

-   Interest rate
-   Tenure
-   Loan size
-   Expected return
-   Funding cost
-   Default risk

### Priority 2 --- Review low-rate pricing

Set a minimum acceptable return after considering funding cost and
expected loss.

### Priority 3 --- Control long-term Car loans

Consider shorter maximum tenures or additional pricing for longer-term
loans.

### Priority 4 --- Control large exposures

Very large loans should receive stronger approval and exposure controls
because they can create concentrated losses.

### Priority 5 --- Protect profitable products

Laptop and Bike are currently profitable. Their economics should be
protected while considering controlled growth.

### Priority 6 --- Review regional performance

East has the largest regional loss, but the product/rate/tenure mix
should be investigated before making a geographic lending decision.

------------------------------------------------------------------------

## 8. Excel Features Used

The project demonstrates the use of:

-   Excel Tables
-   Formulas
-   Calculated fields
-   PivotTables
-   PivotCharts
-   Slicers
-   KPI calculations
-   Conditional formatting
-   Dashboard design
-   Business-oriented reporting

### Interactive Slicers

The workbook uses slicers for:

-   Product / Device Category
-   Region
-   Loan Status
-   Interest Rate Segment
-   Tenure Segment

These slicers allow the user to filter the analysis and examine how
profitability changes for different parts of the portfolio.

------------------------------------------------------------------------

## 9. Workbook Structure

A recommended structure for the final workbook is:

``` text
Loan_Business_Analysis/
│
├── Raw_Data
│   └── Original loan records
│
├── Data_Dictionary
│   └── Field definitions and descriptions
│
├── Business_Health
│   └── KPIs and portfolio-level analysis
│
├── Product_Analysis
│   └── Product, pricing and tenure PivotTables
│
├── Business_Decisions
│   └── Decision-focused analysis
│
├── Dashboard
│   └── Final interactive dashboard
│
└── Report
    └── Business-oriented project documentation
```

------------------------------------------------------------------------

## 10. Dashboard Design

The dashboard should provide a quick management-level view.

### Recommended layout

**Top section** - Total Loans - Loan Principal - Total Revenue - Cost of
Funds - Default Loss - Net Bank Profit - Profit Margin

**Main analysis section** - Net Bank Profit by Product - Net Bank Profit
by Interest Rate - Product × Interest Rate - Product × Tenure - Regional
Profitability

**Filter section** - Product - Region - Loan Status - Interest Rate
Segment - Tenure Segment

The dashboard should prioritize readability and decision-making rather
than displaying every available metric.

------------------------------------------------------------------------

## 11. Project Outcome

The project converts raw loan-level data into a business-focused
analysis.

Instead of only showing that the portfolio is loss-making, the analysis
identifies the areas that require attention:

``` text
Overall Loss
     ↓
Product Analysis
     ↓
Car identified as major loss driver
     ↓
Interest Rate Analysis
     ↓
Low-rate lending identified as major issue
     ↓
Product × Rate Analysis
     ↓
Car + Low/Medium Rate identified
     ↓
Tenure Analysis
     ↓
Car + Long Term identified
     ↓
Regional Analysis
     ↓
East identified as largest regional loss
```

This provides a logical path from **data → insight → business
decision**.

------------------------------------------------------------------------

## 12. Final Conclusion

The loan portfolio is currently loss-making, but the analysis provides a
clear direction for improvement.

The most important issue is the **Car loan segment**, particularly the
combination of lower pricing and longer tenure. The regional analysis
also shows that losses exist across all regions, so the solution should
focus on improving loan economics rather than simply reducing lending in
one location.

The key lesson from this project is that **loan volume should not be
treated as the main measure of success**. A loan is valuable only when
the return generated from it is sufficient to cover funding cost and
expected losses.

The first business priority should therefore be to **fix the economics
of Car loans**, review low-rate pricing, control long-term exposure, and
protect products that are already profitable.

------------------------------------------------------------------------

## 13. Author

**Student:** Tufan Bera , Spriha Sahu , Sumit Singh

**Project:** Loan Business Profitability Analysis

**Tools:** Microsoft Excel, PivotTables, PivotCharts, Slicers,
Dashboard, Microsoft Word

<img width="1505" height="771" alt="WhatsApp Image 2026-09-02 at 13 23 28" src="https://github.com/user-attachments/assets/2431097c-fa40-4d95-8a10-c6da1bf961f7" />
