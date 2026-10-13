# Learning Analytics

Learning Analytics case study examining how students’ online learning engagement relates to course outcomes and assessment performance using the Open University Learning Analytics Dataset (OULAD).

## Research Question

How does students’ online learning engagement relate to course outcomes, and when do disengagement patterns emerge among students who fail or withdraw?

## Dataset

Open University Learning Analytics Dataset (OULAD), containing anonymized student demographics, course outcomes, assessments, registrations, and Virtual Learning Environment (VLE) interaction data.

- 32,593 student-course records
- 10.6M+ VLE interaction records
- 7 courses
- 22 course presentations

## Tools & Methods

**Tools:** Python · Pandas · SciPy · Matplotlib · Tableau

**Methods:** Learning Analytics · Descriptive Statistics · One-Way ANOVA · Pearson Correlation · Longitudinal Engagement Analysis · A/B Test Design

## Analysis

### 1. Engagement by Course Outcome

Average total LMS clicks differed substantially by final outcome:

| Outcome | Average LMS Clicks |
|---|---:|
| Distinction | 2,666.76 |
| Pass | 1,922.28 |
| Fail | 688.36 |
| Withdrawn | 444.82 |

A one-way ANOVA showed a statistically significant difference in engagement across outcome groups (**F = 2526.06, p < .001**).

### 2. Engagement & Assessment Performance

LMS engagement had a modest positive relationship with average assessment performance:

**Pearson r = .293, p < .001**

Students with higher LMS activity tended to have higher average assessment scores, although this relationship should not be interpreted as causal.

### 3. Engagement Over Time

Weekly engagement trajectories showed that students receiving **Distinction** and **Pass** outcomes generally maintained higher LMS activity than students who **Failed** or **Withdrew**.

Fail and Withdrawn students showed broadly similar weekly engagement patterns, suggesting that low engagement may provide a useful signal for learner-support opportunities.

## Tableau Dashboard

An interactive Tableau dashboard explores:

- LMS engagement by course outcome
- Assessment performance by course outcome
- Weekly engagement trajectories
- Course-level filtering

**Tableau Dashboard:** https://public.tableau.com/views/OULADLearningAnalytics/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Learner-Support Intervention

Based on the observed engagement patterns, a potential intervention is an **early engagement support message** for students showing low LMS activity during the early course period.

The message could include:

- upcoming learning activity reminders
- a short study-planning prompt
- links to relevant course resources and support

Because the analysis is observational, this intervention is proposed as a hypothesis to test rather than a proven solution.

## A/B Test Design

**Hypothesis:** A proactive support message will improve subsequent engagement among students showing low early-course LMS activity.

**Treatment:** Early engagement support message  
**Control:** Standard course experience  
**Primary outcome:** LMS engagement during the following two weeks  
**Secondary outcome:** Next assessment submission/completion

Eligible low-engagement students would be randomly assigned to treatment or control groups and their subsequent outcomes compared.

## Key Takeaways

- LMS engagement differed significantly across course outcomes.
- Higher engagement was associated with higher assessment performance.
- Pass and Distinction students generally maintained higher weekly engagement than Fail and Withdrawn students.
- Engagement patterns can inform testable learner-support strategies, but the observational analysis does not establish causality.

## Limitations

- LMS clicks are a behavioral proxy for engagement and do not capture the quality of learning.
- Weekly averages represent students with recorded VLE activity during each week.
- Average assessment score is an unweighted mean of recorded assessment scores.
- The analysis identifies associations, not causal relationships.

## Skills Demonstrated

Learning Analytics · Learning Science · Python · Tableau · LMS/VLE Analytics · Statistical Analysis · Learner Engagement · Experimental Design · A/B Testing
