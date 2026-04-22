# AI-Powered Marketing Campaign Intelligence System

## Overview

This project simulates a marketing campaign and demonstrates how data can be transformed into actionable business insights using AI.

Instead of focusing on complex modeling, the goal is to showcase the **last mile of analytics**, converting performance metrics into clear, decision-oriented insights.

## Objective

* Analyze campaign performance using key metrics
* Understand customer engagement behavior
* Generate business insights using an AI layer
* Provide actionable recommendations for optimization


## System Workflow

```
Simulated Campaign Data
        ↓
Metric Extraction (Funnel + Behavior + Financials)
        ↓
AI Insight Generation (LLM)
        ↓
Fallback System (if AI unavailable)
        ↓
Final Business Insight
```


## Project Structure

```
marketing-campaign-analysis/
│
├── data/
│   └── campaign_data.csv
|
├── notebooks/
│   └── data_simulation.ipynb
|
├── src/
│   ├── data_simulation.py
│   ├── metrics_extraction.py
│   ├── ai_insights.py
│   ├── fallback.py
│   └── run_pipeline.py
│
├── outputs/
│   └── sample_insight.txt
│
└── README.md
```


## Key Metrics Extracted

The system focuses on three core areas:

### 1. Campaign Performance

* Open Rate
* Click-Through Rate (CTR)
* Conversion Rate

### 2. Customer Behavior

* Average Engagement Score
* High vs Low Engagement Segments

### 3. Financial Performance

* Total Revenue
* Revenue Per User
* Campaign Cost
* ROI


## 🤖 AI-Powered Insights Layer

To bridge the gap between data and decision-making, the project integrates a lightweight AI layer.

Instead of passing raw data, the system feeds curated business metrics into an LLM to generate:

* Key observations
* Business interpretation
* Strategic recommendations

A **multi-model fallback mechanism** is implemented to ensure reliability. If all models fail, a deterministic fallback generates structured insights.


## Sample Insight

> **Key Observations**
>
> * Conversion rate is relatively low compared to engagement levels
> * A significant portion of users show low engagement behavior
> * Campaign generates positive ROI but with limited efficiency

> **Business Interpretation**
>
> * The campaign is reaching users but not converting them effectively
> * Targeting or messaging may not align with user intent

> **Recommended Actions**
>
> * Refine audience targeting using engagement signals
> * Optimize campaign creatives and messaging
> * Focus on high-engagement users to improve conversion rates


## Key Takeaway

Traditional analytics pipelines stop at reporting metrics.

This project goes a step further by answering:

> **"What should the business do next?"**

By combining structured analytics with AI-generated interpretation, it demonstrates a simple yet powerful **decision-support system**.


## Tech Stack

* Python (NumPy, Pandas)
* Requests (API integration)
* OpenRouter (LLM access)


## ⚠️ Note

Free LLM endpoints may occasionally fail or be rate-limited.
The system is designed to handle this gracefully using a fallback mechanism.


## 🤝 Connect

If you found this interesting or have feedback, feel free to follow and connect!

**My Portfolio & Profiles: 
- [Portfolio](https://nibeditans.github.io/)
- [LinkedIn](https://www.linkedin.com/in/ns-nibedita-sahu/)
- [Medium](https://nsdsda.medium.com/)
- [Kaggle](https://www.kaggle.com/nibeditasahu)
- [Hackerrank](https://www.hackerrank.com/profile/nibeditans)!**

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
