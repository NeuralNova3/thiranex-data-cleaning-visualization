# Data Cleaning and Visualization Project

## Internship
Thiranex Internship Program

## Project Overview
This project demonstrates a basic data-analysis workflow using Python. A synthetic student performance dataset was created for educational purposes.

## Tools and Libraries
- Python
- Pandas
- Matplotlib
- Google Colab

## Dataset
The dataset contains 15 sample student records with study hours, attendance, and exam scores. Missing values, a duplicate record, and an unusually high study-hours value were deliberately included for practice.

**Note:** This is synthetic sample data, not real student data.

## Data Cleaning
1. Inspected dataset dimensions, column types, missing values, duplicates, and summary statistics.
2. Filled missing numerical values using each column's median.
3. Removed one duplicate record.
4. Detected a potential outlier using the Interquartile Range (IQR) method.
5. Excluded the flagged record from the final analysis dataset for this demonstration.

## Visualizations
- Box plot of study hours.
- Scatter plot of study hours versus exam scores.
- Bar chart of average exam scores by attendance group.
- Histogram of exam-score distribution.

## Results
- Original records: 15
- Duplicate rows removed: 1
- Missing numerical values handled: 3
- Potential outlier flagged: 1
- Records in final analysis: 13

## Limitations
This is a small synthetic dataset created for learning. The results should not be treated as conclusions about real students. In a real project, potential outliers should be investigated before exclusion.

## Conclusion
This project demonstrates data inspection, cleaning, outlier detection, visualization, and exporting a cleaned CSV using Python libraries.
