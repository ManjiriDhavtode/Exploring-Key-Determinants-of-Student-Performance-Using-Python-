### Project Title: **Student Performance Analysis**

#### Description:
This project analyzes various factors influencing students' academic performance using a dataset containing attributes such as attendance, access to resources, parental involvement, family income, and more. The goal of the analysis is to identify significant factors affecting exam scores and provide actionable insights for improving student outcomes. The project employs Python for data cleaning, analysis, and visualization, showcasing key relationships through compelling plots and statistical tests.

---

#### Key Features:
1. **Correlation Analysis**:
   - Explores the correlation between attendance percentage and exam scores, showing a **moderate positive relationship (0.58)**.

2. **Impact of Resources**:
   - Conducted a statistical test revealing a **significant difference in exam scores** between students with high/medium access to resources and those with low access.

3. **Parental Involvement**:
   - Demonstrates that students with high parental involvement score significantly better than those with low involvement.

4. **Income Level**:
   - Analyzed the impact of family income on exam scores, highlighting that students from high or medium income families perform better than those from low-income families.

5. **School Type**:
   - Compares the performance of students in private vs. public schools using a t-test, revealing no significant difference in exam scores.

6. **Other Insights**:
   - Variables like **hours studied** showed a strong positive correlation with exam scores.
   - **Sleep hours** and **tutoring sessions** exhibited minimal or no impact on performance.
   - **Distance from school** slightly influenced exam scores, with students living closer performing better.

---

#### Visualization:
The project includes a consolidated set of visualizations presented in a **single 3x3 subplot grid** for easy interpretation. Key plots include:
- Attendance vs. Exam Score (Regression Plot)
- Access to Resources (Strip Plot)
- Parental Involvement (Box Plot)
- Family Income (Strip Plot)
- Sleep Hours, Tutoring Sessions, and Hours Studied (Scatter Plots)
- School Type and Gender Analysis (Box Plots)

---

#### Statistical Analysis:
- **ANOVA Tests** to assess the impact of categorical variables like parental involvement, access to resources, and family income.
- **Correlation Metrics** to evaluate relationships between numerical variables.
- **T-tests** to compare exam scores across groups (e.g., private vs. public schools).

---

#### Conclusion:
The analysis provides actionable insights:
1. Encourage high parental involvement to boost performance.
2. Improve resource availability, especially for students with low access.
3. Prioritize attendance as a key metric for better performance.
4. Promote efficient study habits, focusing on hours studied rather than external tutoring or sleep patterns.

---

#### Tools & Technologies:
- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Environment**: Jupyter Notebook

---

#### Files in Repository:
1. `student_performance_analysis.ipynb` – Jupyter Notebook with complete analysis and visualizations.
2. `dataset.csv` – Dataset used for the project.
3. `README.md` – Detailed project description and insights.
4. `plots/` – Folder containing all generated plots in PNG format.

---

#### How to Run:
1. Clone the repository.
2. Install required Python libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook and run all cells to reproduce the analysis.

---

#### Future Work:
- Extend the analysis by incorporating predictive modeling to forecast exam scores based on significant variables.
- Explore additional factors like extracurricular activities or mental health indicators.
- Apply advanced visualization techniques for a more interactive presentation.

This repository is a comprehensive guide for educators, policymakers, and analysts aiming to enhance student academic outcomes.
