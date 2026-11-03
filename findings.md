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

The United Kingdom generated the highest recorded sales value, approximately £8.19 million, representing around 84% of the overall recorded transaction value. The Netherlands ranked second, followed by EIRE, Germany and France. This indicates a strong concentration of recorded sales in the UK market.
