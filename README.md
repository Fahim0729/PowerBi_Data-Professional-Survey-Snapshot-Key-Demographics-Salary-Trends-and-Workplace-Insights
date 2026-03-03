## 📊 Data Professional Survey Analysis: Key Demographics, Salary Trends, and Workplace Insights

##### 🟩 This survey offers a detailed view of data professionals, demographics, salary trends, programming interests, and overall job satisfaction, highlighting key trends in the field.
---

🛠️ **Tools Used**

- **Power BI:** Dashboard development and visual analysis (Card, Line, Area, Stacked Column, Pie, Gauge, Treemap)

- **Power Query & DAX:** Data cleaning, transformation, and calculated metrics (e.g., Average Salary)

- **Excel / CSV:**  Raw data storage and inspection

- **Data Modeling:** Linking datasets via Unique ID for relational analysis

**Purpose:** Enabled clean, standardized data and actionable insights for reporting.

---

📊 **Data Overview**

<div align="center">

| Specification   | Details                                                                                                                                                         |
|:---------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Survey Size     | 630                                                                                                                                                           |
| Missing Values  | None                                                                                                                                                          |
| Data Sources    | [Demographics](Demographics.xlsx), [Career & Compensation](https://github.com/Fahim-Hossain-Data/PowerBi_Data-Professional-Survey-Snapshot-Key-Demographics-Salary-Trends-and-Workplace-Insights/blob/f5c5e75b524661b01b47b8d0badcb696b88d873d/Career%20%26%20Compensation.xlsx), [Job Satisfaction & Survey](https://github.com/Fahim-Hossain-Data/PowerBi_Data-Professional-Survey-Snapshot-Key-Demographics-Salary-Trends-and-Workplace-Insights/blob/f5c5e75b524661b01b47b8d0badcb696b88d873d/Job%20Satisfaction%20%26%20Survey.xlsx) |

</div>

---

🗄️ **Data Modeling & Dashboard**

Initially, three dataset are loaded into Power BI. These datasets are connected using a Unique ID. The figure below illustrates the data model.
<p align="center">
  <img src="https://github.com/Fahim0729/PowerBi_-Data-Professional-Survey-Snapshot-Key-Demographics-Salary-Trends-and-Workplace-Insights/blob/a9b0aba0c9a0e960bdaad406e8a066decc8629fc/Data_Modeling.png" alt="Histogram" width="600"/>
  <br>
  <em>Figure: Conceptual Data Model and Relationships </em>
</p>


📊 The dashboard has interactive visualization, including Card, Area Chart, Line Chart, Stack Column Chart, Pie Chart, Gauge, and Treemap, to study the demographics, salaries, preference in programming, and job satisfaction is as follows:

<p align="center">
  <img src="https://github.com/Fahim0729/PowerBi_-Data-Professional-Survey-Snapshot-Key-Demographics-Salary-Trends-and-Workplace-Insights/blob/a9b0aba0c9a0e960bdaad406e8a066decc8629fc/DashBoard.png" alt="Histogram" width="600"/>
  <br>
  <em>Figure: Power BI Dashboard for Data Visualization </em>
</p>

---

## 📝 Key Findings

Following are the key findings of the survey:

🟩 Survey respondents:  A total of 630 data professionals from various countries participated in this survey.

🟩 Average age of responds: The average age of a survey respondent is **29.87 years**, indicating a relatively young workforce.

🟩 Salary Insights:  Data Scientists are paid the most among the positions that were surveyed. The top three roles are:
- **Data Scientists:** $94.04k
- **Data Engineers:** $65.29k
- **Data Architects:** $64.00k

🟩 Country Participation: The **United States** is the most responsive nation with **261** responses. **Canada** had the fewest respondents.

🟩 Gender pay gap: he gender distribution is almost balanced (Male: 50.81, Female: 49.19), but the average salary of males is slightly higher, indicating that there is a slight but existing gender pay gap in this survey group.

🟩 Age vs Salary Satisfaction: 
- The greatest changes in happiness are observed in **younger and mid-career professionals** who have ratings between **3 and 8** out of 10.
- **Older respondents (aged 66 and above)** is much more stable, as the rating of happiness is around **5 out of 10**.

🟩 Programming Language Preferences: **Python** is the overwhelming favorite. On the other end of the spectrum, **Java** was identified as the least popular language in this survey.

🟩 Workplace Satisfaction: 
- **Work/Life Balance:** Received a moderate average rating of **5.74/10**.

- **Coworker Relationships:** is rated slightly higher, at **5.86 out of 10**.

---

## 🔧 Data Preprocessing

This section will describe the data cleaning and transformation procedures which will be used in preparing the raw survey data to be analyzed.

📝 **Salary Range → Average Salary**

- Converted ranges (e.g., “50k-65k”) to numeric values

- Handled “150k+” as 225k

- Calculated Average Salary:
    ```
    (Minimum Salary + Maximum Salary) / 2
    ```


📝 **Standardizing “Other” Categories**

- Split write-ins in columns like Favorite Programming Language or Industry using "(" or ":" as delimiters
- Only retained the main category **Other**, and eliminated all additional text or descriptions in parentheses or following a colon.

---

## 📌 Conclusion

This study gives important information on the demographics of data professionals, salary rates, programming favourites, and job satisfaction. The standardized and cleaned data provide the correct results, which can be used as a good benchmark to the industry trend and decision-making.

---

## 🌐 I’d Love to Connect!

- **LinkedIn:** [Md Fahim Hossain](https://www.linkedin.com/in/md-fahim-hossain-b51258227/)  
- **Email:** [fahimhossain0729@gmail.com](mailto:fahimhossain0729@gmail.com)


<div align="center">
  
**[⬆ Back to Top](#top)**

</div>
