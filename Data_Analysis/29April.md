# Objective

Explore data distributions and relationships using basic statistical and visual techniques before applying machine learning models.

# Tools Used

- Python (Pandas, Numpy)
- Seaborn, Matplotlib
- SciPy (for statistical tests)

# Dataset

- Synthetic dataset generated using NumPy

- Features: Age, Marks, Study Hours, Sleep Hours, Gender, BuysProduct

# Process

## 1. Univariate Analysis

### Objective: 
- Understand single variable distribution

### Tools: 
- Histogram, Boxplot, Summary statistics (mean, median, std)

### Feature Example: 
- Marks

## 2. Bivariate Analysis

### Objective: 
- Explore relationship between two variables

### Types:

- Numerical vs Numerical: Scatter plot + Pearson correlation (correlation matrix)

- Categorical vs Categorical: Contingency table + Chi-Square test

- Categorical vs Numerical: Boxplot + ANOVA

## 3. Multivariate Analysis

### Objective: 
- Visualize and analyze relationships between multiple variables

### Tools: 
- Pairplot (Seaborn), ANOVA for multiple groups

### Feature Example: 
- Study Hours, Sleep Hours, Age, Marks

### Results

- Found strong positive correlation between Study Hours and Marks

- Chi-Square test showed relationship between Gender and BuysProduct was significant (p < 0.05)

- ANOVA confirmed statistically significant difference in Marks across Grades (A/B/C)