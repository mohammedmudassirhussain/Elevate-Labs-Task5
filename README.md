# Elevate-Labs-Task5
Titanic Dataset - Exploratory Data Analysis (EDA)
📊 Task 5: Data Analyst Internship
🎯 Objective
Extract insights from the Titanic dataset using visual and statistical exploration techniques.
🛠 Tools Used

Python 3.x
Pandas - Data manipulation and analysis
Matplotlib - Data visualization
Seaborn - Statistical data visualization
NumPy - Numerical computing
Jupyter Notebook - Interactive computing environment

📁 Dataset

Source: Titanic - Machine Learning from Disaster | Kaggle
Files Used:

train.csv - Training dataset (891 passengers)
test.csv - Test dataset (418 passengers)



📋 Analysis Performed
1. Data Loading & Inspection

Loaded train and test datasets
Examined data structure, types, and dimensions
Generated statistical summaries using .describe() and .info()

2. Missing Values Analysis

Identified missing values in Age (19.9%), Cabin (77.1%), and Embarked (0.2%)
Visualized missing data patterns
Analyzed impact on overall dataset

3. Univariate Analysis

Survival rate distribution (38.4% survived)
Age distribution (histogram)
Fare distribution (histogram)
Passenger class, gender, and embarkation port distributions

4. Bivariate Analysis

Survival by Gender: Females had 74% survival rate vs 19% for males
Survival by Class: 1st class (63%), 2nd class (47%), 3rd class (24%)
Survival by Age: Children had higher survival rates
Survival by Fare: Higher fares correlated with better survival

5. Multivariate Analysis

Combined analysis of Class, Gender, and Survival
Age groups vs Survival patterns
Family size impact on survival

6. Correlation Analysis

Generated correlation matrix
Created heatmap visualization
Pairplot for key variables
Key findings:

Negative correlation: Pclass vs Survival (-0.34)
Positive correlation: Fare vs Survival (+0.26)



7. Outlier Detection

Used IQR method for outlier detection
Identified outliers in Age, Fare, SibSp, and Parch
Visualized using boxplots

8. Feature Engineering

Created Family_Size feature (SibSp + Parch + 1)
Created Is_Alone binary feature
Analyzed survival patterns by family size

📊 Key Insights

Gender was the strongest survival predictor

74% of females survived vs only 19% of males
"Women and children first" policy was clearly followed


Passenger Class significantly impacted survival

1st class: 63% survival rate
2nd class: 47% survival rate
3rd class: 24% survival rate


Age played a role

Children (<18 years) had higher survival chances
Average age: 29.7 years


Family size mattered

Small families (2-4 members) had better survival rates
Solo travelers and very large families had lower survival


Fare correlation

Higher ticket prices correlated with survival
First-class tickets ranged significantly in price



📈 Visualizations Created

Pie charts for survival distribution
Histograms for Age and Fare distributions
Count plots for categorical variables
Box plots for outlier detection
Heatmap for correlation matrix
Pairplot for multivariate relationships
Grouped bar charts for survival by categories

🔍 Statistical Methods Used

.describe() - Descriptive statistics
.info() - Dataset information
.value_counts() - Frequency distributions
.corr() - Correlation analysis
.groupby() - Aggregated analysis
IQR method - Outlier detection

