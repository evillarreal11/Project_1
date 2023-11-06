# Project_1
Project 1
Jessica References:
High Blood Pressure Symptoms and Causes. 2021, May 18. National Center for Chronic Disease Prevention and Health Promotion , Division for Heart Disease and Stroke Prevention. Centers for Disease Control and Prevention. https://www.cdc.gov/bloodpressure/about.htm#:~:text=Blood%20pressure%20is%20measured%20using,your%20heart%20rests%20between%20beats.

# Sleep Health vs. Occupation (Elisabeth Villarreal):

Dataset used: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset 

Occupation: The occupation or profession of the person.

Quality of Sleep (scale: 1-10): A subjective rating of the quality of sleep, ranging from 1 to 10.

Stress Level (scale: 1-10): A subjective rating of the stress level experienced by the person, ranging from 1 to 10.


# Test Hypothesis

Null Hypothesis (H0): A person’s occupation does not affect their sleep health.

Alternative Hypothesis (Ha): Sleep health is affected by occupations that are associated with higher stress levels.


# Visualizations:

- occupation_piechart.png
- occupation_sleep_stress_corr.png

# Analysis:

Sleep quality and occupation stress have a negative correlation (r-value = -0.86). The higher the occupation stress, the lower the sleep quality.

The p-value is less than 0.05 (0.004). Therefore, sleep quality and occupation stress are statistically significant and we can reject the null hypothesis.


**Jessica Analysis**: 

**Objective**: **Analysis of trends/correlations between health factors and sleep disorders**. 

**Question**: Does lack of sleep cause certain health problems in patients with diagnosed sleep disorders versus patients without sleep disorders?

**Null Hypothesis**: There is no significant relationship between health factors (Blood pressure, Heart rate, BMI) and patients with sleep disorders. No difference between these factors between patients with a disorder and patients without. 

**Alternative Hypothesis**: There is significant cause and effect between health factors (Blood pressure, Heart rate, BMI) and patients with sleep disorders. 

**Analysis**:

  T-testing results between the following groupings on disorders:

  Control group - patients without sleep disorders Apnea group - patients with apnea sleep disorder Insomnia group - patients with insomnia sleep disorder

  The following results show statistical significance:

  Systolic blood pressure, diastolic blood pressure, and heart rate in patients with Apnea sleep disorder

  Sleep duration, quality of sleep, systolic and diastolic blood pressure in patients with Insomnia sleep disorder

  Therefore, we can reject the null hypothethis that certain health factors are not related and/or symptoms of sleep disorders, specifically Insomnia and Sleep Apnea.

  **Findings from scatterplots:**

  The diastolic and systolic blood pressures show a similar trend of increasing alongside heartrate, signaling that there is a relationship between increased blood pressure     when the heart is actively pumping (systolic) and when the pressure between pumps (diastolic) increases.

  There is also an increase in Heart rate with less sleep duration, which is a symptom of Insomnia, and a decrease in reported quality of sleep associated with higher heart     rates, a symptom of Sleep Apnea.

  Normal control group with no reported sleep disorders has the highest duration and quality of sleep patterns, with overall lower systolic and diastolic blood pressures.



