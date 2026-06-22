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
- Top 1% of donors account for 61
