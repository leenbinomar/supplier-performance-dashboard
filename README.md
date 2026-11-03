# Supplier Performance Dashboard

An interactive Power BI dashboard comparing five suppliers on delivery speed, quality, compliance and cost savings, using the Procurement KPI Analysis Dataset (Kaggle).

## Dashboard
![Dashboard](procurement_dashboard.pngg.png)

## Questions answered
1. Which suppliers deliver fastest?
2. Which suppliers have the best quality (lowest defect rate)?
3. Which suppliers comply with terms most consistently?
4. How much was saved through price negotiation, and with whom?
5. Where does spend go by category?

## Key findings
- Average lead time is similar across suppliers (10.2 to 11.3 days)
- Quality and compliance vary notably: Delta_Logistics has a 14.43% defect rate and 60.82% compliance, while Alpha_Inc (2.25%, 93.62%) and Epsilon_Group (2.97%, 98.19%) perform best
- Beta_Supplies delivered the highest negotiated savings ($889,941) but has a 9.35% defect rate
- Spend is spread across categories, with MRO ($10.1M) and Office Supplies ($10.0M) the highest

## Recommendation
Prioritize Alpha_Inc and Epsilon_Group, and review the performance of Delta_Logistics and Beta_Supplies.

## Tools
Power BI, Power Query, DAX

## Data
Procurement KPI Analysis Dataset (Kaggle). Defect rate is calculated on orders with defect data; savings = (Unit price - Negotiated price) x Quantity.
