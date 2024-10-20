# **Sexual Assault Cases in Assam: Data Analysis (1999-2013)**

## **Overview**

This project provides an in-depth analysis of sexual assault cases in **Assam, India**, focusing on cases where the offenders were known to the victims. The dataset spans the years 1999 to 2013 and includes different categories of offenders such as parents, close family members, relatives, neighbors, and other known persons. The goal is to identify patterns, trends, and correlations to better understand the dynamics of sexual assault cases in Assam during this period.

## **Dataset Information**

The dataset includes the following columns:

- **STATE/UT**: Represents the state or union territory (Assam in this case).
- **YEAR**: The year when the data was collected.
- **No. Of Cases In Which Offenders Were Known To The Victims**: Total number of cases where offenders were known to the victims.
- **No. Of Cases In Which Offenders Were Parents / Close Family Members**: Number of cases involving parents or close family members as offenders.
- **No. Of Cases In Which Offenders Were Relatives**: Cases where the offenders were other relatives.
- **No. Of Cases In Which Offenders Were Neighbours**: Cases where the offenders were neighbors.
- **No. Of Cases In Which Offenders Were Other Known Persons**: Cases involving other known persons as offenders, excluding family members and neighbors.

## **Analysis and Visualizations**

The analysis is performed using **pandas**, **matplotlib**, and **seaborn**, providing key insights into sexual assault trends in Assam. The main components of the analysis include:

### 1. **Data Cleaning and Preprocessing**:
   - Managed missing values and errors in the dataset.
   - Ensured consistency in column formats across the years for effective analysis.

### 2. **Line Graph: Yearly Trend of Cases**:
   - A line graph showcasing the number of sexual assault cases involving known offenders over the years in Assam.
   
### 3. **Correlation Analysis**:
   - A **heatmap** depicting the correlation between different offender types, such as parents, relatives, neighbors, and other known offenders, highlighting relationships between these categories.

### 4. **Total Number of Cases by Known Offenders**:
   - An analysis of the total number of cases involving known offenders, with specific focus on different offender types across the years.

### 5. **Yearly Distribution of Offender Types**:
   - A detailed yearly breakdown of the number of cases involving parents, relatives, neighbors, and other known persons in **Assam**.

### 6. **Cumulative Cases Over Time**:
   - A cumulative time-series plot showing the number of cases over time, focusing specifically on **Assam**, to identify the rise in cases during certain periods.

### 7. **Top Years with Highest Offender Cases in Assam**:
   - A bar chart highlighting the years with the highest number of known offender cases, showing the most concerning periods in terms of sexual assault cases.

### 8. **Pivot Table Summary**:
   - A pivot table summarizing the data by offender types across different years in Assam, helping to identify which types of offenders were more common in specific years.

## **Key Findings**

- **Year-on-Year Growth**: Some years saw a substantial increase in cases involving known offenders.
- **Offender Categories**: **Known Person and neighbors** made up a significant portion of the offenders in Assam.
- **Cumulative Growth**: The cumulative number of cases showed a sharp increase from **2002** to **2013**, signaling a worrying trend in known offender cases.
- **Most Affected Years**: **2012** stands out as one of the top years in **Madhya Pradesh** with the highest number of sexual assault cases involving known offenders.
- 
## **Technologies Used**

- **Python**: For data cleaning, preprocessing, and analysis.
- **pandas**: Used for handling, cleaning, and manipulating the dataset.
- **matplotlib**: For visualizing trends, bar charts, and line graphs.
- **seaborn**: To generate heatmaps and correlation analyses.


## **Visualizations**

Here are some of the visualizations generated during this analysis:

1. **Yearly Trend**:
   - A line graph showing how sexual assault cases involving known offenders have evolved from 1999 to 2013 in Assam.

2. **Correlation Heatmap**:
   - A heatmap visualizing the correlation between different offender categories, such as relatives, parents, and neighbors.

3. **Top Years with the Highest Offender Cases**:
   - A bar chart showcasing the years in Assam with the highest number of sexual assault cases involving known offenders.

4. **Cumulative Cases Over Time**:
   - A cumulative plot visualizing the total number of cases over time.
