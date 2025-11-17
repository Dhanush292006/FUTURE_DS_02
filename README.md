# FUTURE_DS_02
Analyzed Facebook/Instagram ad data to evaluate performance, engagement, CTR, CPC, CPM, CPA, ROAS and ROI. Cleaned data in Excel, built KPIs, and created visual dashboards in Power BI/Looker. Identified top campaigns, audiences and creatives, and provided optimization insights for better results.
# Social Media Campaign Performance Tracker

**350-char description:**  
Analyzed Facebook/Instagram ad data to evaluate performance, engagement, CTR, CPC, CPM, CPA, ROAS and ROI. Cleaned data in Excel, built KPIs, and created visual dashboards in Power BI/Looker. Identified top campaigns, audiences and creatives, and provided optimization insights for better results.

## Repository Contents
- `sample_ads_data.csv` — mock dataset (daily-level) with fields: Date, Platform, Account, Campaign, AdSet, Ad, Impressions, Reach, Clicks, Link_Clicks, Spend, Engagements, Video_Views, Conversions, Conversion_Value, Landing_Page, Country, Device, plus computed CTR/CPC/CPM/CPA/ROAS.
- `README.md` — this file with usage instructions.
- `power_bi_notes.md` — (below) DAX measures and recommended visuals.

## How to use
1. Clone this repo.
2. Open `sample_ads_data.csv` in Excel/Sheets for inspection.
3. Load CSV into Power BI or Looker Studio.
   - Power BI: Use the provided DAX measures (see power_bi_notes.md) and build visuals: KPI cards, time series (Spend vs Conversions), campaign ROAS bar, funnel, creative grid, geo map.
   - Looker Studio: Connect CSV/Google Sheet, create calculated fields: CTR, CPC, CPM, CPA, ROAS.
4. Update with your real Meta Ads export (replace CSV) and refresh visuals.

## Next steps
- Replace mock CSV with your Meta Ads export (daily granularity).
- Tune benchmarks and targets per vertical.
- Create a one-page Canva report from dashboard screenshots.

## License
MIT

