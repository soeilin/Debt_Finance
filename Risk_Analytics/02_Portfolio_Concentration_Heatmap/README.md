## Portfolio Concentration Heatmap
A lightweight portfolio-risk tool to identify exposure concentrations and detect emerging deterioration clusters.

# Objective

To demonstrate the ability to assess portfolio composition and highlight risk concentrations using simple, interpretable heatmaps.
This project replicates a common workflow used in Risk Analytics and Portfolio Insights teams for detecting:

• shifts in exposure distribution  
• pockets of elevated bad-rate performance  
• cross-segment deterioration patterns  
• early signals that may require strategy or policy review  
• The focus is on interpretation and portfolio logic, not advanced modelling  

# Dataset

A synthetic retail-credit dataset with the following fields:

• segment (Core / HighRisk / Value)   
• product_type (Cards / Loans — configurable)   
• region (North / Central / South — illustrative)   
• exposure (account balance or limit proxy)   
• dpd30_flag (1 = 30+ delinquent, 0 = current)  


# Methods

**1. Exposure Distribution Heatmap**

Aggregates total exposure by segment × region (or any two categorical axes).
Used to identify:
• where the portfolio is concentrated   
• whether concentration is increasing over time   
• whether riskier segments hold disproportionate weight   

**2. Bad-Rate Heatmap**

Calculates bad-rate (DPD30+) by segment × region.
Designed to highlight:
• deterioration clusters   
• geographies with emerging stress   
• segment pockets where performance diverges from the portfolio average  

**3. Joint Interpretation**

Combining exposure and bad-rate heatmaps helps answer:
• Are high-risk clusters small but deteriorating?   
• Are large exposure buckets stable or worsening?    
• Do regional or segmental trends signal early warning?   
• Which areas require deeper drill-down, AB testing, or policy review?    

# Key Visuals
Heatmaps are generated using pandas + matplotlib / seaborn, ensuring full reproducibility.

• Exposure Heatmap (absolute balances / % of portfolio)   
• Bad-Rate Heatmap (% DPD30+)   
• Overlay Table summarising risk ranking and notable pockets   

# Skills Demonstrated

**Portfolio Risk & Analytics**

• Concentration-risk assessment   
• Deterioration scanning across matrix dimensions   
• Bad-rate computation and interpretation   
• Early-warning identification  

**Technical**

• pandas for aggregation and matrix construction   
• matplotlib / seaborn for heatmap generation   
• Reproducible Python workflow for analytics reporting   

**Business Communication**

• Insight-driven commentary   
• Highlighting risk pockets and exposure implications   
• Translating visual diagnostics into portfolio-actions context  












