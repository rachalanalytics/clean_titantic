# Titanic Data Analysis

This is a data analysis project using the Titanic dataset from the Seaborn library. The goal of this project was to practice data cleaning, exploration, and visualization techniques to prepare a dataset for further analysis. I used this project as a learning exercise to explore how to handle missing values, outliers, duplicates, and inconsistencies in real-world data.

## Key Skills Demonstrated:
- **Data Cleaning**: Handling missing values, duplicates, and inconsistencies.
- **Data Exploration**: Understanding dataset structure, inspecting missing values, and identifying outliers.
- **Visualization**: Using `matplotlib` and `seaborn` to create meaningful plots, such as boxplots for detecting outliers.
- **Imputation**: Filling missing values with appropriate strategies based on available data.
- **Data Transformation**: Grouping and transforming data for analysis.

## Steps:
1. **Loading the Data**:
   - The dataset was loaded using Seaborn's built-in Titanic dataset.

2. **Exploratory Data Analysis (EDA)**:
   - Displayed the first few records and reviewed the structure of the dataset.
   - Checked for missing values and inconsistencies across columns.

3. **Data Cleaning**:
   - Filled missing values in the `age` column using the median value grouped by `sex` and `pclass`.
   - Filled missing values in the `embarked` and `embark_town` columns using the mode (most frequent value).
   - Dropped the `deck` column due to a significant portion of missing data.
   - Removed duplicate rows from the dataset.

4. **Handling Outliers**:
   - Used boxplots to visually inspect outliers in numerical columns such as `fare`.
   - Identified that some passengers had an exceptionally high `fare`, which was retained for analysis after verifying that these were legitimate first-class passengers.

5. **Final Dataset**:
   - After cleaning, the dataset was prepared for further analysis, with a total of 773 entries and 14 columns.

## Libraries Used:
- `pandas`: Data manipulation and cleaning.
- `seaborn`: Data visualization and dataset loading.
- `matplotlib`: Plotting graphs.
- `numpy`: Data manipulation and numerical operations.

## Future Improvements:
- **Modeling**: The next step could involve using machine learning models to predict survival based on the features in the dataset.
- **Advanced Outlier Detection**: Implementing more sophisticated outlier detection techniques.
- **Feature Engineering**: Creating new features to improve model performance.
  
## Notes:
This project was created for practice and learning purposes. It is a foundational step in learning data cleaning and exploratory data analysis (EDA). The code is not fully optimized for production use, but it demonstrates essential skills that are key to data analysis tasks.

---

Feel free to explore the code and analysis! Feel free to open an issue or contribute with improvements.
