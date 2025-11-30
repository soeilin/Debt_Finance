# Portfolio KPI Monitoring (MoM / Risk Trends)
This project builds a lightweight retial-credit risk monitoring pack. It showcases:
• How key credit portfolio KPIs move month-on-month
• How early signals propagate into later risk outcomes

## Objective
To simulate a monthly portfolio monitoring process used in credit decisioning and risk analytics teams for early detection of deterioration, identifying emerging risk themes, and supporting credit strategy decisions.

The project replicates the workflow used in automated lending portfolios:

• Calculate core credit KPIs
• Analyse MoM movements
• Visualise risk signals
• Produce business-focused insights

## Metrics Tracked
• Bad rate (30+ DPD)  
• Early-arrears formation  
• Approval/decline rates  
• Utilisation rate  
• Vintage performance (lite version)  

## Methods
• Synthetic monthly data (Python) : The model uses 12 months of synthetic data, designed to resemble a typical credit card / personal loan portfolio. Values are generated to produce realistic patterns in approval behaviour, early arrears formation, and late arrears flow-through.
• KPI calculations (Python / Excel Dual-Version)  
• Month-on-month movement tracking
• Early-warning identification
• Variance commentary with risk interpretation  

## Outputs - Visuals
• Early Arrears vs Bad Rate：Two-series overlay plot showing propagation of risk
• Approval Rate vs Bad Rate：Used to assess credit tightening/loosening impact
• MoM risk movement

## Outputs - Summary
• Early warning signals  
• Business-focused insights  

## Skills Demonstrated
Portfolio thinking, KPI variance analysis, Early-warning identification，Credit risk fundamentals (DPD1, DPD30, approval behaviour)，Visual storytelling with risk data，Python-based data workflow，Excel-based business-ready calculations
