**SpendingHabitsUnveiled**

**Project Overview**

This project, **SpendingHabitsUnveiled**, is a data science project aimed at analyzing individuals' spending habits based on various demographic and lifestyle factors. The dataset includes attributes such as age, hobbies, number of countries visited, monthly stipend, and more.

**Dataset**

The dataset used in this project is **DataSet_Project.csv**, which contains multiple features related to individuals' spending behaviors. The dataset undergoes extensive preprocessing to clean and transform it for analysis.

**Installation and Dependencies**

Before running the script, ensure that the required libraries are installed:

pip install pandas numpy word2number

**Data Preprocessing**

The script performs the following data preprocessing steps:

1. **Column Selection:** Only relevant columns are retained for analysis.
2. **Data Cleaning:**
    - Removing unwanted characters from numerical columns.
    - Handling missing values by replacing them with the mode.
    - Converting words to numerical values using the word2number library.
    - Extracting only alphabetic values where required.
3. **Feature Engineering:**
    - Converting written numbers to numerical format.
    - Standardizing categorical values.
    - Counting the number of countries visited using a predefined country list.

**Key Functions**

- keep_digi(col): Retains only numerical digits in a column.
- convert_nan(col): Converts blank values to NaN.
- keep_alpha(col): Extracts only alphabetical characters from a column.
- fill_missing_mode(col): Fills missing values using the mode.
- convert_word_to_num_col(col): Converts words into numbers using word2number.
- count_countries_country(col): Counts the number of countries visited.

**Running the Script**

To execute the script, run the following command in a Python environment:

python SpendingHabitsUnveiled.ipynb

**Output**

- The cleaned and preprocessed dataset ready for further analysis.
- Various transformations applied to ensure consistency and correctness in data representation.

**Author**

**Aishwarya Naik**

**License**

This project is open-source and available for public use.
