# SparkMLLibLab
Assessment for Hadoop for Developers Course

College-Admissions Dataset
Zulema Caldwell

Overview
Analyze college admission data to determine admission based on GRE, GPA, and rank using two different MLLib functions--LogisticRegression and KMeans


Steps Completed
1. Initialize spark
2. Read in college admissions dataset from /data/college-admissins/admission-data.csv
3. Create the Training and Test Data set using randomSplit
4. Create Vector for GRE, GPA, and Rank
5. Fit the LogisticRegressin model using the training data
6. Calculate predictions on test dataset
7. Show LR Model accuracy
8. Using WSSSE, fit 2 KMeans clusters using the training data
9. Calculate predictions on test dataset
10. Show WSSSE and silhoutte score
11. Compare the two models
