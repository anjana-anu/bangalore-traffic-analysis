
# Bangalore Traffic Analysis: From Raw Data to Actionable Insights
**Author**: Anjana A

## 📌 Project Overview
This project presents an end-to-end Data Analytics workflow that analyzes real-world urban mobility data from Bangalore. The goal is to move beyond simply stating "Bangalore has bad traffic" and instead use data to prove exactly *why*, *where*, and *when* the congestion happens. 

### Objectives
* **Primary Objective**: To identify the root causes of traffic congestion in Bangalore and provide data-driven, actionable recommendations for infrastructure and traffic management.
* **Technical Objective**: To demonstrate a complete data analytics portfolio project—taking a "dirty" Kaggle dataset, cleaning it using Python, uncovering hidden patterns through Exploratory Data Analysis (EDA), and translating the findings into a visually compelling, interactive story using Power BI.

## 📊 About the Data
The dataset was originally sourced from Kaggle and contains comprehensive metrics on behavioral patterns, infrastructure utilization, and a multi-dimensional view of urban mobility in Bangalore. 

**Key Features Include:**
* **Categorical Data**: Area Name (e.g., Koramangala, Indiranagar, Whitefield), Road/Intersection Name, Weather Conditions, etc.
* **Continuous Numerical Data**: Traffic Volume, Average Speed, Congestion Level, Incident Reports, and Pedestrian/Cyclist Count.
* **Time-Series Data**: Daily records (e.g., Date, Day of Week) allowing for trend analysis.

*Note: The repository contains both the original raw data (`Banglore_traffic_Dataset_raw.csv`) and the processed, analytics-ready dataset (`bangalore_traffic_cleaned_final.csv`) which includes engineered features like Day of the Week.*

## 🛠️ Tools Used
* **Python**: Data cleaning and Exploratory Data Analysis (EDA).
* **Power BI**: Creation of interactive dashboards to visually communicate findings.
* **PowerPoint**: Executive presentation summarizing insights and recommendations (`Final_Project.pptx`).

## 💡 Key Findings
1. **The Mid-Week Surge**: Traffic volume actually peaks mid-week, with Wednesdays seeing an average of 34,506 vehicles. This proves Bangalore's traffic has a heavily commercial profile that surges beyond the traditional weekend rushes.
2. **Regional Vulnerability & Bottlenecks**: Koramangala and M.G. Road consistently display the highest congestion levels. The traffic in these zones is "inelastic," meaning the volume doesn't drop significantly even when traffic speeds slow down to a crawl.
3. **The Weather-Safety Link**: Weather acts as a massive system disruptor. While 60% of high-speed travel occurs during "Clear" weather, rain triggers an immediate 30-40% drop in speed. Furthermore, incident reports spike disproportionately during fog and rain.
4. **The Silent Majority**: The data recorded a massive 683,000 pedestrians and cyclists. While cars drive the current congestion, there is a clear, undeniable demand for alternative, non-motorized transport.

## 🚦 Actionable Recommendations
Based on the data insights, the following infrastructure and management strategies are recommended:
* **Shift Shift-Alignments**: Align traffic police shifts and public transit frequency to prioritize the "Tuesday-Wednesday-Thursday" mid-week peak rather than just Mondays and Fridays.
* **Smart Signals**: Prioritize "Smart Signal" technology and intersection redesigns specifically for inelastic zones like Koramangala and M.G. Road to prevent city-wide spillover.
* **Weather-Responsive Management**: Implement weather-responsive speed limits and active real-time "Hazard Warning" digital signage at major junctions.
* **Protect the Non-Motorized Users**: Capitalize on the massive pedestrian/cyclist volume by building dedicated cycle tracks and improving sidewalks in high-volume areas to encourage the shift away from motor vehicles.

## 📂 Project Structure
* `Banglore_traffic_Dataset_raw.csv`: The initial, uncleaned dataset.
* `bangalore_traffic_cleaned_final.csv`: The cleaned dataset used for modeling and BI.
* `Final_Project.pptx`: The executive summary presentation.
* `[Insert Power BI File Name].pbix`: The interactive Power BI dashboard tracking mobility metrics.