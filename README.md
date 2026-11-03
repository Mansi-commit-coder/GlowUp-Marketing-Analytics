# GlowUp – Marketing Campaign Performance Analysis 📊

## 📌 Project Overview

GlowUp is a beauty and skincare startup that runs multiple online and offline marketing campaigns through Email, 
Social Media, Influencer Collaborations, and Events.
The objective of this project is to analyze marketing campaign performance, evaluate Return on Investment (ROI), 
identify the most effective marketing channels, and recommend strategies for optimizing future marketing budgets.
This project uses **Power BI** to transform campaign data into meaningful business insights and interactive visualizations.

## 🎯 Business Objectives

- Identify campaigns generating the highest ROI.
- Analyze channel performance based on revenue and conversions.
- Evaluate Cost Per Acquisition (CPA) across marketing channels.
- Identify campaigns with high lead generation but low conversion rates.
- Recommend an effective marketing budget allocation strategy.
- Improve marketing efficiency through data-driven decisions.

## 📂 Dataset Overview

The dataset contains marketing campaign information, including:

- Campaign ID and Campaign Name
- Marketing Channel
- Campaign Start Date and End Date
- Campaign Spend
- Leads Generated
- Conversions
- Revenue Generated
- Clicks
- Impressions

**Dataset Summary:**
- Total Campaigns: 30
- Marketing Channels: 4
- Campaign Start Date Coverage: Approximately 10 months

## 📈 Key Performance Indicators (KPIs)

| KPI | Formula |
|---|---|
| Total Spend | SUM(Spend) |
| Total Revenue | SUM(RevenueGenerated) |
| Total Leads | SUM(LeadsGenerated) |
| Total Conversions | SUM(Conversions) |
| ROI (%) | (Revenue - Spend) / Spend × 100 |
| CPA | Spend / Conversions |
| CPL | Spend / Leads |
| Conversion Rate | Conversions / Leads × 100 |

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Interactive dashboard development and visualization.
- **DAX** – KPI calculations and measures.
- **Power Query** – Data cleaning and transformation.
- **Microsoft Excel / CSV** – Dataset preparation and validation.
- **Python (Pandas & Matplotlib)** – Supporting data analysis and visualizations.

## 📊 Dashboard Features

The Power BI dashboard includes:

- KPI cards displaying Total Spend, Total Revenue, CPA, ROI, Total Conversions, CPL, and Total Leads.
- Channel-wise marketing performance comparison.
- Campaign-wise ROI analysis.
- Campaign conversion analysis.
- Revenue and Spend comparison by channel.
- Interactive slicers for Campaign Name, Start Date, and Channel.
- Identification of high-performing and low-performing campaigns.

## 🔍 Key Business Insights

Based on the analysis of 30 marketing campaigns:

1. **Overall Performance:** Campaigns generated ₹511,853.73 in revenue against ₹445,664.29 in marketing spend,
 resulting in an overall ROI of 14.85%.

3. **Email Marketing:** Email campaigns delivered the highest aggregate ROI and the lowest CPA, making this channel a
  strong candidate for future investment.

5. **Event Marketing:** Events generated the highest revenue and conversion volume but also accounted for the
   largest share of marketing expenditure.

7. **Influencer Marketing:** Influencer campaigns delivered positive aggregate returns, although performance
   varied across individual campaigns.

9. **Social Media Marketing:** Social Media recorded negative aggregate ROI, indicating a need to improve audience
    targeting, advertising creatives, and campaign optimization.

## 💡 Business Recommendations

### Short-Term Strategies
- Increase investment in high-performing Email campaigns.
- Prioritize Influencer campaigns with proven conversion performance.
- Optimize Social Media advertisements before increasing spending.
- Monitor Event campaign costs and lead-to-customer conversion.

### Long-Term Strategies
- Implement audience segmentation and personalized marketing.
- Conduct A/B testing for advertisements and promotional offers.
- Improve campaign tracking using UTM parameters.
- Monitor customer acquisition costs and campaign profitability.
- Review marketing performance regularly to optimize budget allocation.

### Recommended Next-Quarter Budget Allocation

| Marketing Channel | Budget Allocation |
|---|---:|
| Email | 35% |
| Influencer | 30% |
| Events | 25% |
| Social Media | 10% |
| **Total** | **100%** |


## 📁 Project Deliverables

- Interactive Power BI dashboard.
- Marketing campaign performance analysis.
- KPI calculations and business insights.
- Campaign ROI and CPA comparison.
- Business recommendations.
- Detailed project report.

## ⚠️ Assumptions & Limitations

- Analysis is based on the supplied campaign dataset.
- Revenue is treated as campaign-attributed revenue.
- ROI is calculated using campaign spend and generated revenue.
- Product costs and other operating expenses are not included.
- Missing Event channel engagement metrics are treated as unavailable rather than zero.
- The analysis identifies associations and performance patterns but does not establish campaign causality.

## 🏁 Conclusion

This project demonstrates how data analytics and Power BI can help businesses evaluate marketing performance and make 
informed budget allocation decisions.

The analysis highlights Email as the strongest channel in terms of ROI and acquisition efficiency, Events as a major 
contributor to revenue and conversions, Influencer Marketing as an opportunity for selective expansion, and Social Media as 
an area requiring optimization.

The overall goal is to help GlowUp improve marketing efficiency, reduce acquisition costs, and maximize future campaign returns.

---

**Project:** GlowUp – Marketing Campaign Performance Analysis  
**Domain:** Marketing Analytics / Business Intelligence  
**Tool:** Microsoft Power BI  
**Author:** Mansi Sinha
