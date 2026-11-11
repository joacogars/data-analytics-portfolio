### Top 10 Descriptions by Recorded Sales Value

A PivotTable was used to rank product descriptions by the sum of `LineValue`, calculated as `Quantity × UnitPrice`. A horizontal bar chart was created to compare the ten highest recorded values.

DOTCOM POSTAGE ranked first, with a recorded line value of £206,245.48, followed by REGENCY CAKESTAND 3 TIER at £164,762.19. WHITE HANGING HEART T-LIGHT HOLDER ranked third at £99,668.47.

**Interpretation and limitation:** The ranking includes postage-related descriptions, so it should not be interpreted as a ranking of merchandise alone. The figures represent recorded line values, not profit. Further analysis should separate postage from merchandise and investigate cancellation and negative-quantity records before drawing broader conclusions.

## Monthly Recorded Sales Value (2010–2011)

A PivotTable was created using `InvoiceDate` grouped by year and month, with the sum of `LineValue` used to calculate monthly recorded transaction values.

### Key finding

November 2011 had the highest monthly recorded value, at **£1,461,756.25**.

December 2011 recorded **£433,668.01**. However, this is an incomplete month because the dataset ends on 9 December 2011.

### Interpretation and limitations

The monthly analysis suggests that November 2011 was the strongest month by recorded transaction value in this dataset.

These figures are calculated as `Quantity × UnitPrice`. They should not be interpreted as profit or definitive net revenue because the initial analysis includes cancellation invoices, negative quantities and postage-related transactions.

The December 2011 figure should not be directly compared with complete months without acknowledging its partial coverage.

### Tools

- Microsoft Excel: PivotTables and line chart
- GitHub: Project documentation

### Dataset source

Chen, D. (2015). *Online Retail*. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33

## Country Analysis: Recorded Sales Value

A PivotTable was used to compare recorded sales values across countries.

### Key findings

- United Kingdom: £8,187,806.364 — ranked first.
- Netherlands: £284,661.54 — ranked second.
- EIRE, Germany and France followed in the ranking.
- The UK accounted for approximately 84% of the overall recorded transaction value.

### Business interpretation

The recorded transaction values are strongly concentrated in the United Kingdom market. The Netherlands ranked second, but its recorded value was substantially lower than the UK's.

### Limitation

These figures include cancellation invoices and negative-quantity records. They represent recorded transaction values, not verified net revenue or profit.

## Customer Analysis: Top 10 Customers by Recorded Sales Value

A PivotTable was used to rank identifiable customers by the sum of `LineValue`.

### Key findings

- Customer 14646 ranked first, with a recorded value of £279,489.02.
- A horizontal bar chart was created to compare the ten highest-ranked customers.
<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/2901774c-db05-4cba-b1f8-e0540076d94c" />

### Business interpretation

Customer 14646 contributed the highest recorded transaction value among identifiable customers. This provides a starting point for investigating customer concentration and purchasing behaviour.

### Limitations

The analysis excludes records with missing CustomerIDs. Recorded values include cancellation invoices and negative quantities, so they should not be interpreted as verified customer spending or profit.
