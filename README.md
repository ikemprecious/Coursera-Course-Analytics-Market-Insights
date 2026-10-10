# Coursera Course Insights & Performance Analysis

## Project Overview

This project analyses a dataset of Coursera courses to identify patterns in **course popularity, learner engagement, ratings, difficulty levels, and course organisations**.

The analysis explores which courses attract the highest number of learners and investigates whether factors such as course difficulty and ratings are associated with enrolment.

The project demonstrates practical skills in data cleaning, exploratory analysis, statistical analysis, outlier detection, and data visualisation using Python.

## Objectives

- Analyse course popularity based on student enrolment.
- Examine the distribution of courses across difficulty levels.
- Investigate the relationship between course difficulty and enrolment.
- Analyse the relationship between course ratings and enrolment.
- Identify the most popular course categories.
- Identify organisations offering the largest number of courses.
- Detect potential outliers in course enrolment.
- Use statistical analysis and visualisation to identify meaningful patterns.

## Dataset

The dataset contains information about Coursera courses, including:

- Course title
- Course organisation
- Course difficulty
- Course rating
- Number of students enrolled
- Course URL

The dataset was obtained from Kaggle.

## Data Preparation

Several data-cleaning steps were performed before analysis:

- Removed unnecessary index columns.
- Cleaned student enrolment values containing **K/M abbreviations** and converted them into numerical values.
- Standardised relevant categorical variables.
- Reviewed missing and inconsistent values.
- Preserved course URLs for reference and further exploration.
- Prepared variables for statistical analysis and visualisation.

## Analysis

The analysis focused on:

- Course distribution by difficulty level.
- Student enrolment across courses.
- Course ratings.
- Relationship between course difficulty and enrolment.
- Relationship between course ratings and enrolment.
- Most popular courses based on student enrolment.
- Course organisations with the highest number of courses.
- Detection of unusually high enrolment using the **Interquartile Range (IQR) method**.

Python visualisation libraries were used to present patterns and comparisons across the dataset.

## Key Insights

- A small number of courses account for a disproportionately high number of student enrolments, indicating substantial variation in course popularity.
- **Mixed-difficulty courses** had the highest average enrolment among the difficulty categories analysed.
- Course ratings showed **almost no relationship with enrolment**, with a correlation of **0.07**, suggesting that higher ratings alone do not necessarily translate into greater popularity.
- **Machine Learning** courses recorded the highest enrolment in the dataset.
- **University of Pennsylvania** offered the largest number of courses in the dataset.
- Several courses had unusually high enrolment and were identified as potential outliers using the **IQR method**.

## Conclusion

Overall, course ratings alone do not explain differences in course popularity. **Course topic, difficulty level, and course organisation** may also influence learner engagement and enrolment.

The analysis demonstrates how combining descriptive statistics, correlation analysis, outlier detection, and data visualisation can provide deeper insights into online learning platforms and course performance.

## Limitations

- The dataset represents a snapshot of Coursera courses and may not reflect current course popularity.
- Enrolment figures may change over time.
- The analysis identifies relationships and patterns but does not establish causation.
- Other factors, such as course duration, instructor reputation, marketing, and course content, may influence enrolment but were not analysed.
- The dataset may not represent the entire Coursera course catalogue.

## Future Improvements

- Analyse course categories and subject areas in greater detail.
- Investigate whether course ratings vary across different organisations and categories.
- Analyse the relationship between course duration and enrolment.
- Compare organisations based on learner engagement.
- Build an interactive dashboard to explore course performance.
- Develop a predictive model to estimate course enrolment.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
