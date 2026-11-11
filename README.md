# data-analytics-portfolio
Data Analytics and Storytelling Projects &amp; Assistant Bot
PORTFOLIO

About Me

I have completed a data analytics and storytelling course and an Excel course. I am now practicing my skills through hands-on projects using real-world datasets.
My Learning Goals

- Practice data analysis using Excel and SQL.
- Learn to communicate findings through clear data storytelling.
- Develop practical skills in data cleaning, analysis, and visualization.
- Build a portfolio of projects that demonstrates my progress.
**Projects**

Project 1: Online Retail Sales Analysis
[Read the detailed findings](findings.md)
**Status:** Planning
**Objective:** Explore historical retail transactions to understand sales trends, product performance, and customer purchasing behavior.
**Tools:** Excel and SQL, with additional tools to be considered as I progress.
My Approach
I will focus on understanding the business question, checking data quality, analyzing the evidence, and explaining what the results mean.
This portfolio will grow as I complete projects and develop my skills.

## Project 1: Online Retail Sales Analysis

**Project Status**
**Project Status:** Initial Excel analysis completed. Findings documented; portfolio presentation and final review in progress.


**Business Question**
What can historical sales transactions tell us about sales trends, popular products, and customer purchasing behavior?

 **Dataset**
UCI Online Retail Dataset  
Source: https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains historical transactions from a UK-based online retailer selling gifts and other products.

 **Research Questions**
1. How do recorded sales change over time?
2. Which products have the highest recorded sales?
3. Which countries contribute the most recorded sales?
4. What can the data tell us about customer purchasing behavior?

 **Tools**
- Microsoft Excel for data exploration, calculations, PivotTables, and charts.
- GitHub for project documentation and version history.

**Planned Method**
1. Understand the dataset and its columns.
2. Inspect data quality and document cleaning decisions.
3. Calculate and validate sales metrics.
4. Create charts that answer the research questions.
5. Summarize the findings and suggest evidence-based next steps.

**Limitations**
The dataset covers a historical period. Recorded revenue does not necessarily equal profit, and missing customer identifiers may limit customer-level analysis.

### Key Findings

- **Monthly analysis:** November 2011 had the highest recorded monthly transaction value.
- **Product analysis:** DOTCOM POSTAGE ranked first by recorded line value, followed by REGENCY CAKESTAND 3 TIER.
- **Country analysis:** The United Kingdom ranked first, followed by the Netherlands.

These are preliminary recorded transaction values, not verified profit or definitive net revenue. The analysis includes cancellation invoices and negative quantities. December 2011 is also incomplete.

**Dataset Attribution**
Chen, D. (2015). Online Retail. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.
**Planned outcome:** A documented analysis with charts, key findings, and evidence-based recommendations.

## Day 2: Initial Data Exploration

### Dataset Structure
- Dataset name: UCI Online Retail
- File: Online Retail.xlsx
- Source: UCI Machine Learning Repository
- Expected columns: 8
- Expected records: 541,909

### Initial Observations
Dataset contains 541,909 records and 8 columns.
Inspected sample rows 100, 500 and 1,000.
Date and decimal-comma formats were observed in Excel.
Date and decimal-comma formats were observed in Excel.
Missing CustomerIDs and missing product descriptions were identified.
No original transaction records were deleted or modified during initial exploration.

### Changes Made
No data-cleaning changes made during initial exploration.


### Day 2: Initial Data Exploration

- Successfully opened the UCI Online Retail workbook in Excel.
- Identified the eight dataset columns.
- Checked the Quantity, UnitPrice, and InvoiceDate fields.
- Regional number format: decimal comma (observed in UnitPrice).
- Data cleaning: not yet started.
- Next step: inspect a small sample for missing values and unusual transactions.

  ### Step 3: Sample Inspection

Rows inspected: 100, 500, 1000

- Cancellation invoice observed: Yes
- Negative quantities observed: Yes
- Zero prices observed: Not Yet Checked
- Blank customer IDs observed: Yes, identified in the wider data-quality check.

No records have been deleted or modified.

### Questions for further analysis
- How frequent are cancellations?
- How many transactions have missing customer identifiers?
- How should returns and zero-price transactions be treated when calculating sales?

  ### Initial Sample Review

Three sample rows were inspected: 100, 500, and 1000.

- All three reported invoice numbers were numeric and did not begin with C.
- All three reported quantities were positive.
- All three reported unit prices were positive.
- All three reported customer IDs were populated.
- Sample line values were calculated as Quantity × UnitPrice.

These three rows are illustrative examples only. They are not sufficient to establish the overall data quality of the dataset.

No original records have been modified.
