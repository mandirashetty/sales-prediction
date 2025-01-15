# Sales Prediction using Python

This project involves building a Sales Prediction Model using Python and Linear Regression. The dataset used is the Advertising.csv file, containing data on advertising spending across different mediums and their effect on sales.

## Project Workflow

**1. Importing Libraries**
The following libraries were used:
  - pandas for data manipulation
  - matplotlib.pyplot and seaborn for data visualization
  - sklearn for model building and evaluation

**2. Loading the Dataset**
  - The dataset Advertising.csv is loaded using pandas.
  - An unwanted column Unnamed: 0 was removed.
  - Checked for null values and basic dataset statistics.

**3. Data Visualization**
  - Pair Plots were created for feature relationships.
  - Heatmap to display correlation between features.

**4. Data Splitting**
  - Features: TV, Radio, Newspaper
  - Target Variable: Sales
  - Split into training (80%) and testing (20%) sets using train_test_split.

**5. Linear Regression Model**
  - A Linear Regression model was trained using the training data.
  - Model performance was evaluated using:
    - Mean Squared Error (MSE)
    - R-squared (R²)

**6. Visualization of Results**
- A scatter plot was created comparing actual sales and predicted sales.

**7. Test Data Prediction**
Sample test data was used to predict sales values.

**Setup Instructions**

- Install required libraries:
pip install pandas matplotlib seaborn scikit-learn
- Run the Jupyter Notebook containing the code.
- Ensure the dataset Advertising.csv is present in the same directory.

**Results**
- MSE and R-squared values were used to evaluate the model's performance.
- The model successfully predicted sales based on the advertising expenditure.

**Conclusion**
- This project enhanced the understanding of:
- Data preprocessing and visualization
- Building and evaluating a Linear Regression model
- Model performance metrics
