# Power BI Notes - DAX Measures

Total Spend = SUM(Ads_Fact[Spend])
Total Impressions = SUM(Ads_Fact[Impressions])
Total Clicks = SUM(Ads_Fact[Clicks])
Total Link Clicks = SUM(Ads_Fact[Link_Clicks])
Total Conversions = SUM(Ads_Fact[Conversions])
Total Revenue = SUM(Ads_Fact[Conversion_Value])

CTR = DIVIDE([Total Clicks], [Total Impressions])
Link CTR = DIVIDE([Total Link Clicks], [Total Impressions])
CPC = DIVIDE([Total Spend], [Total Clicks])
CPM = DIVIDE([Total Spend], [Total Impressions]) * 1000
CPA = DIVIDE([Total Spend], [Total Conversions])
Conversion Rate = DIVIDE([Total Conversions], [Total Link Clicks])
ROAS = DIVIDE([Total Revenue], [Total Spend])
ROI_pct = DIVIDE([Total Revenue] - [Total Spend], [Total Spend])

Engagement Rate = DIVIDE(SUM(Ads_Fact[Engagements]), SUM(Ads_Fact[Reach]))
