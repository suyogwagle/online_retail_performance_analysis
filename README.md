# Online Retail Performance Analysis

## Project Overview
Analysis of two years of transactional data (Dec 2009 – Dec 2011) 
from a UK-based online gift-ware retailer, structured to support 
partner advisory, offer curation, and merchant targeting decisions.

## Business Questions Answered
- Which products generate the most revenue and which are underperforming?
- Which products have high cancellation rates and why?
- Are there seasonal trends that should inform offer planning?
- Which international markets represent the biggest growth opportunity?
- Which product categories drive the most order volume?

## Dataset
- **Source:** Online Retail II — UCI ML Repository
- **Link:** https://archive.ics.uci.edu/dataset/502/online+retail+ii
- **Period:** December 2009 – December 2011
- **Records:** 1,067,371 raw → 820,829 after cleaning

## Tools Used
- Microsoft Excel 2016
  - Power Query (data loading, cleaning, transformation)
  - PivotTables with Data Model (aggregation and analysis)
  - Dashboard (KPI cards, charts)

## Key Findings
1. REGENCY CAKESTAND 3 TIER is the top revenue product at £286,486
2. Cherry Lights range has a systemic cancellation problem (27–51%)
3. November is the peak revenue month with both years exceeding £1.2M
4. EIRE and Netherlands are high-value but dangerously concentrated markets
5. Signs, Wall Decor & Garlands leads category demand with 18,393 orders

## Files
| File | Description |
|------|-------------|
| `online_retail_performance_analysis.xlsx` | Full Excel workbook with Power Query, PivotTables, charts and dashboard |
| `online_retail_performance_report.docx` | 5-page insights report with findings and recommendations |

## How to Use
1. Download the dataset from the UCI link above
2. Open the Excel workbook — Power Query will prompt you to refresh the data source path
3. Update the data source path in Power Query to point to your local file
4. Refresh all — all PivotTables and charts will update automatically
