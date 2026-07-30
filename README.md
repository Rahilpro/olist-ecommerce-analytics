# Olist Brazilian E-Commerce Analytics

End-to-end data analytics project on the Olist marketplace dataset 
(100,000 orders · 9 tables · 2016–2018)

## Business Question
"What is driving delivery delays and low review scores — 
and which sellers should be flagged for intervention?"

## Tech Stack
- **SQL** — 14 queries, multi-table JOINs, CTEs, window functions
- **Python** — pandas, matplotlib, seaborn, scipy (statistical tests)
- **Power BI** — 5-page interactive dashboard with DAX measures

## Key Findings
- Late deliveries cause **6.6x more bad reviews** (avg 2.27 vs 4.29)
- **97% of customers never return** — repeat buyers spend 78% more
- **42 sellers** flagged for intervention out of 3,095 active sellers
- AL state has **23.9% late rate** vs SP at only 5.9% — 4x difference
- November 2017 Black Friday spike: **R$987K** revenue in one month

## Statistical Validation
- All findings confirmed via chi-square tests and t-tests (p < 0.05)
- Delivery delay vs review: t = 51.97, p < 0.0001

## Dashboard
🔗 **[Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGRjZTNhYWYtYWUyYi00ZTQ3LTlhMmUtMWNjYWE5MTczODcyIiwidCI6Ijk2NDY0YThhLWY4ZWQtNDBiMS05OWUyLTVmNmI1MGEyMDI1MCIsImMiOjN9)**

## Dashboard Pages
| Page | Content |
|------|---------|
| Executive Overview | KPI cards, revenue trend, delivery speed impact |
| Delivery Analysis | Late rate by state, delay analysis |
| Seller Scorecard | Tier distribution, intervention list |
| Customer Analytics | RFM segments, purchase frequency |
| Key Insights | 4 findings with recommendations |

## Project Structure
