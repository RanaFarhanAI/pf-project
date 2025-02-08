 # What is accident:

 # Ans:
           An accident is an unexpected and unplanned event that causes harm, damage, or loss. It can occur in various situations, such as on the road, at work, at home, or in other environments. Accidents can result from human error, mechanical failure, environmental factors, or a combination of these.
# Causes of Accidents:
        1:    Human error (carelessness, fatigue, distraction)
        2:    Poor environmental conditions (bad weather, slippery floors)
        3:    Mechanical failure (brake failure, structural collapse)
        4:    Violating safety rules or guidelines
        5:    Natural disasters

# step 1: Import labraries :

      pandas


# step 2: Analyzing the data

 Load the dataset into a pandas dataframe.
 <!-- using  head  function  -->  
              It display the fist 5 rows of the dataset.
 <!-- Using tail function --> 
            It display the last 5 rows of the dataset.
<!-- Using sample function -->
            It display the random 1 rows of the dataset.
<!-- using the rename() function -->
            Changing the columns name.
<!-- Using the describe() function. -->
            Quick overview of the your dataset
<!-- using the info() function -->
            Detailed the summary of your dataset

# step 3: Element slicing using the loc and iloc

<!-- using the single element slicing loc -->
df.loc[0,'age']
<!-- using the multipale  element slicing iloc -->
df.iloc[1,4]

# step 4: Finding the mean , median and mode.

<!-- using the mean function  -->
df.['age'].mean()
<!-- using the median function  -->
df.['age'].median()
<!-- using the mode function  -->
df.['age'].mode()

# step 5: Data cleaning .

<!-- Drop rows using missing values  -->
df.dropna(inplace= True)

<!-- finding the rows with missing values -->
df.isnull().sum()
 
 <!-- fill the rows using the fillna() -->
fillna(values, inplace=True)

# Data vasualization
 Using  the graph for data representation.

 # Conclusion.
            They often result from human error, environmental conditions, or mechanical failures. However, many accidents can be prevented by following safety guidelines, being aware of potential risks, and using protective measures. By promoting safety awareness and responsible behavior, we can reduce the occurrence of accidents and minimize their impact on lives and property.


