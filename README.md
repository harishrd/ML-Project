# Student Performance Indicator

This project aims to analyze how student performance on tests is affected by various factors, such as gender, ethnicity, parental level of education, lunch, and test preparation courses.

## Data Source

The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977). It contains 1000 rows and 8 columns.

## Data Cleaning

Before analyzing the data, several checks were performed to ensure its quality:
- Missing values were identified and either filled in or removed.
- Duplicates were removed.
- Data types were verified and corrected where necessary.
- The number of unique values in each column was determined.
- Descriptive statistics of the dataset were computed.
- Various categories present in the categorical columns were identified.

## Exploratory Data Analysis

Several visualizations were created to explore the relationships between the different variables:
- Histograms and box plots were used to visualize the distribution of each variable.
- A heatmap was used to visualize the correlation between the variables.

## Data Preprocessing

Before modeling, the categorical variables were converted to numerical variables using one-hot encoding. The data was then split into training and testing sets.

## Model Training

Several regression models were trained and evaluated:
- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression

The models were evaluated using Mean Squared Error (MSE).

## Model Selection

The model with the lowest MSE was selected as the final model.

## Usage

1. Clone the repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run `python main.py` to train and evaluate the models.
4. Run `python predict.py` to make predictions using the final model.

## Contributors

- Harish (harishrd321@gmail.com)
