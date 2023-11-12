# Digantra-Assignment
**Overview:**

Conjunctions in space occur when two or more Resident Space Objects (RSOs) in Earth's orbit approach each other dangerously, potentially leading to collision scenarios. This assignment focuses on analyzing and visualizing predicted conjunctions of active satellites in space. The dataset provided contains information about RSOs involved in conjunction scenarios, including attributes such as NORAD Catalog IDs, Object Names, Time of Closest Approach (TCA), and risk assessment parameters.

**Data Source:**

The sample dataset for predicted conjunctions can be downloaded from CelesTrak.

Details of the RSOs predicted to be in conjunction can be viewed at CelesTrak Satcat.

**Questions:**

**Question 1:**

A) **Derive High-Level Analytics for a Single Day**

**Objective:** Provide general analytics for the entire set of conjunction scenarios for a single day.

**Example Metric:** Number of conjunctions among active satellites.

B) **Represent Conjunctions Data of a Single Satellite**

**Objective:** Provide intuitive analytics and visualizations for a single satellite or a satellite constellation.

**Focus:** Enable decision-making from a satellite operator’s perspective.

**Question 2:**

**Objective:** Utilize the entire dataset spanning approximately five days to derive analytics and visualize the data, considering the evolution from the first day.

**Example Metric:** Number of conjunctions for the RSO with NORAD ID 12345 over a period of 7 days.

**Assumptions:**

**Data Integrity:**

Assumed that the provided data accurately represents conjunction scenarios, accounting for potential limitations or known inaccuracies.

**Conjunction Definition:**

Defined based on criteria such as minimum separation distance, relative speed, and maximum probability of collision.

**Active Satellites:**

"Active satellites" refer to operational satellites currently in use, excluding decommissioned or non-functional satellites from the analysis.

**Orbital Dynamics:**

Assumed that the orbital dynamics of the satellites follow established laws of celestial mechanics without significant perturbing forces.

**Response Time:**

A predetermined response time for satellite operators to take action after being alerted about a potential conjunction is assumed.

**Risk Tolerance:**

Predefined risk tolerance levels or thresholds guide decision-making in conjunction scenarios.

**External Factors:**

External factors like space weather conditions or communication delays may impact conjunction assessments.

**Instructions:**

1. Download the sample dataset "sort-minRange.csv" from the provided CelesTrak link.

2. Ensure you have the necessary tools (Python, pandas, Dash, Plotly) installed to run the provided code for data visualization.
