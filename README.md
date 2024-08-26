# 📊 Student Mental Health Analysis

## Overview

This project aims to explore the mental health landscape among students by analyzing a dataset that encompasses various aspects of student life, including demographic details, academic information, lifestyle factors, and mental health indicators. The insights gained from this analysis can help in understanding the factors influencing student well-being and guiding policies to improve the academic environment.

Dataset Used: https://www.kaggle.com/datasets/abdullahashfaqvirk/student-mental-health-survey/data

## Table of Contents

- [Dataset Description](#dataset-description)
- [Project Goal](#project-goal)
- [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
- [Key Insights](#key-insights)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Results](#results)
- [Conclusion](#conclusion)
  
## Dataset Description

The dataset used for this analysis covers a range of factors affecting student mental health, including:

- **Demographic Details:** Gender, age, and university.
- **Academic Details:** Degree level, major, academic year, and current CGPA.
- **Residential Status:** Whether the student is living on-campus or off-campus.
- **Lifestyle Factors:** Frequency of sports engagement and average sleep hours per night.
- **Satisfaction Metrics:** Student's satisfaction with their field of study and perception of academic workload.
- **Psychosocial Factors:** Experiences with discrimination, harassment, or bullying.
- **Mental Health Indicators:** Frequency of depression, anxiety, isolation, and insecurity about the future.
- **Stress Relief Activities:** Common activities students engage in to relieve stress.

### Project Goal

The primary goal of this project is to analyze the mental health landscape among students, identifying key factors that influence their well-being and academic performance. By exploring various demographic, academic, and lifestyle attributes, the project aims to uncover patterns and correlations that can inform universities and policymakers on how to better support students. This analysis seeks to provide actionable insights that will help in developing targeted interventions and creating a more supportive educational environment that promotes both academic success and mental health.

## Data Cleaning & Preprocessing

The following steps were undertaken to prepare the data for analysis:

1. **Handling Missing Values:** Missing values were identified and managed appropriately, either by imputation or removal.
2. **Data Transformation:** Timestamp data was split into separate date and time columns for more granular analysis.
3. **Encoding Categorical Variables:** Categorical data, such as stress relief activities, was encoded using one-hot encoding for numerical analysis.
4. **Normalization:** CGPA values were normalized to bring them to a common scale.

## Key Insights

- **Universities Represented:** The dataset includes students from multiple universities, providing a diverse perspective on student mental health.
- **CGPA and Mental Health Correlation:** A negative correlation was observed between CGPA and mental health indicators, suggesting that higher academic performance is associated with better mental health.
- **Impact of Academic Pressure:** Increased academic workload was linked to higher levels of stress, anxiety, and depression among students.
- **Popular Stress Relief Activities:** Activities such as exercise, socializing with friends, and hobbies were commonly used by students to manage stress.
- **Differences by Degree Level:** Postgraduate students showed higher stress and anxiety levels compared to undergraduate students.
- **Differences by Major:** Students in certain majors reported higher mental health issues, indicating a need for tailored mental health support.

## Tools and Technologies Used

- **Python**: Pandas
- **VS Code**: For code development and analysis

## Results

- Comprehensive analysis of mental health indicators across various student demographics.
- Identification of key factors influencing student mental health, such as academic pressure, discrimination, and sleep.
- Recommendations for educational institutions to enhance student support systems based on findings.

## Conclusion

This analysis provides valuable insights into the mental health challenges faced by students. By understanding the factors contributing to mental health issues, educational institutions can take proactive steps to support student well-being and foster a healthier academic environment.
