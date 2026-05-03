# Crime Pattern Analysis in Indian Cities Using Data Visualization Techniques

**Sector:** Urban Safety & Crime Analytics  
**Course:** Data Visualization & Analytics  
**Institution:** Newton School of Technology  
**Date:** 18 February 2026

**Team:** Bhargav Patil · Ayush Tiwari · Saumya Soni · Aparna Singh · Priyanshu · Parv

---

## 1. Executive Summary
Urban crime across Indian cities varies by location, crime category, demographics, and time. This project analyzes **40,000+ crime records across 29 cities** to identify spatial concentration, vulnerable groups, and temporal hotspots for data‑driven policing.

Key findings:
- Crime concentrated in metropolitan cities (Delhi, Mumbai, Bangalore, Hyderabad)
- Other Crime = 57.2%, Violent Crime = 28.8%
- Females = 55.6% of victims (highest in violent crimes)
- Night period shows peak incidents
- Solve rate ≈ 50%

The study demonstrates how pivot analysis and dashboards transform administrative datasets into actionable insights.

---

## 2. Sector & Business Context
### Sector Overview
Rapid urbanization increases complexity of crime patterns requiring optimized resource allocation.

### Current Challenges
- Aggregated statistics hide patterns
- Hard to identify hotspots
- Inefficient policing deployment

### Purpose
Use structured historical data and visualization to support evidence‑based policing decisions.

---

## 3. Problem Statement & Objectives
### Core Problem
Analyze crime distribution to identify high‑risk locations, domains, and vulnerable populations.

### Objectives
- Identify high‑crime regions
- Determine dominant crime categories
- Analyze demographic vulnerability
- Study temporal patterns
- Evaluate case resolution efficiency

### Success Criteria
Clear spatial, temporal, and demographic patterns leading to actionable recommendations.

---

## 4. Dataset Description
- Source: Kaggle Indian Crimes Dataset (Sudhanva HG, 2023)
- Original records: 40,160
- Cleaned analytical dataset: 7,891
- Coverage: 29 cities, 5 domains, 22 categories

### Key Fields
City · Crime Domain · Crime Description · Victim Age · Gender · Date/Time · Police Deployed · Case Status

### Limitations
- Only reported crimes
- Missing values handled via preprocessing
- No socio‑economic context → descriptive analysis only

---

## 5. Data Cleaning & Preparation
Performed using **Python + Google Sheets**

Steps:
1. Removed incomplete entries
2. Standardized categorical variables
3. Standardized date/time formats
4. Created derived variables

### Engineered Features
- Victim group (age category)
- Resolution days
- Reporting delay
- Resolution category
- Time‑of‑crime period
- Month & year attributes

---

## 6. KPI Framework
| KPI | Definition | Purpose |
|----|----|----|
| Total Cases | Count of records | Crime scale |
| YoY Growth | % change yearly | Trend tracking |
| Ongoing Cases | Not closed | Workload |
| Solved Cases | Closed cases | Performance |
| Solve Rate | Solved / Total | Efficiency |
| Avg Resolution Time | Days to close | Speed |
| Avg Police per Crime | Officers assigned | Resource intensity |

---

## 7. Exploratory Data Analysis
### Crime Distribution
- Other Crime: 57.2%
- Violent Crime: 28.8%
- Fire Accidents: 9.35%
- Traffic Fatalities: 4.65%

### City Concentration
Highest incidents in metro cities.

### Gender Analysis
Females: 55.6% victims → higher vulnerability

### Temporal Pattern
Night‑time peak across cities.

### Investigation Status
Solved ≈ 50% | Active ≈ 50% | Avg resolution ≈ 90 days

---

## 8. Advanced Analysis Insights
- Spatial risk highest in large cities
- Violent crimes strongly linked to female victims
- Consistent night‑time risk
- Balanced but moderate investigation closure

---

## 9. Dashboard Design
Implemented in Google Sheets using pivot tables and filters.

### Features
- KPI summary panel
- City & crime distribution charts
- Gender analysis
- Time‑of‑crime visualization
- Investigation status tracking
- Interactive filters & drilldowns

---

## 10. Key Insights
1. Urban crime concentrated in metros
2. Non‑violent crimes dominate volume
3. Female victimization elevated
4. Night‑time risk highest
5. Moderate closure efficiency (~50%)

---

## 11. Recommendations
| Action | Impact | Feasibility |
|------|------|------|
| Target metro policing | Reduce hotspots | High |
| Female safety measures | Reduce victimization | Medium‑High |
| Night patrol intensification | Reduce incidents | High |
| Focused violent crime units | Lower severity | Medium |
| Improve resolution workflows | Faster closure | Medium‑High |
| Data‑driven monitoring | Proactive policing | Medium |
| Community reporting | Better detection | Medium |
| Urban planning integration | Long‑term reduction | Medium‑Low |

---

## 12. Impact Estimation
**Cost Savings:** Optimized patrol deployment  
**Efficiency:** Faster investigation throughput  
**Service Improvement:** Higher public safety perception  
**Risk Reduction:** Lower night & metro crime concentration

---

## 13. Limitations
- Reported incidents only
- Missing values preprocessing
- No causal inference

---

## 14. Future Scope
- Longitudinal trend analysis
- Neighborhood‑level hotspot mapping
- Integrate socio‑economic data
- Predictive crime modeling
- Real‑time dashboards

---

## 15. Data Dictionary (Key Columns)
| Column | Description |
|------|------|
| Report Number | Unique case ID |
| City | Crime location |
| Crime Domain | Category group |
| Victim Age/Gender | Demographics |
| Police Deployed | Officers assigned |
| Ticket Status | Active/Solved |
| Resolution Days | Closure duration |
| Time of Crime | Morning/Afternoon/Night |

---

## 16. Tools Used
- Python (initial structuring)
- Google Sheets (analysis & dashboard)
- Pivot tables & visualization

---

## 17. Contribution Matrix
All team members contributed across sourcing, cleaning, analysis, dashboard, and documentation.

---

## License
Educational academic project — analytics demonstration only.

