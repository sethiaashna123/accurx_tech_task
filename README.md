# User Retention Analysis — Accurx Take-Home

This repository contains the BigQuery SQL used to analyse whether performing key activities in the first week predicts long-term retention.

## Report

See the full analysis and insights as Accurx Analysis PDF. 

## SQL Files

1. **Accurx Activity Base**
   View name: accurx_activity_base
   View created aggregate weekly activity to one row per user per week. This view does the following:
   - Flatten activity to one row per user per week and organisation
   - Reformat fields for readability
   - Deal with outliers 


2. **Accurx Activity Summary**
   View name: accurx_activity_base
   View created to understand overall user activation and retention. This view does the following:
   - Flatten activity to one row per user
   - Filters signup week activity to calculate activation metrics
   - Calculates retention metrics per user


3. **Retention Rate Adhoc Query**  
   Calculates retention rates by activation status.

