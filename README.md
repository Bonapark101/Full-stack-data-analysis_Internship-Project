# Full stack data analysis_Internship Project
Spot coffee sales performance analysis

# Executive summary
The company is growing its client base and increasing the number of spot lots available. Using Python and Tableau, I analysed sales and lot attribute data to build a dashboard insepcting sales and market trends across 2023-2025.

The analysis identified that Attesa Coffee's revenue peaks in June and November align with major global harvest windows, reflecting healthy participation in the green spot market. However, despite significant revenue growth, profitability remains constrained by a concentration in low-price, low-margin transactions. Along with price and margin sales volumn analysis, sales velocity data reveals that commercial-grade lots from Brazil, India, and Vietnam with Nutty/Cocoa and Nutty/Cocoa and Fruity flavour profiles represent the core demand base, clearing inventory most efficiently within the current portfolio.

I connected the finding to the market trend and consumer behaviour to recommended the company to:
1) Prioritise sourcing spot lots with Nutty/Cocoa and Nutty/Cocoa Fruity flavours, as these demonstrate the highest sales velocity and most consistent demand within the current portfolio
   
2) Increase the concentration of these flavour profiles and mid-SCA score/commercial grade lots during the April-May and September-October sourcing windows to maximise inventory turnover.

# Business Problem
The quality of green coffee beans degrade over time. When spot coffee lots sell slowly or at discounts, overall business performance and profitability drop. How can we reduce holding cost and maximize profit for spot coffees?

# Methodology
1. Data cleaning, standardizing, and transforming in Python
2. A dashboard in Tableau that shows the trends in sales and lot attributes

# Skills
Python: pdf plumber, pandas, pathlib, numpy, re
Tableau: establish relationships, writing functions, data visualization 

# Result & Recommendation
This analysis showed that spot coffee revenue peaks in June/July, with 173% client growth from 2023 to 2025. Lot attributes reveal Brazil/Natural/Blend dominate velocity for aggressive scaling, Colombia/Anaerobic honey/Castillo variants lead margins (180-221%, for profit focus), while Vietnam and Guatemala underperform. Brazial/Natural/Blend and Colombia/Anaerobic honey/Castillo variants are highly aligned with Nutth/Cocoa flavour profiles. Additionally, Nutty/Cocoa flavour + SCA 83 - 85 maximize commercial velocity. 

<img width="441" height="378" alt="Screenshot 2026-02-10 at 15 59 19" src="https://github.com/user-attachments/assets/802e6713-af6e-44a5-8266-1c9ce4725577" />


<img width="441" height="378" alt="Screenshot 2026-02-10 at 16 56 52" src="https://github.com/user-attachments/assets/30d9b7f4-a3b0-4e9b-b3b1-220922f321f3" />


Recommendation: Rebalancing sourcing based on the finding to reduce holding costs and boost profitability.

*Because the company operates pre-order coffee and spot coffee, further anlaysis is required on overall lot sales performance across both channels to confirm strategy applicability

# Next Steps
1. Research and analyze about regional market and clients
2. Analyze pre-order coffee sales performance

# NOTE
Due to confidentiality, sales data from ZOHO book is not included in this repository.

Summary of data processing:
1. Created two reports in ZohoBook (FIFO Cost Lot Tracking, Invoice Details).
2. Exported the reports as CSV files and selected relevant columns from each.
3. Merged the two CSV files into a single dataset for anlaysis.
