# Understanding Customer Survey Participation Through Response History Segmentation

## Project Overview

Customer satisfaction surveys are widely used to measure service quality and customer experience. However, survey participation is often uneven across customer groups, creating challenges for data quality and representativeness.

This project examines whether prior survey participation history can predict future survey response behavior. Using two consecutive survey cycles, customers were segmented according to their prior response history and compared based on subsequent participation rates.

The goal was to identify customer groups that may benefit from targeted outreach strategies and to provide practical recommendations for improving survey participation.

---

## Business Question

Can prior survey participation history predict future customer survey response behavior?

Specifically:

* Are previous responders more likely to respond again?
* Are historically silent customers less likely to participate?
* Are there differences between in-state and out-of-state customers?

---

## Customer Segmentation

Customers were classified into three groups:

### Prior Responders

Customers who were surveyed in the previous two years and responded at least once.

### Silent Customers

Customers who were surveyed in the previous two years but never responded.

### New Customers

Customers who had not been surveyed in the previous two years.

---

## Key Findings

### Finding 1: Prior response history strongly predicts future participation

| Segment          | FY25 Response Rate | FY26 Response Rate |
| ---------------- | ------------------ | ------------------ |
| Prior Responders | 69%                | 71%                |
| New Customers    | 39%                | 38%                |
| Silent Customers | 28%                | 20%                |

Customers who responded previously were substantially more likely to respond again.

---

### Finding 2: Silent customers consistently exhibit the lowest participation rates

Across both survey cycles, silent customers demonstrated the lowest response rates, suggesting that prior nonresponse is a strong indicator of future nonresponse.

---

### Finding 3: Geographic differences may exist

Overall response rates were higher among out-of-state customers than in-state customers.

| Year | In-State | Out-of-State |
| ---- | -------- | ------------ |
| FY25 | 45%      | 60%          |
| FY26 | 43%      | 62%          |

However, subgroup sample sizes were limited and additional validation would be required before implementing location-specific interventions.

---

## Business Implications

The findings suggest that survey participation can be improved through targeted engagement strategies.

Potential interventions include:

* Customized reminder messaging
* Alternative sender-domain testing
* Segment-specific outreach strategies
* Enhanced engagement plans for historically silent customers

---

## Tools Used

* Python
* Pandas
* NumPy
* JupyterLab
* Matplotlib

---

## Data Confidentiality Notice

The original project was conducted using proprietary customer satisfaction survey data.

To protect confidentiality and comply with organizational data governance requirements, all publicly shared data in this repository have been aggregated and de-identified. No customer-level information is included.
