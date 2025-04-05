# 📘 Data Professionals Survey Dashboard

## 🧾 Overview

This project presents a comprehensive analysis of the **global data professional workforce**, based on a survey of **630 respondents**. The dashboard built in Power BI delivers key insights into salaries, job satisfaction, programming preferences, and career demographics, allowing for a quick and interactive understanding of trends shaping the data field today.

---

## 📁 Project Files

- **Power BI - Final Project.xlsx**: Raw dataset with survey responses.
- **Data Professionals Survey.pbix**: Power BI project file containing data transformations and visuals.
- **Data Professionals Survey.pdf**: Exported report visuals from the final Power BI dashboard.

---

## 🎯 Objectives

- Identify the most common job titles and roles within data professions.
- Analyze salary trends by job title, gender, and geography.
- Examine satisfaction levels across different aspects of data roles.
- Understand the most popular programming languages.
- Highlight job market preferences and demographic breakdowns.

---

## 🧠 Key Metrics and Figures

- **👥 Number of Participants**: `630`
- **📊 Average Age**: `29.87`
- **💰 Salary (Overall and Segmented)**:
  - By **job title**
  - By **gender**
- **💬 Satisfaction Ratings**:
  - Salary: Avg `4.27` out of 10
  - Work-life balance: Avg `5.74` out of 10

---

## 📊 Dashboard Visuals

The dashboard includes the following visuals:

### 🔹 Average Salary by Job Title
Bar chart comparing average annual salary across roles:
- **Top earners**: Data Architect > Data Scientist > Data Engineer
- **Lowest earners**: Students/Interns, Data Analysts

### 🔹 Favorite Programming Languages
Bar chart of vote counts for preferred programming languages:
- **Top 3**: Python, R, SQL
- Others include: Java, JavaScript, C/C++, Other

### 🔹 Participants by Country
Bar chart with top 5 countries:
- United States, India, United Kingdom, Canada, Others

### 🔹 Average Salary by Gender
Dual gender breakdown showing:
- Salary comparison
- Gender distribution (approx. 50.8% Male, 49.2% Female)

### 🔹 Happiness Ratings
Numeric KPIs showing:
- **Salary satisfaction**: `4.27` / 10
- **Work-life balance**: `5.74` / 10

---

## 🔧 Data Preparation

Using Power Query within Power BI:
- Removed columns with all null values (e.g., Browser, OS, City).
- Cleaned up inconsistent text entries in job titles and countries.
- Converted salary to numeric format, removed currency symbols.
- Created custom calculated fields like:
  - Age groups
  - Satisfaction averages
  - Career switch indicators

---

## 🛠 Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query Editor (M Language)**
- **Excel (Raw Data Handling)**

---

## 📌 Key Insights

- **Python dominates** as the most loved programming language.
- **Salary satisfaction is relatively low** across the board (avg 4.27/10).
- **Data Architects earn the highest average salary**, followed closely by Data Scientists and Engineers.
- **Gender pay gap is evident** in the salary by gender visual.
- **Respondents are mostly aged around 30**, suggesting a younger, early-career demographic.
- The **U.S. and India** dominate the participant distribution.

---

## 🧩 Challenges

- Incomplete data in some columns (e.g., geo fields like city and browser).
- Variability in free-text entries for job titles and countries required manual normalization.
- Subjective responses (e.g., satisfaction scores) vary widely, making statistical averages sensitive.

---

## 📌 Conclusion

This project provides a compelling snapshot of the modern data professional's experience, preferences, and satisfaction. It’s a valuable resource for HR professionals, educators, and aspiring data analysts seeking to understand the industry's evolving dynamics.

---

## 📄 Future Recommendations

- Collect more granular location data for city-level insights.
- Add a time-based element to explore trends over years.
- Include open-text analysis (e.g., reasons for job satisfaction/dissatisfaction).
- Enable filtering by education level or years of experience.
