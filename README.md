# Used Car Sales Pricing Efficiency Analysis

## Overview
This project analyzes used-car transaction data to evaluate  and to identify the key drivers of mispricing across vehicle lifecycle, mileage, seller behavior,  and time.

The analysis is anchored on pricing efficiency as a core benchmark, with supporting analyses explaining *why*, *where*, *who*, and *when* pricing deviates from market expectations.

## Business Questions
- Are vehicles priced efficiently relative to market benchmarks?
- What factors drive systematic overpricing or underpricing?
- How do vehicle age, mileage, and condition affect value retention?
- Do seller behavior and regional dynamics influence pricing discipline?
- Does timing or seasonality impact pricing power?

## Dataset
The dataset contains transaction-level vehicle sales data, including:
- Vehicle attributes (make, model, year, trim, body, transmission)
- Pricing information (MMR, selling price)
- Usage indicators (odometer, condition)
- Seller identifiers
- Geographic and time-based fields

## Methodology
1. Light EDA to validate data integrity
2. Pricing efficiency benchmarking against MMR
3. Feature engineering
3. Feature engineering to capture vehicle age, pricing deviations, and temporal patterns
4. Analysis of pricing efficiency drivers:
   - Vehicle lifecycle and depreciation
   - Mileage and condition impact
   - Seller performance and pricing discipline
   - Time-based and seasonal behavior
5. Interaction analysis to identify compounded mispricing risks
6. Synthesis of insights and business recommendations

## Key Metrics
- Price Delta (Selling Price − MMR)
- Price premium pct(price eff %)
- Vehicle Age at Sale
- Mileage Bands
- Condition Bands
- Seller-Level Pricing Variability

## Tools & Technologies
- Python (Pandas, NumPy)
- Data visualization with Matplotlib
- SQL-style preprocessing logic
- Jupyter Notebook

## Key Insights
- Pricing in this datset is generally efficient but exhibits systematic deviations in specific segments
- Early vehicle lifecycle stages experience the steepest depreciation
- High mileage amplifies underpricing beyond what MMR predicts
- High-volume sellers demonstrate tighter pricing discipline
- "Niche" sales are where the greatest opportunities for high premiums and the greatest risks of underpricing exist.
- Pricing inefficiencies are most severe when multiple risk factors coincide

## How to Use This Repository
- Start with the Executive Summary in the notebook
- Follow the analysis sequentially; each section builds on the previous one
- Markdown cells explain analytical intent and business interpretation
- Visualizations highlight patterns; tables support detailed inspection

## Author
Solomon Wisdom  
Data Analyst | Financial Analysis | Pricing & Market Analytics
