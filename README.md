 # Week1-StudentPerformance-EDA
 The Project Contains:
 
   1. Load the Dataset
                > We begin by importing the required pandas library and loading the dataset using pd.read_csv(). The df.head() function is used to preview the first few rows and confirm that the data has loaded correctly.
   2. Explore the Dataset 
                > We use df.info() to check the structure of the dataset, including data types and non-null values. The df.describe() function gives us descriptive statistics such as mean, min, and max for the numerica
   3. Check for Missing Values
                > Before analysis, it’s important to validate that the dataset is clean. We use df.isnull().sum() to ensure there are no missing or null values.
   4. Analyze Score Patterns
                > We use groupby() along with mean() to calculate average scores across different categories:

                     > Gender
                     > Parental level of education
                     > Lunch type
                     > Test preparation course
      
   5. Data Visualization
                > We use the seaborn and matplotlib.pyplot libraries to create plots that visually represent the patterns in the data. These include:
      
                     > Boxplot for math scores by gender
                     > Barplot for reading scores by parental education level
                     > Boxplot for writing scores by lunch type
                     > Boxplot for math scores based on test preparation
      
  6. Summarize Key Insights
                > Based on the analysis, we can draw the following insights:

                     > Test Preparation Helps: Students who completed a test preparation course scored significantly higher in all subjects.
                     > Gender Differences: Female students tend to perform better in reading and writing, while male students slightly outperform in math.
                     > Parental Education Influence: Higher parental education levels correlate with better student performance.
                     > Lunch Type Matters: Students with standard lunch scored better than those with free/reduced lunch.
                     > Reading & Writing are Linked: Reading and writing scores are highly correlated.

