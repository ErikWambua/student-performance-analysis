# Student Performance Analysis

This project analyzes student performance data using Python, Pandas, and Matplotlib.

## Dataset

The dataset used is the Student Performance dataset from the UCI Machine Learning Repository (ID: 320).

## Project Structure

- `src/student_performance_analysis.py`: Main analysis script
- `notebooks/student_analysis.ipynb`: Jupyter notebook version of the analysis
- `requirements.txt`: Python dependencies
- `data/`: Directory for datasets (not included in repo due to size)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/student-performance-analysis.git
   cd student-performance-analysis

2. Install the required packages:
  ```bash
pip install -r requirements.txt
```
## Usage

Run the analysis script:
```bash
python src/student_performance_analysis.py
```
## Dependencies

The project requires the following Python packages:

1. pandas
2. matplotlib
3. seaborn
4. numpy
4. ucimlrepo

All dependencies are listed in the requirements.txt file.

## Analysis Overview

The analysis includes:
1. Data Loading and Exploration: Loading the dataset, checking for missing values, and understanding the data structure
2. Basic Data Analysis: Computing statistics, grouping by categories, and identifying patterns
3. Data Visualization: Creating various plots including:
4. Line charts showing grade trends by age
5. Bar charts comparing performance by school
6. Histograms of grade distributions
7. Scatter plots examining relationships between variables
8. Box plots analyzing performance by different factors

## Key Findings

The analysis revealed several interesting patterns:
1. Students from GP school generally perform better than those from MS school
2. Female students have slightly higher average grades than male students
3. Internet access is associated with higher academic performance
4. There is a weak positive correlation between study time and final grade
5. Final grades tend to decrease slightly as students get older
6. Parental occupation in education or health correlates with better student performance

## Visualizations

The project generates multiple visualizations to illustrate these findings, including:
1.  Average Final Grade by Age
2.  Average Final Grade by School
3.  Distribution of Final Grades
4.  Study Time vs Final Grade
5.  Final Grade Distribution by School and Internet Access
6.  Average Final Grade by Parental Occupation

## Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating a feature branch
3. Making your changes
4. Submitting a pull request
