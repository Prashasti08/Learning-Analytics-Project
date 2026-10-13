# Learning Analytics Project: Student Engagement & Academic Outcomes

**Python | Tableau | Statistical Analysis | Longitudinal Analysis | A/B Test Design**

Analyzed **32,593 student-course records and 10.6M+ LMS interactions** to examine student engagement, academic performance, and opportunities for early learner-support interventions.

## Research Question

How does online learning engagement relate to academic outcomes, and when do disengagement patterns emerge?

## Business Purpose

Identify engagement patterns to inform **early interventions, learner retention, and data-driven learning strategies**.

## Methodology

- **Data Preparation:** Analyzed student records, LMS interactions, assessment scores, and course outcomes using Python.
- **Statistical Analysis:** Applied descriptive statistics, one-way ANOVA, and Pearson correlation to examine engagement and performance.
- **Longitudinal Analysis:** Compared weekly engagement patterns across Distinction, Pass, Fail, and Withdrawn students.
- **Experimental Design:** Proposed an A/B test to evaluate proactive learner-support messages.

## Findings

- **Engagement Differences:** Distinction students averaged 2,667 LMS clicks versus 445 for Withdrawn students; differences across outcome groups were statistically significant (p < .001).
- **Academic Performance:** Engagement was positively correlated with assessment scores (r = 0.293, p < .001).
- **Engagement Trends:** Students who failed or withdrew generally showed lower weekly LMS engagement than those who passed or earned distinctions.

## Key Insights and Recommendations

- **Early Intervention:** Identify students with low LMS engagement for targeted learning support.
- **Personalized Support:** Pilot reminders, study-planning prompts, and relevant course resources.
- **Impact Evaluation:** Use randomized A/B testing to assess subsequent engagement and assessment completion before scaling interventions.

## Data Source

[Open University Learning Analytics Dataset (OULAD)](https://analyse.kmi.open.ac.uk/open_dataset)

Real-world, anonymized educational data covering **7 courses, 22 course presentations, 32,593 student-course records, and 10.6M+ LMS interactions**.

## Code

- **Python (Pandas, SciPy, Matplotlib):** Data preparation, descriptive statistics, ANOVA, correlation analysis, and longitudinal engagement analysis.
- **[View Python Analysis — Jupyter Notebook](https://github.com/Prashasti08/oulad-learning-analytics/blob/main/oulad_learning_analytics.ipynb)**

## Data Visualizations and Dashboard

- **Tableau:** Interactive dashboard comparing LMS engagement, academic performance, and weekly engagement trends across course outcomes.
- **[View Interactive Tableau Dashboard](https://public.tableau.com/views/OULADLearningAnalytics/Dashboard1)**

## Limitations

- Observational findings establish associations, not causation.
- LMS clicks measure activity, not learning quality.
- The A/B test is proposed, not implemented.
