Engagement & CRM Analytics
Nonprofit Donor Case Study
📊 Project Overview

This project analyzes a nonprofit CRM-style donor dataset (5,000 donors) to uncover behavioral patterns, revenue concentration, and retention risk using exploratory data analysis and RFM-based segmentation.

The objective is to simulate how a development team or foundation could use analytics to inform donor strategy and portfolio management.

🎯 Business Questions

How concentrated is revenue across the donor base?

Does gift frequency predict lifetime value?

What proportion of donors are at risk of lapse?

How should the donor file be segmented for strategic action?

🗂 Dataset Summary

The dataset includes:

5,000 donor records

Lifetime giving totals

Gift frequency (TotalGifts)

Last donation date

Engagement indicators

Geographic information

🔎 Analytical Methods

Data cleaning & validation (Pandas)

Feature engineering (RecencyDays, HighValueDonor flag)

Exploratory data analysis (Matplotlib)

Pareto revenue concentration modeling

RFM segmentation (Recency, Frequency, Monetary)

📈 Key Findings

The top 20% of donors contribute ~36% of total revenue (moderate concentration).

Gift frequency strongly correlates with lifetime giving.

Recency distribution indicates substantial lapse risk across the donor base.

RFM segmentation reveals actionable tiers for cultivation and retention strategy.

🧠 Strategic Recommendations

Prioritize high-RFM donors for major gift cultivation.

Develop recurring upgrade campaigns for mid-tier donors.

Launch reactivation campaigns targeting high-recency-risk segments.

Use segmentation for data-informed portfolio assignment and campaign targeting.

🛠 Tools & Skills Demonstrated

Python (Pandas, NumPy, Matplotlib)

CRM data modeling

Feature engineering

Behavioral segmentation (RFM)

Revenue concentration analysis

Strategic insight framing

📁 Repository Structure
notebooks/
    01_data_intake.ipynb
README.md
