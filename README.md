
# Heart Disease Prediction Project

## Overview
This project analyzes clinical data to predict heart disease risk. It demonstrates the application of data science techniques in healthcare, potentially aiding early diagnosis and prevention strategies.

## Repository Contents
- `heart.csv`: Contains the dataset used for the analysis.
- `heart.Rmd`: An R Markdown document authored by Shanmukhi, dated 2022-11-09. It includes the analysis process, covering data loading, preprocessing, and machine learning models for prediction.
  
## Analysis Workflow
The `heart.Rmd` file includes sections on:
- **Data Gathering and Integration**: Importing the Heart Failure Prediction Dataset from Kaggle.
- **Loading Required Libraries**: Including data manipulation, visualization, and machine learning libraries.
- **Detailed Analysis**: Steps for preprocessing, exploratory data analysis, and model building.

## How to Run
1. Ensure R and the necessary packages are installed.
2. Set the working directory to the location of the dataset and R Markdown file.
3. Run the `heart.Rmd` file in RStudio or a similar environment to view the analysis.

## Results
1. The dataset contains 12 Columns in which 5 are categorical and 7 are integer/numerical.

2. Among the 918 observations 508 people are prone to heart diseases among which only 50 are women which shows that men are more prone to heart diseases.

3. Nearly 65% people have Fasting Blood Sugar of value indicated '0' which means Blood Sugar is less than 120 mg/dl.

4. 54% people suffer from Asymptomatic type of Chest Pain among which 84% people are Males , 22% have Non-Anginal Pain, 18% have Atypical Angina Pain and rest 6% have Typical Angina Pain.

5. Among the 508 heart disease people 77% have Asymptomatic chest Pain.
 
6. On an Average Females tend to have high levels of Cholesterol and Max Heart rate thn compared to Males.

7. Total 690 observation in the data lie within 3 standard deviations.

8. K means clustering Algorithm produces 3 clusters of sample sizes 109,227,354.

9. Cluster 3 has mean values of -0.09751309 for Cholesterol , -0.4221635	for Resting Blood Sugar, 0.5 for Max Heart rate and -0.67 for Exercise Angina.

10. SVM has training accuracy of 85.7% with C value tuned to 10e-03 while Kknn has 86.6% with kmax=8, rectangle kernel and p set to Manhattan distance.

11. Testing accuracy of svm is 85% and False positives are only 4.

12. The model has a precision of 79.2% and recall of 93.8%.

13. Area under ROC Curve is 86.3%.
