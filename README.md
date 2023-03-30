# Student Performance Indicator
## Life cycle of Machine learning Project
### 1) Problem statement
This project understands how the student’s performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.
### 2) Data Collection
Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
The data consists of 8 column and 1000 rows.
### 3) Data Checks to perform
Check Missing values
Check Duplicates
Check data type
Check the number of unique values of each column
Check statistics of data set
Check various categories present in the different categorical column
### 4) Exploratory data analysis
Visualize the distribution of each variable using histograms and boxplots.
Visualize the correlation between variables using a heatmap.
### 5) Data Pre-Processing
Convert categorical variables to numerical variables using one-hot encoding.
Split data into training and testing sets.
### 6) Model Training
Train different models such as Linear Regression, Decision Tree Regression, Random Forest Regression, and Gradient Boosting Regression.
Evaluate each model using Mean Squared Error (MSE).
### 7) Choose best model
Choose the model with the lowest MSE as the final model.
Installation
Clone the repository.
Install the required packages using pip install -r requirements.txt.
Usage
Run python main.py to train and evaluate the models.
Run python predict.py to make predictions using the final model.
