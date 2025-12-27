# Resume–Job Matching Data Analysis

This project explores patterns in resume–job match outcomes to understand which factors influence higher match quality. Instead of focusing on building a predictive model, the goal is to analyze relationships between resume structure, keyword overlap, job length, and predicted match results to uncover data-driven insights.

---

## 📌 Key Questions
- Does resume length correlate with higher match probability?
- Is keyword/skill overlap the strongest factor in match success?
- Do longer job descriptions favor longer or more keyword-rich resumes?
- What resume length ranges (short/medium/long) show the highest match rate?

---

## 📊 Dataset
| File | Description |
|------|-------------|
| `resume_job_matching_dataset.csv` | Cleaned dataset with resume & job features |
| `resume_job_with_predictions.csv` | Contains predicted probabilities used for analysis |

This is **not** a modeling project — model output is used only for insight discovery.

---

## 🛠️ Tools & Libraries
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Tableau / Power BI (dashboard visualization)

---

## 🔍 Analysis Workflow
1. Load & inspect dataset
2. Explore relationships (correlation, grouping, distributions)
3. Visualize patterns with scatter plots, bar charts, and heatmaps
4. Compare resume & job text structure patterns
5. Identify insights for potential hiring or applicant-screening decisions

---

## 📈 Key Insights (Example Summary)
- Resumes between **25–35 lines** show the highest match consistency.
- Higher keyword overlap strongly correlates with better predicted match outcomes.
- Very short resumes (<15 lines) rarely score well.
- Job descriptions longer than 30 lines show clearer structural patterns.

Note: Logistic Regression is used only as a baseline to generate match probability scores. 
The objective of this project is analysis and insight, not model deployment.
