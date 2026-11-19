# Ecommerce Project

# Global E-Commerce Sales Analysis

An Excel-based analysis of 2,000 global e-commerce orders (January 2023 – December 2025) to uncover sales and profitability trends and recommend ways to improve performance.

**Headline finding:** The business earns a healthy 32.8% profit margin, but 13.6% of orders (272) are sold at a loss, and 82% of those loss-making orders come from a single category, Office Supplies.

![Dashboard / chart preview](images/preview.png)

## Business Problem

The business looks profitable on the surface, but sales are flat over three years and a noticeable share of orders lose money. This project asks:

- How have sales and profit changed over time?
- Which regions, product categories, customer segments and payment methods perform best?
- Which categories and conditions are driving loss-making orders?
- What should the business do to improve profitability?

## Dataset

- **Source:** Kaggle, [dataset name and link here]
- **Size:** 2,000 order records, 15 fields (including Order ID, Date, Region, Country, Category, Segment, Payment Method, Quantity, Sales, Profit, Discount and Shipping Cost)
- **Coverage:** 5 regions, 20 countries, 4 product categories, 3 customer segments, 4 payment methods
- **Data quality:** No missing values, no duplicate rows and all dates valid, so no cleaning was required

## Tools

- Microsoft Excel (data checks, calculated fields, pivot tables and charts)
- Microsoft PowerPoint (presentation of findings)

## Approach

1. Checked the data for missing values, duplicates and invalid dates.
2. Created calculated fields such as profit margin and a loss-order flag.
3. Summarised sales and profit by month, region, category, segment and payment method.
4. Isolated loss-making orders and traced them to category.
5. Turned the results into charts and written recommendations.

## Key Findings

| Metric | Result |
| --- | --- |
| Total sales | $484,559 |
| Total profit | $158,872 |
| Profit margin | 32.8% |
| Average order value | $242.28 |
| Orders sold at a loss | 272 (13.6%) |

- **Time trend:** Sales are cyclical with no sustained growth or decline. Monthly sales ranged from $7,337 (Feb 2025) to $18,068 (Jun 2025).
- **Regions:** Europe ($137,006) and North America ($133,876) lead. The top three regions make up about 81% of sales.
- **Categories:** Furniture earns the most revenue ($256,275, 53% of sales). Clothing & Accessories has the highest margin (37.6%). Office Supplies has the lowest (17.1%).
- **Segments:** Consumers drive 53% of sales ($256,288).
- **Payments:** Credit card is the most used method (40% of sales), followed by PayPal.
- **Losses:** 224 of the 272 loss-making orders (82%) are Office Supplies.

## Recommendations

1. **Fix Office Supplies pricing:** review the discount policy for this category.
2. **Invest in Furniture and Technology:** they bring the most revenue with healthy margins.
3. **Address the early-year dip:** consider promotions or bundling in January and February.
4. **Explore smaller regions:** assess whether Middle East & Africa and South America are limited by market size or by under-investment.

## Limitations and Next Steps

- Total losses ($953) are small compared with total profit, so the loss problem is mainly about pricing discipline rather than a large profit leak.
- Next, I plan to analyse loss rate by discount level and compare profit margin by region, segment and payment method.

## Repository Structure

```
├── data/            # Dataset (check the Kaggle licence before uploading)
├── analysis/        # Excel workbook with pivot tables and charts
├── presentation/    # Slide deck (PDF and PPTX)
├── images/          # Chart and dashboard screenshots
└── README.md
```

## Author

**Ibraheem Tunde Lawal**
Microbiology graduate and aspiring data analyst, Kwara State University
[LinkedIn](https://www.linkedin.com/in/lawalibraheem-aa8981321)

*Completed as the final project of a three-month data analysis training with Learn with Wida.*
