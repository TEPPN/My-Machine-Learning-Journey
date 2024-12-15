Previous [[Type Of Machine Learning]]

Stating problem in machine learning are the first step that are important and crucial in the process of model development. 

## Identify Purpose

We need to understand the objective we want to achieve by project. Without clear objective, we can losing direction  in model development.

### S.M.A.R.T Method
In Business, SMART are the effective way to make sure that the objective are clear, reachable, and relevant to company's strategy. SMART method are the abbreviation of *specific, measurable, achievable, relevant, and time-bound*.
1. Specific
   The objective must be clear so that everyone that involve in the project understand what to achieve. The specific objective must be able to answer: (1)What we want to achieve? (2)Why it's important? (3)Who get involved? (4)When this objective will be achieved?
2. Measurable
   The objective must be measurable so that we can track the progress and know that the objective's target achieved. metric or performance indicator must declare to measure the progress.
3. Achievable
   The objective musts be realistic and achievable with the available resources.
4. Relevant
   The objective must be relevant with the whole business strategy and give significant contribution to company's long term achievement.
5. Time-Bound
   The objective must have the clear deadline to help stay focus and urgency feeling.

## Understand The Available Data
Observe the available data. The data must be enough to help achieve the objective.

1. Inventory Data
   Identifying all the data resource available, either internal or external are the first crucial step in the process of data analyse. Make sure to cover all the data received from company's internal system, like operational databases. By collecting all the relevant data, we make sure that none important information missed that could affect the data accuracy. This process also help in identifying the potential of data's gap and make a strategy to overcome it.
2. Evaluate Data's Quality
   Checking the data's completeness, consistency, accuracy, and relevancy. This step  consist of missing values, duplicated data, incorrect typing, and no sense data. Make sure that the data consistent to the whole dataset, for example the same format for date.
3. Data Exploration 
   Doing data exploration to understand pattern, distribution, and relation between variable. It's done by data visualization, like histogram, scatter plot, and box plot, also analyzing statistic. Data exploration help finding outliers, understand variable distribution, and finding important relation between feature.
4. Feature Choice
   Choosing the most relevant feature for the determined objective. Choosing the correct feature could increase the model performance and reduce complexity. Feature that are not relevant or have few information must be ignored.
5. Cleaning and Transformation Data
   First, fixing problem, like missing values, duplication, and inconsistency by filling the missing value, deleting duplicated data, and standardize the data format. Next, transform data by normalization numeric variable, encoding categorical variable, and merging related feature to prepare data for machine learning algorithm.

## Find The Machine Learning Problem
Finding the type of machine learning problem are important because it can affect the approach that will be use and also algorithm choice. The type of machine learning problem usually categorized by some main type: classification, regression, and clustering. Each problem have its own characteristic and specific objection, that in the end determine the most fit method to implemented.

1. Classification
   In classification, we group data into category that have been determined. Example, if we have data about people's height and want to classified into two category "tall" or "short", we can determine the limit the height for each category. Here are the algorithm we can use:
   - K-Nearest Neighbours (KNN)
   - Decision Tree
   - Random Forests
   - Support Vector Machines (SVM)
   - Logistic Regression
   
    Evaluation Criteria 
   - Accuracy
   - Precision and Recall
   - F1-Score
   - ROC-AUC Score
   
2. Regression
   Regression use to predict continue numeric value. If we want to determine someone's height in centimeter, we can use regression where the model will help us to understand the relation between variable and make body height prediction based on the available data. Here are the algorithm we can use:
   - Linear Regression
   - Polynomial Regression
   - Support Vector Regression (SVR)
   - Random Forest Regression
   - Gradient Boosting Regressor
   
   Evaluation Criteria
   - Mean Squared Error (MSE)
   - Mean Absolute Error (MAE)
   - R-squared ($R^2$)Score
   
3. Clustering
   In Clustering, data grouped by characteristic similarity without label that have been determined. Each cluster represent group with similar height gap. Here are the algorithm we can use:
   - K-Mean Clustering
   - Hierarchical Clustering
   - DBSCAN (Density-Based Spatial Clusteing of Application with Noise)
   - Gaussian Mixture Models
   
   Evaluation Criteria
   - Silhouette Score
   - Davies-Bouldin Index
   - Inertia (for K-Means)

This step make sure that we use the correct technique to get the most accurate and reliable.

Next [[Machine Learning Workflow]]