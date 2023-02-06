# Humana-Mays-Healthcare-Case-Competition-2022

### Competition Website
https://mays.tamu.edu/humana-tamu-analytics/

### Brief Introduction
- This competition offers an opportunity for U.S. masters students to showcase their analytical skills and solve a real-world business problems for Humana utilizing real data.

### Problem Statement
- Housing insecurity is the focus of this year’s case competition and is defined as the lack of access to quality and safe housing. It may include scenarios such as lack of affordability, unsafe/overcrowded conditions or frequent moves. 37.1 million American households are “housing cost-burdened,” and 32.7% of older adult households have severe housing problems. Resulting health problems can range from allergies to neurological to heart damage.
- Using the provided data and potentially supplementing it with public data, create a model to identify Medicare members most likely to be struggling with housing insecurity issues and propose solutions that help people achieving their best health. 

### Competition Objectives
- Identify members most likely to be experiencing Housing Insecurity issues
- Provide recommendations & potential solutions based on the insights derived from the data.
- Ensure analysis and recommendations demonstrate fairness and equity through mitigation of potential bias inherent in the data

### Case Data
- Target population: Humana MAPD members
- Event: Each member will have a binary flag to indicate Housing Insecurity
- Lookback: 1 year look back prior to the date that member responded the screening
- Data warehouse: 800+ features

### Humana will access model accuracy & fairness
- Judging metrics will be established based on each team’s scored file
    - ROC curves generated & AUC metric will be calculated
    - Disparity Score and corresponding weighting will be calculated utilizing RACE & SEX
- Based on the 2 metrics, a final combined metric will be assigned to each team’s submission
    - Combined Metric = AUC * Disparity Score Weight
- Top 50 teams will be identified and selected using a combined metric 
