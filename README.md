# Rider Delivery Time Performance Analysis Dashboard

## Project Overview

This project presents an interactive Power BI dashboard designed to analyze rider delivery time performance in a food-delivery platform environment. It examines the time taken at different stages of the delivery process, helping identify potential operational bottlenecks, monitor rider performance, and evaluate delivery efficiency across zones, dates, and individual riders.

The dashboard uses synthetic/generated data created for portfolio and analytical learning purposes. It is not connected to Pathao's actual systems and does not represent its real operational performance.

## Business Problem

Timely delivery is an important factor in customer experience and delivery operations. Delays can occur at multiple stages, including rider acceptance, arrival at the restaurant, and delivery completion.

Monitoring only the total delivery time may not reveal where delays originate. This project separates the delivery process into measurable stages and applies a performance classification framework to highlight records that may require further investigation.

## Project Objectives

- Monitor rider performance across key delivery time indicators.
- Analyse order acceptance and rider arrival times.
- Evaluate delivery time and total delivery time trends.
- Identify zones, dates, and riders associated with higher levels of delivery delay.
- Classify delivery performance into All Good, Warning, and Red Flag categories.
- Support data-driven investigation of delivery bottlenecks and operational inefficiencies.

## Delivery Time Framework

The dashboard evaluates three key performance parameters:

| Parameter | Operational meaning | Target threshold |
|---|---|---|
| Accept Time | Time taken by the rider to accept an assigned order | 3 minutes |
| Arrived Time | Time from order acceptance until the rider arrives at the restaurant | 5 minutes |
| Delivery Time | Time from the rider's arrival at the restaurant until delivery is completed at the customer | 20 minutes |

**Total Delivery Time** combines the three stages: Accept Time + Arrived Time + Delivery Time.

These thresholds are analytical assumptions used in this portfolio project, not verified official company service-level targets.

## Rider Performance Classification

The dashboard classifies overall delivery performance based on how many parameters exceed their thresholds or are missing.

- **All Good:** None of the three parameters is flagged.
- **Warning:** At least one parameter is flagged, but fewer than all three are flagged.
- **Red Flag:** All three parameters are flagged.

This classification helps prioritise records for further review. A Red Flag indicates that all three checks require attention, while a Warning highlights a potential issue in at least one stage.

## Dashboard Features

- **KPI Cards:** Total riders, total orders, average distance, acceptance time, arrival time, delivery time, and total delivery time.
- **Performance Summary:** Overall counts and percentages for All Good, Warning, and Red Flag orders.
- **Zone Analysis:** Compare flagged orders across delivery zones to identify areas requiring investigation.
- **Date-Based Analysis:** Track Red Flag orders and delivery time indicators over time.
- **Stage-Level Trend Analysis:** Review changes in acceptance, arrival, delivery, and total delivery times.
- **Rider Performance Tables:** Compare rider-level performance across the three classification categories.
- **Late Order Details:** Inspect rider-level order counts and related time metrics.
- **Interactive Filtering:** Explore results by zone, date, and performance classification.

## Business Value

This dashboard demonstrates how delivery-time data can be converted into actionable operational questions, such as:

- Which delivery zones have the highest concentration of flagged orders?
- At which stage do delivery delays appear most frequently?
- How do acceptance, arrival, and delivery times change over time?
- Which riders or groups of riders may require further performance review?
- Are delivery performance patterns improving or deteriorating across the selected period?

The findings can help operations teams prioritise investigations, monitor performance trends, and explore opportunities to improve delivery efficiency.

## Tools and Skills

- Power BI — interactive dashboard development and data visualisation
- DAX — KPI calculations and performance classification
- Data Analysis — time-based, zone-based, and rider-level analysis
- Operational Analytics — delivery performance monitoring and bottleneck investigation
- Data Storytelling — presenting operational indicators for business decision-making

## Data Disclaimer

All data used in this project is synthetic/generated for portfolio demonstration and learning purposes. The dashboard is not connected to Pathao's actual operational systems. The company name is used only to describe the intended food-delivery context; the analysis does not represent actual Pathao data, performance, or endorsement.
