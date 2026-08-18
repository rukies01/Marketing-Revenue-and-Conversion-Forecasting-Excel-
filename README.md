# Marketing Revenue & Conversion Forecasting

## Project Overview

This project analyses 24 months of historical marketing performance data from January 2023 to December 2024 to forecast revenue, conversions and advertising performance.

The analysis combines trend-based and seasonality-aware forecasting methods to support marketing planning, budgeting and performance management.

The goal was not only to produce forecasts, but to translate the results into practical recommendations that could support non-technical business stakeholders.

---

## Business Problem

Marketing teams need reliable short- and medium-term forecasts to:

- Set realistic revenue and conversion targets
- Plan marketing budgets effectively
- Understand the relationship between advertising spend and revenue
- Prepare for seasonal demand fluctuations
- Make more informed planning decisions

Historical performance data was available, but forecasting was not standardized, making it more difficult to translate historical trends into actionable planning insights.

---

## Objectives

The project aimed to:

1. Analyse historical marketing performance and identify key trends.
2. Forecast future revenue, conversions and advertising spend.
3. Compare different forecasting approaches.
4. Identify seasonal patterns in marketing performance.
5. Evaluate the relationship between advertising spend and revenue.
6. Translate the findings into practical business recommendations.

---

## Dataset

The dataset contains monthly marketing performance data covering:

**January 2023 – December 2024**

Key variables include:

| Variable | Description |
|---|---|
| Website Sessions | Monthly website traffic |
| Ad Spend (€) | Monthly advertising expenditure |
| Leads | Number of leads generated |
| Conversions | Number of converted leads |
| Revenue (€) | Monthly marketing-generated revenue |

The dataset reflects realistic growth trends and seasonal patterns typical of digital marketing environments.

---

## Methodology

### 1. Data Preparation

The data was validated for completeness and consistency before analysis.

Key preparation steps included:

- Validating data completeness
- Converting month values into date format
- Creating a time index to support trend-based forecasting
- Preparing the data for forecasting and visualization

---

### 2. Linear Trend Forecasting

Excel's `FORECAST.LINEAR` function was used to estimate future:

- Revenue
- Conversions
- Advertising spend

This approach was used to capture longer-term growth trends.

---

### 3. Moving Average Forecasting

A 3-month moving average was used to smooth short-term fluctuations.

This provided an additional perspective for near-term planning and helped reduce the effect of individual monthly variations.

---

### 4. Seasonality-Aware Forecasting

Excel's Forecast Sheet using the ETS (Exponential Triple Smoothing) method was used to incorporate recurring seasonal patterns.

This was particularly useful for revenue forecasting where seasonal peaks were visible in the historical data.

---

## Key Findings

### Revenue Trends

Revenue demonstrated an overall upward trend across the analysis period, with noticeable seasonal peaks during Q4.

The analysis also showed that linear trend forecasts can underestimate peak seasonal periods compared with seasonality-aware ETS forecasting.

---

### Conversion & Funnel Performance

Conversion growth broadly followed website session growth.

Conversion rates remained relatively stable across the historical period, supporting the use of traffic assumptions when forecasting future conversions.

---

### Advertising Spend vs Revenue

Revenue increased as advertising spend increased, but the relationship was not proportional.

The analysis showed indications of diminishing returns at higher levels of advertising spend.

This suggests that improving marketing efficiency may provide greater value than simply increasing the overall advertising budget.

---

## Business Recommendations

### 1. Align Budgets With Seasonal Demand

Increase marketing investment ahead of historically strong periods, particularly Q4, while optimizing spend during lower-performing periods.

### 2. Prioritize Efficiency Over Spend Growth

Revenue does not increase linearly with advertising spend.

Marketing teams should focus on improving conversion performance, targeting, creative effectiveness and landing-page performance rather than relying solely on larger budgets.

### 3. Use Multiple Forecasting Methods

Different forecasting approaches provide different planning benefits:

- Linear trend forecasting for longer-term planning
- Moving averages for short-term planning
- ETS forecasting for seasonality-aware planning

Using multiple methods provides a more informed basis for decision-making.

### 4. Reforecast Regularly

Forecasts should be updated as new performance data becomes available.

Changes in campaign mix, pricing, market conditions or other business assumptions should trigger a review of the forecast.

### 5. Integrate Forecasts Into Stakeholder Reporting

Forecasts should be incorporated into management dashboards and reporting processes so that marketing and leadership teams can compare expected performance with actual results.

---

## Assumptions & Limitations

The forecasting analysis assumes that:

- Historical trends and seasonal patterns continue into the forecast period.
- There are no major changes in marketing channel mix or market conditions.
- Forecast assumptions remain reasonably stable.

Forecasts should therefore be reviewed and updated regularly as new data becomes available.

---

## Tools & Techniques

- Microsoft Excel
- `FORECAST.LINEAR`
- Moving Average Forecasting
- ETS / Excel Forecast Sheet
- Data Visualization
- Line Charts
- Combo Charts
- Marketing KPI Analysis
- Forecasting & Trend Analysis
- Business Analysis

---
## Project Preview

### Excel Marketing Dashboard

![Excel Marketing Dashboard](exceldashboard.png)

### Forecasting Analysis

![Forecasting Analysis](forecastinganalysis.png)

## Project Outputs

The project includes:

- Historical marketing performance analysis
- Revenue forecasting
- Conversion forecasting
- Advertising spend forecasting
- Moving-average analysis
- Seasonality-aware ETS forecasting
- Marketing performance dashboard
- Business recommendations

---

## Related Power BI Analysis

This Excel forecasting project forms the analytical foundation for a related Power BI analysis.

The Power BI version extends the analysis into:

- Interactive KPI monitoring
- Marketing funnel analysis
- ROI analysis
- Cost-per-lead analysis
- Revenue-per-lead analysis
- Budget scenario analysis

While both projects use the same underlying marketing dataset, they have different analytical purposes:

**Excel:** Forecasting, trends, seasonality and planning

**Power BI:** Interactive BI reporting, KPI monitoring and budget scenario analysis

[View the Power BI Case Study](https://rukies01.github.io/case-study.html)

---

## Key Takeaway

Forecasting creates the most value when it supports concrete business decisions.

By combining trend-based forecasting, moving averages and seasonality-aware forecasting with business interpretation, this project demonstrates how historical marketing data can be transformed into practical insights for planning, budgeting and performance management.
