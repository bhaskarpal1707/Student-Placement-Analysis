
![Image1]([images/cgpa_vs_placement.png](https://github.com/bhaskarpal1707/Student-Placement-Analysis/blob/main/image1.png?raw=true))
# 📊 Student Placement Analysis: Visualizing Success Factors in Campus Hiring

## 🔍 Project Overview

**Student Placement Analysis** is a data-driven project aimed at uncovering the key academic and demographic factors that influence campus placement success. By analyzing a real-world dataset of over 1,100 students, this project provides actionable insights for educators, career counselors, and students.

* **Dataset**: 2,966 raw records → 1,137 cleaned unique entries
* **Goal**: Identify major factors that contribute to successful student placements
* **Approach**: Data cleaning, EDA, and visual storytelling using Python

---

## 🌟 Objectives

* Understand dataset structure and quality
* Clean and preprocess for analysis
* Perform exploratory data analysis (EDA)
* Visualize trends and draw insights
* Guide institutional strategies and student decision-making

---

## 🛠️ Tools & Technologies

| Tool           | Purpose                                                                 |
| -------------- | ----------------------------------------------------------------------- |
| **Python**     | Core programming language for the analysis                              |
| **Pandas**     | Data cleaning, manipulation, and exploration                            |
| **Matplotlib** | Static plotting for distributions and comparisons                       |
| **Seaborn**    | Enhanced visualization with statistical plots (heatmaps, boxplots, etc) |
| **Jupyter**    | Notebook interface for combining code, output, and explanation          |

---

## 🧹 Data Cleaning & Preprocessing

* **Missing Values**: None found
* **Duplicates**: Removed 1,829 duplicate entries
* **Data Types**: Categorical columns converted to `category` dtype
* **Consistency**: Validated unique values for `Gender`, `Hostel`, `Backlogs`, and `Stream`

---

## 📈 Key EDA Insights

| Factor               | Observation                                                |
| -------------------- | ---------------------------------------------------------- |
| **Placement Rate**   | \~55% students placed; \~45% not                           |
| **Gender**           | Males slightly more likely to be placed                    |
| **Stream**           | CSE and ECE students have higher placement rates           |
| **Age**              | Most students are 21–22 years; age has minimal impact      |
| **CGPA**             | Strong positive correlation with placement                 |
| **Internships**      | More internships significantly boost placement probability |
| **Hostel Residency** | Slight positive impact on placement                        |
| **Backlogs**         | Major negative impact on placement                         |
| **Top Predictors**   | CGPA, Internships, Backlogs                                |

---

## 🔍 Visualizations Include

* Target Distribution
* Placement by Gender
* Stream-wise Placement
* CGPA vs Placement
* Internships Impact
* Backlogs vs Placement
* Correlation Heatmap

---

## 📌 Conclusions

* **High CGPA** and **multiple internships** are strong indicators of placement success.
* **Backlogs** substantially reduce placement chances.
* **Stream** and **hostel residency** have moderate impact.
* **Age** is not a reliable predictor.

---

## ✅ Recommendations

* Encourage students to pursue **internships** early.
* Emphasize the importance of **academic consistency** (high CGPA).
* Support systems for students with **backlogs**.
* Customize career training by **stream-specific trends**.

---

## 📁 Files Included

* `Student-Placement-Analysis.ipynb`: Full notebook with code, analysis, and visualizations
* `collegePlace.csv`: Cleaned dataset used for EDA
* `Student Placement Analysis.pdf`: Project summary and presentation deck

---

## 📬 Contact

For queries or collaborations:
**Bhaskar Pal**
📧 [bhaskarpal.official@gmail.com](mailto:bhaskarpal.official@gmail.com)
