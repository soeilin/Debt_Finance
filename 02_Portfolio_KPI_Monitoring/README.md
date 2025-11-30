# Portfolio KPI Monitoring (MoM / Risk Trends)
This project builds a lightweight retial-credit risk monitoring pack. It showcases:
• How key credit portfolio KPIs move month-on-month
• How early signals propagate into later risk outcomes

## Objective
To simulate a monthly portfolio monitoring process used in credit decisioning and risk analytics teams for early detection of deterioration, identifying emerging risk themes, and supporting credit strategy decisions.

The project replicates the workflow used in automated lending portfolios:

• Calculate core credit KPIs <br>
• Analyse MoM movements and flag material changes <br>
• Visualise risk signals <br>
• Identify early-warning signals and potential risk shifts  <br>
• Summarise business-focused insights for decisioning <br>

## Metrics Tracked
• Bad rate (30+ DPD)  
• Early-arrears formation  
• Approval/decline rates  
• Utilisation rate  
• Vintage performance (lite version)  

## Data Dictionary (Key Fields)
| Variable | Definition | Interpretation |
|---------|------------|----------------|
| DPD1 | Accounts 1+ day past due | Early-warning signal; leads DPD30 by 1–2 cycles |
| DPD30 | Accounts 30+ days past due | Core bad-rate indicator; strong risk outcome metric |
| Approval Rate | Approvals ÷ Applications | Tightening/loosening signal; impacts future risk mix |
| Utilisation | Balances ÷ Limits | Behavioural stress indicator; rises during liquidity pressure |
| Vintage Bad | New 30+ from recent cohorts | New-book quality check; detects underwriting risk |

## Methods
• Synthetic monthly data (Python) : The model uses 12 months of synthetic data, designed to resemble a typical credit card / personal loan portfolio. Values are generated to produce realistic patterns in approval behaviour, early arrears formation, and late arrears flow-through. <br>
• KPI calculations (Python / Excel Dual-Version)  <br>
• Month-on-month movement tracking <br>
• Early-warning identification <br>
• Variance commentary with risk interpretation   <br>

## Outputs - Visuals
• Early Arrears vs Bad Rate：Two-series overlay plot showing propagation of risk <br>
• Approval Rate vs Bad Rate：Used to assess credit tightening/loosening impact <br>
• MoM risk movement

## Outputs - Executive Insights (Summary)
• Early arrears (DPD1) rose consistently during Feb–Mar, feeding into higher DPD30 in Apr–May.  
• Approval tightening in Jul–Aug contributed to a stabilisation in bad rate in Sep.  
• Vintage bad rate deterioration in Dec signals potential new-book quality issues.  
• Utilisation trending up in Q4, hinting at behavioural liquidity stress.


## Skills Demonstrated
Portfolio thinking, KPI variance analysis, Early-warning identification，Credit risk fundamentals (DPD1, DPD30, approval behaviour)，Visual storytelling with risk data，Python-based data workflow，Excel-based business-ready calculations
