# Week1-StudentPerformance-EDA

The goal of this task is to perform Exploratory Data Analysis (EDA) on the Students Performance in Exams dataset and uncover patterns in exam scores based on gender, parental education, lunch type, and test preparation course.  


## Dataset  
- Source: [Kaggle – Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  
- Rows: 1,000 students  
- Columns:  
  - Gender  
  - Race/ethnicity  
  - Parental level of education  
  - Lunch type  
  - Test preparation course  
  - Math score  
  - Reading score  
  - Writing score  


## Steps Performed  

1. Data Loading  
   - Imported dataset into pandas DataFrame and previewed first rows.  

2. Data Exploration  
   - Used .info() and .describe() to check structure and distributions.  
   - Reviewed category distributions for gender, parental education, lunch, and test preparation.  

3. Missing Values Check  
   - Confirmed no missing data in any column.  

4. Pattern Analysis  
   - Grouped averages by gender, lunch type, parental education, and test preparation.  

5. Deeper Relationships  
   - Correlations between math, reading, and writing scores.  
   - Cross-tabs for gender × test prep and lunch × parental education.  
   - Created a total_score feature to evaluate overall performance.  

6. Visualizations  
   - Boxplots: math by gender, reading by lunch.  
   - Violin plot: writing by test preparation.  
   - Heatmap: correlation between scores.  
   - Barplot: average total score by parental education.  

## Important Findings  

- Gender: Males score slightly higher in math, while females perform better in reading and writing.  
- Lunch Type: Students with standard lunch consistently outperform those with free/reduced lunch.  
- Parental Education: Higher parental education is associated with better exam performance.  
- Test Preparation: Students who completed the test preparation course scored 5–8 points higher across all subjects.  
- Correlation: Strong positive correlation between math, reading, and writing — high performance in one subject predicts good performance in others.  

##  Tools & Libraries used

- Python  
- pandas  
- matplotlib  
- seaborn  
- Google Colab 

