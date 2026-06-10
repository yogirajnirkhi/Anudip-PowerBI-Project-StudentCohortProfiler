# Anudip-PowerBI-Project-StudentCohortProfiler
A Data analysis and Visualization project made in PowerBI 


<img width="887" height="498" alt="image" src="https://github.com/user-attachments/assets/cd9e9b9b-761a-44e5-947e-31c9f9302f30" />


An analytics dashboard designed to explore the relationships between academic performance, enrollment demographics, behavioral traits, and student well-being. By cross-examining metrics like study habits, stress levels, attendance, and external commitments, this project uncovers the underlying patterns that drive or hinder student success.

## Dataset Specifications

**Student Performance & Lifestyle Dataset**, a synthetic collection of 1,000 unique student profiles

* **Dataset Source:** [Kaggle - Student Performance Dataset by lightningxyz](https://www.kaggle.com/datasets/lightningxyz/student-performance-dataset)
* **Dataset Size:** 1,000 records, 21 columns

**Data Features:**
* **Demographics:** Name, Age (ranging from 18–25), Gender, Major (STEM, Business, Arts, Humanities), and Living Area (Urban/Suburban/Rural).
* **Socioeconomic/Background:** Parent Education level, Scholarship Status, and Home Internet Access.
* **Behavioral & Lifestyle:** Weekly Study Hours, Average Sleep Hours, Attendance Rates, Self-Reported Stress Levels (0–10), Part-Time Job Status, and Extracurricular Activities.
* **Target Variables:** Performance Score (Continuous scale from 0–100) and Final Letter Grade (A, B, C, D, F).

## Dashboard Visualizations & Insights

### 1. Overall Grade Distribution (Pie Chart)

* **What it shows:** A macro-level breakdown of final letter grades across the entire cohort.
* **Insight:** The vast majority of the student population falls into the average-to-above-average tier. Grade **B** is the most frequent outcome at 46.9% (469 students), followed closely by Grade **C** at 38.7% (387 students). Elite performers (Grade **A**) make up 8.3% (83 students), while struggling cohorts (Grades **D** and **F**) represent the remaining minority.

### 2. Academic Output vs. Total Attendance (Stacked Bar)

* **What it shows:** A balanced comparison between the normalized averages of student performance scores and their physical attendance rates.
* **Insight:** The close split (47.46% performance score vs. 52.54% attendance) indicates a stable baseline where attendance metrics scale proportionately alongside overall academic output metrics across the cohort.

### 3. Average Score Frequency by Major (Donut Chart)

* **What it shows:** The average academic performance score segmented by fields of study: Arts, Business, Humanities, and STEM.
* **Insight:** Performance is remarkably uniform across disciplines. Average scores hover tightly between **70.11 and 71.41**, with each major accounting for roughly 25% of the score distribution. This indicates that a student's chosen field of study is not a primary discriminator for higher or lower average grades.

### 4. Extracurriculars & Jobs Impact on Grades (Clustered Bar Chart)

* **What it shows:** Academic grades filtered by whether a student holds a part-time job, further cross-referenced by their participation in extracurricular activities.
* **Insight:** Counterintuitively, external commitments do not cause a severe drop in performance. Average score thresholds remain steady regardless of employment status or extracurricular engagement, suggesting that students with extra responsibilities adapt effectively to manage their time.

### 5. Well-being to Grade Correlation (Scatter Plot)

* **What it shows:** Individual student performance mapped against self-reported stress levels on a scale from 0 to 10.
* **Insight:** This chart reveals a clear **negative correlation**. As stress levels climb past 6 and approach 10, the density of high performance scores thins out, and data points slope downward. Lower stress strongly associates with healthier, more consistent academic outputs.

### 6. Total Attendance Proportion by Major (Bar Chart)

* **What it shows:** Cumulative attendance volumes tracked across the four academic majors.
* **Insight:** STEM fields dominate the total volume of classroom attendance, followed by Business, Arts, and Humanities. This variation is driven primarily by the higher concentration of student enrollment within STEM tracks in this cohort.

### 7. Total Points Accumulated by Grade (Area Chart)

* **What it shows:** The total volume of score points pooled together by individual grade brackets.
* **Insight:** Because the cohort is heavily weighted toward mid-tier students, the cumulative points form a steep bell-curve variation that peaks drastically at Grade **B** and **C**, before sharply tapering off for the smaller populations of **A**, **D**, and **F** students.

### 8. Lifestyle Impact (Radar Chart)

* **What it shows:** A multi-axis comparison of three key lifestyle behaviors—Average Sleep Hours, Average Stress Levels, and Average Study Hours—mapped against final grade outcomes.
* **Insight:** High-achieving students (Grade **A**) display a distinct behavioral profile marked by optimal study hour allocation and manageable stress profiles. Conversely, failing brackets (Grade **F**) show distinct imbalances, such as high stress combined with lower study efficiency or disrupted sleep patterns.



