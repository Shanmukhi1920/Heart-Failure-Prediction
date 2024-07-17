

# Overview
This project analyzes clinical data to predict heart disease risk. It demonstrates the application of data science techniques in healthcare, potentially aiding early diagnosis and prevention strategies.

# Repository Contents
- `heart.csv`: Contains the dataset used for the analysis.
- `heart.Rmd`: An R Markdown document which includes the analysis process, covering data loading, preprocessing, and machine learning models for prediction.
  
# Analysis Workflow
## Data Gathering and Integration
- Dataset: Heart Failure Prediction Dataset from Kaggle
- Loaded and examined the dataset structure

## Data Exploration
- Performed summary statistics
- Created visualizations including histograms, bar plots, and scatter plots
- Analyzed relationships between variables

## Data Cleaning
- Checked for null values
- Removed outliers using the IQR method
- Converted categorical variables to numeric

## Data Preprocessing
- Created bins for cholesterol levels
- Normalized data using standardization
- Created dummy variables for categorical features

## Clustering
- Used K-means clustering
- Determined optimal number of clusters
- Visualized clusters using PCA

## Classification
- Implemented two classifiers:
  1. Support Vector Machine (SVM)
  2. K-Nearest Neighbors (KNN)
- Used grid search for hyperparameter tuning

## Evaluation
- Compared SVM and KNN performance
- Created confusion matrices
- Calculated precision and recall
- Plotted ROC curve

## How to Run
1. Ensure R and the necessary packages are installed.
2. Set the working directory to the location of the dataset and R Markdown file.
3. Run the `heart.Rmd` file in RStudio or a similar environment to view the analysis.

# Results

- SVM has training accuracy of 85.7% with C value tuned to 10e-03 while Kknn has 86.6% with kmax=8, rectangle kernel and p set to Manhattan distance.
- SVM outperformed KNN with an accuracy of 85.5% on the test set.
- ROC curve analysis showed an AUC of 86%.
