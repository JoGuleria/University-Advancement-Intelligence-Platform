# University-Advancement-Intelligence-Platform
An end-to-end fundraising analytics project exploring donor behavior, giving propensity, and donor segmentation using a synthetic university advancement dataset containing 500,000 constituents and $31B+ in philanthropic giving.

## Business Problem

Advancement teams collect large amounts of donor, engagement, event, and stewardship data. However, determining which donors are most likely to give again and where fundraising resources should be allocated remains a challenge.

This project explores:

- What predicts future giving?
- Which donor segments exist?
- How can advancement teams prioritize stewardship efforts?

## Dataset

Dataset includes:

- 500,000 donors
- $31.1B lifetime giving
- Giving history
- Contact reports
- Event attendance
- Relationship networks
- Giving propensity scores

Tables used:

- Donors
- Giving
- Contacts
- Events
- Relationships

  ## Methodology

### 1. Exploratory Data Analysis

- Giving distribution
- Donor concentration analysis
- Donor type analysis
- Correlation analysis

### 2. Regression Analysis

Predictors tested:

- Giving history
- Contact activity
- Event attendance
- Relationship metrics

Target:

- Will_Give_Again_Probability

### 3. Decision Tree

Used to identify the most important predictors of future giving propensity.

### 4. K-Means Clustering

Used to identify donor personas for fundraising strategy.

## Key Findings

### Giving is Highly Concentrated

- Median lifetime giving: $441
- Average lifetime giving: $62,196
- Top 1% of donors account for 61% of donations given

  ## Donor Personas

| Persona | Description |
|----------|------------|
| Loyal Annual Donors | ... |
| Contacted but Unconverted | ... |
| Event-Engaged Mid-Major Donors | ... |
| Transformational Donors | ... |
| Low Engagement Constituents | ... |

## Dashboard 
<img width="692" height="389" alt="image" src="https://github.com/user-attachments/assets/f0b09c72-5977-406d-a166-c5331dfd78e8" />

<img width="389" height="139" alt="image" src="https://github.com/user-attachments/assets/ef4b1db3-79c5-4b52-ae08-e9dce8bf254a" />


## Recommendations
Prioritize retention of Loyal Annual Donors
Develop cultivation strategies for Contacted but Unconverted donors
Create event-to-gift conversion pathways
Provide personalized stewardship for Transformational Donors

## Tools Used
- Python
- Pandas
- Statsmodels
- Scikit-Learn
- Power BI

## Future Work

- Random Forest
- XGBoost
- Prospect Scoring
- Major Gift Identification
