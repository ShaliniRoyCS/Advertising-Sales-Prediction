# Advertising-Sales-Prediction
This project leverages simple linear regression to predict sales figures based on advertising expenditure across multiple media channels. The dataset comprises three key advertising mediums: TV, Newspaper, and Radio, along with the target variable, `Sales`.

## Dataset Description

The dataset used in this project contains the following variables:

- **TV**: Advertising budget spent on TV (in thousands of dollars).
- **Radio**: Advertising budget spent on Radio (in thousands of dollars).
- **Newspaper**: Advertising budget spent on Newspaper (in thousands of dollars).
- **Sales**: Units sold (in thousands).


## Project Structure

The project is structured into the following phases:

### 1. Data Exploration and Cleaning
- Loading and inspecting the dataset.
- Checking for missing values and ensuring data integrity.
- Performing descriptive statistical analysis.
- Identifying and visualizing potential outliers using box plots.

### 2. Exploratory Data Analysis (EDA)
- Analyzing relationships between variables through pair plots.
- Visualizing the correlation matrix using a heatmap to identify potential multicollinearity.

### 3. Model Development
- Data splitting into training and testing sets (70%-30% split).
- Building a linear regression model using the `statsmodels` library.
- Assessing model performance through statistical summaries.

### 4. Model Evaluation
- Plotting the regression line over training and test data to assess the fit.
- Residual analysis to verify the normality of errors and check for heteroscedasticity.
- Computing performance metrics, including R-squared and Mean Squared Error (MSE).

## Libraries and Tools

The following Python libraries are utilized in this project:
- **numpy**: Efficient numerical computations.
- **pandas**: Data manipulation and analysis.
- **matplotlib** and **seaborn**: Data visualization.
- **scikit-learn**: Train-test split and model evaluation.
- **statsmodels**: Statistical modeling and regression analysis.

## Key Results and Insights

- The linear regression model predicts `Sales` based on the `TV` advertising budget.
- The model's performance is quantified through:
  - **R-squared:** Represents the proportion of variance explained by the model.
  - **Mean Squared Error (MSE):** Measures the average of the squares of the errors.

### Visual Insights:
- Box plots depict the distribution of advertising budgets and highlight the absence of significant outliers.
- Pair plots illustrate the relationship between the variables.
- Scatter plots exhibit the linear relationship between TV budget and Sales.
- Heatmap visualization reveals the correlation between the variables.
- Residual plots validate the normal distribution of error terms.

## Future Enhancements

The current model can be further refined by:
- Incorporating additional variables to enhance prediction accuracy.
- Exploring advanced regression techniques, including Ridge and Lasso.
- Implementing cross-validation for better generalizability.
