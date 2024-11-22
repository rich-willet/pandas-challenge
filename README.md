# pandas-challenge

# PyCitySchools Analysis

## Overview

This project analyzes school and standardized test data to help the school district make informed decisions about budgets and priorities. Using **Pandas** and **Python**, the analysis examines district-wide performance trends, school-specific metrics, and relationships between funding and student performance.

The analysis includes:
- District-wide performance metrics
- Performance summaries for each school
- Trends in performance by grade level
- Comparisons of school performance based on spending, size, and type

## Project Files

The project contains the following files:
- **`PyCitySchools_starter.ipynb`**: The main analysis notebook containing all calculations and visualizations.
- **`schools_complete.csv`**: Dataset with information about schools, including budgets and types.
- **`students_complete.csv`**: Dataset with student information, including grades and test scores.

## Key Metrics and Insights

### District Summary
- **Total Schools**: 15
- **Total Students**: 39,170
- **Total Budget**: $24,649,428
- **Average Math Score**: 79.0
- **Average Reading Score**: 81.9
- **% Passing Math**: 75.0%
- **% Passing Reading**: 85.8%
- **% Overall Passing**: 65.0%

### School Summary
Each school was analyzed for:
- School type (Charter vs. District)
- Total students and budget
- Per student spending
- Average math and reading scores
- % Passing rates for math, reading, and overall

### Key Observations:
1. **Charter Schools Outperform District Schools**:
   - Charter schools had higher passing rates in both math and reading compared to district schools, despite lower budgets.
   
2. **Higher Spending Does Not Guarantee Better Performance**:
   - Schools with the highest per-student spending did not have the best passing rates.

### Performance by Grade
Average math and reading scores were broken down by grade level (9th, 10th, 11th, and 12th). No significant trends in performance were observed across grades.

## Performance by Spending Ranges
Schools were categorized into spending ranges per student:
- **Spending Ranges (Per Student)**: `<$585`, `$585-630`, `$630-645`, `$645-680`
- Higher spending ranges showed slightly lower performance.

| Spending Range      | Avg Math Score | Avg Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
|---------------------|----------------|-------------------|----------------|-------------------|-------------------|
| `<$585`             | 83.5          | 83.9             | 93.0%          | 96.0%             | 90.0%             |
| `$585-630`          | 81.0          | 83.0             | 81.0%          | 90.0%             | 73.0%             |

## Performance by School Size
Schools were categorized by size:
- **Small (<1000 students)**: Highest performance across metrics
- **Medium (1000-2000 students)**: Moderate performance
- **Large (2000-5000 students)**: Lowest performance

| School Size         | Avg Math Score | Avg Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
|---------------------|----------------|-------------------|----------------|-------------------|-------------------|
| Small (<1000)       | 83.8          | 84.0             | 93.0%          | 95.0%             | 91.0%             |
| Medium (1000-2000)  | 81.5          | 83.6             | 85.0%          | 92.0%             | 80.0%             |
| Large (2000-5000)   | 78.0          | 80.3             | 67.0%          | 78.0%             | 62.0%             |

## Performance by School Type
Charter schools significantly outperformed district schools across all metrics.

| School Type         | Avg Math Score | Avg Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
|---------------------|----------------|-------------------|----------------|-------------------|-------------------|
| Charter             | 83.4          | 83.9             | 90.0%          | 93.0%             | 88.0%             |
| District            | 77.0          | 80.9             | 67.0%          | 78.0%             | 58.0%             |

## Conclusions
1. **Charter schools outperform district schools despite lower budgets**, suggesting that funding allocation or management may significantly impact performance.
2. **Smaller schools show higher passing rates**, highlighting potential benefits of lower student-to-teacher ratios or more personalized instruction.
3. **Higher spending does not guarantee better outcomes**, indicating that how resources are used may be more important than total funding.

