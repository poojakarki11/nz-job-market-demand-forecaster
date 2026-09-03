# NZ Job Market Demand Forecaster
Forecasting short-term labour demand trends in New Zealand using MBIE Jobs Online and official Stats NZ labour market data.

## Overview
This project investigates short-term labour demand trends in New Zealand using Jobs Online data and official labour market data from Stats NZ. It examines how online labour demand has changed over time, how patterns differ across regions, industries, occupations, and skill groups, and whether recent vacancy data can support short-term forecasting over the next 3–6 months.

The analytical workflow has three main stages:
1. **Data acquisition, cleaning, and integration** — raw datasets are cleaned, standardised, and merged into analysis-ready tables across monthly, quarterly, regional, industry, occupation, and skill dimensions.
2. **Exploratory data analysis** — examining overall labour demand trends and subgroup differences, alongside official labour market context (unemployment, underutilisation).
3. **Forecasting** — short-term forecasting models applied at the national level, extended to selected industries and regions.

## Data Sources
- **MBIE Jobs Online** — monthly/quarterly online job advertisement data broken down by region, industry, occupation, and skill group. Used as the main signal for trend analysis and forecasting.
- **Stats NZ** — employment indicators, unemployment, and underutilisation rates, used to provide broader labour market context and validate forecast results.

## Key Findings
- Data covers May 2007 – Apr 2026 (228 months); vacancy index peaked at 220.1 in Jul 2021, sitting at 95.1 by Apr 2026.
- **Industries:** Health showed the smallest 5-year decline (-17.8%), while IT saw the largest (-50.4%).
- **Skill level:** Unskilled demand index (110.0) currently exceeds Highly Skilled (84.8) by 25.2 points.
- **Labour market:** Latest unemployment rate 5.3%, underutilisation rate 12.9%.
- **Seasonality:** Demand peaks in March (avg index 120.9) and troughs in December (avg index 78.3).

## Results
Online labour demand in NZ has shifted noticeably over time, showing both downturns during periods of disruption and stronger recovery phases. Patterns are not uniform — regional, industry, and occupation-level trends vary in both level and direction, suggesting labour demand is shaped by local economic structure. Short-term forecasting models (3–6 month horizon) show that recent vacancy data contains enough structure to produce useful national-level projections, with more variability at the industry/regional subgroup level.

## Limitations
- Jobs Online reflects online job ad activity, not total labour demand in the economy.
- Stats NZ data has mixed reporting frequencies, requiring alignment before integration.
- Forecasts are short-term (3–6 months) only, not long-range predictions.
- Industry/regional subgroup forecasts are based on narrower series and more sensitive to short-term fluctuation.
