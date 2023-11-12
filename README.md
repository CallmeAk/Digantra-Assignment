# Digantra-Assignment
Overview:

Conjunctions in space happen when two or more active satellites in Earth's orbit come dangerously close, potentially leading to collisions. This assignment focuses on analyzing and visualizing predicted conjunctions of these satellites. The data set provided contains information about the satellites involved, including NORAD Catalog IDs, Object Names, Time of Closest Approach (TCA), and risk assessment parameters.

Data Source:

You can get the sample data set for predicted conjunctions from CelesTrak.

Details about the satellites predicted to be in conjunction can be found at CelesTrak Satcat.

Questions:

Question 1:

A) Derive High-Level Analytics for a Single Day

Objective: Provide general analytics for all the conjunction scenarios for one day.

Example Metric: Count the number of conjunctions among active satellites.

B) Represent Conjunctions Data of a Single Satellite

Objective: Provide easy-to-understand analytics and visualizations for one satellite or a group of satellites.

Focus: Help satellite operators make decisions.

Question 2:

Objective: Use the entire data set spanning about five days to derive analytics and visualize the data, considering the evolution from the first day.

Example Metric: Count the number of conjunctions for the satellite with NORAD ID 12345 over a period of 7 days.

Assumptions:

Data Integrity:

Assume the provided data accurately represents conjunction scenarios, considering potential limitations or known inaccuracies.

Conjunction Definition:

Conjunctions are defined based on criteria like minimum separation distance, relative speed, and maximum probability of collision.

Active Satellites:

"Active satellites" refer to operational satellites currently in use, excluding decommissioned or non-functional satellites.

Orbital Dynamics:

Assume the satellites' orbital dynamics follow established laws of celestial mechanics without significant perturbing forces.

Response Time:

Assume there's a set time for satellite operators to take action after being alerted about a potential conjunction.

Risk Tolerance:

Decision-making in conjunction scenarios is guided by predefined risk tolerance levels.

External Factors:

External factors like space weather conditions or communication delays may impact conjunction assessments.

Instructions:

1. Download the sample data set "sort-minRange.csv" from the provided CelesTrak link.

2. Make sure you have the necessary tools (Python, pandas, Dash, Plotly) installed to run the provided code for data visualization.
