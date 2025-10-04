# COVID-19 Data Analysis: Tamil Nadu Districts

## Project Overview
This project presents a **comprehensive analysis of COVID-19 data** across **40 districts in Tamil Nadu, India**, as reported on **11 May 2021** . Using statistical and visualization techniques, the study highlights pandemic patterns, correlations, outliers.  

## Dataset
The dataset used in this analysis was obtained from the Government of India's Open Data Platform.

**Source**: [data.gov.in](https://www.data.gov.in/resource/covid-19-district-wise-abstract-cases-including-active-cases-discharges-and-deaths-295)  
**Dataset**: *COVID-19: District-wise abstract of cases including active cases, discharges and deaths in Tamil Nadu as on 11/05/2021*  

**Dataset Details:**
- Total Districts: 40  
- Period: Single-day snapshot (May 11, 2021, with comparison to May 10, 2021)  
- Metrics: Active cases, new cases, discharges, deaths  
- Data Quality: No missing values

## Key Statistics (May 11, 2021)
- **Total Active Cases**: 162,181  
- **Total New Cases**: 29,272  
- **Total Deaths**: 298  
- **Total Discharges**: 19,182

## Analysis Methodology
The analysis employed three major visualization techniques:  

1. **Scatter Plots** – Studied correlations between new cases, deaths, discharges, and active cases.  
2. **Box Plots** – Distribution analysis and outlier detection   
3. **Line Plots** – Compared district-level case growth, deaths, and active case changes.

## Detailed Analysis and Observations

### 1. Scatter Plot Analysis: Relationship Patterns
- **Correlation Coefficients**:  
  - New Cases vs Deaths: **0.956**  
  - Active Cases vs New Cases: **0.989**  
  - New Cases vs Discharges: **0.970**  

- **Interpretation**: COVID-19 spread and its effects followed highly predictable patterns. Districts with high new cases also experienced higher deaths and discharges.

### 2. Box Plot Analysis: Outlier Detection
- **Outliers (New Cases on 11 May 2021):**  
  - Chennai: 7,466  
  - Coimbatore: 2,650  
  - Chengalpattu: 2,419  

- **Outliers (Deaths on 11 May 2021):**  
  - Chennai: 92  

- **Interpretation**: Chennai, Coimbatore, and Chengalpattu emerged as clear outliers, with urban districts bearing a significantly higher burden compared to rural ones.

### 3. Line Plot Analysis: District Trends

#### Top Districts with Highest New Cases (11 May 2021)
1. Chennai – 7,466  
2. Coimbatore – 2,650  
3. Chengalpattu – 2,419  
4. Tiruvallur – 1,204  
5. Madurai – 1,024  

#### Top Districts with Highest Deaths (11 May 2021)
1. Chennai – 92  
2. Coimbatore – 19  
3. Chengalpattu – 19  
4. Salem – 18  
5. Tiruvallur – 17  

#### Districts with Highest Increase in Active Cases
- Chennai: +2,791  
- Coimbatore: +908  
- Tiruvannamalai: +551  
- Kanniyakumari: +504  
- Vellore: +483  

#### Districts with Highest Decrease in Active Cases
- Tiruvallur: -122  
- Thoothukudi: -8  
- Villupuram: -3  
- Salem: 0  
- Chengalpattu: +34

#### Interpretation:  
- Chennai clearly dominated both **new cases and deaths**, establishing its role as the **epicenter**.  
- Coimbatore and Chengalpattu were **secondary hotspots**.  
- Some districts like Tiruvallur and Thoothukudi even reported decreases.

## Final Observations & Conclusions

### Key Observations
1. **Urban Concentration** – Chennai, Coimbatore, and Chengalpattu bore the highest burden.  
2. **Predictable Spread** – Strong correlations suggest consistent proportional impacts between new cases, deaths, and recoveries.  
3. **Outlier Identification** – Box plots highlighted major urban centers as hotspots.  
4. **District Variability** – Some districts reported decreases in active cases, indicating effective local control of the outbreak.  

### Final Conclusions
- **Chennai was the pandemic epicenter**, with secondary hotspots in Coimbatore and Chengalpattu.  
- **Predictive modeling** is feasible given strong correlations, useful for forecasting and healthcare planning.  
- **Policy Action**: Resources should be prioritized for urban hotspots while learning from rural districts and high-performing regions.  
- **Overall Insight**: COVID-19’s impact was **unevenly distributed**, requiring **district-specific healthcare strategies** instead of a uniform state-wide approach.  

## Technical Implementation
- **Language**: Python  
- **Libraries**: Pandas, Matplotlib, NumPy  
- **Plots Used**: Scatter, Box, Line  
- **Analysis Methods**: Correlation analysis, Outlier detection, Trend analysis  

## Repository Structure
├── Data_analysis_Covid19_TamilNadu.ipynb # Main notebook

├── districtwise_abstract_of_cases_including_active_cases_discharges_and_deaths_in_tn_as_on_11_05_2021.csv # dataset

└── README.md # This analysis report

## Data Disclaimer
This analysis is based on **official government data (data.gov.in)** as of **May 11, 2021**.  
The results reflect the pandemic situation on that specific date during the **second wave of COVID-19 in India**.  
 
