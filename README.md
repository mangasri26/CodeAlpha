You can add the following README.md to your GitHub repository:
Student Performance Analysis using Python
Project Overview
This project performs Exploratory Data Analysis (EDA) on a student performance dataset using Python. The analysis helps understand student academic performance, attendance patterns, grades, and overall results through statistical summaries and visualizations.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Dataset Features
The dataset contains the following columns:
Student_ID
Name
Gender
Age
Math Marks
Science Marks
English Marks
Attendance
Tasks Performed
1. Data Loading
Imported required libraries.
Created a Pandas DataFrame from the dataset.
2. Data Exploration
Viewed dataset using head()
Checked dataset shape
Examined data types and missing values using info()
Generated statistical summaries using describe()
3. Feature Engineering
Calculated Total Marks
Calculated Average Marks
Created Result category (Excellent/Good)
Assigned Grades based on average scores
4. Data Cleaning
Identified missing values
Replaced missing values with column means
5. Data Analysis
Subject-wise average marks
Top-performing students
Lowest-performing students
Gender distribution
Attendance analysis
6. Data Visualization
The following visualizations were created:
Gender Distribution (Count Plot)
Age Distribution (Histogram)
Attendance vs Total Marks (Scatter Plot)
Correlation Heatmap
Math Marks Box Plot
Science Marks Box Plot
English Marks Box Plot
Grade Distribution Plot
Key Insights
Calculated overall student performance.
Identified top and low-performing students.
Analyzed attendance impact on academic scores.
Examined subject-wise performance trends.
Visualized relationships between different academic factors.
Project Structure
Plain text
Student-Performance-Analysis/
│
├── mangasreeja.ipynb
├── README.md
└── dataset.csv (optional)
How to Run
Clone the repository:
Bash
git clone https://github.com/mangasri26/student-performance-analysis.git
Install required libraries:
Bash
pip install pandas numpy matplotlib seaborn
Open Jupyter Notebook:
Bash
jupyter notebook
Run mangasreeja.ipynb.
Learning Outcomes
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Data Visualization
Statistical Analysis using Python
Author
Manga sreeja
Connect with Me
GitHub: https://github.com/mangasri26/CodeAlpha.git
LinkedIn: https://www.linkedin.com/in/manga-sreeja-147690340?utm_source=share_via&utm_content=profile&utm_medium=member_android
⭐ If you found this project useful, don't forget to star the repository.
