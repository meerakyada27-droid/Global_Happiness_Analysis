# 🌍 GLOBAL HAPPINESS DATA ANALYSIS

**Author:** Meera Kyada

## 📌 Project Description

Global Happiness Data Analysis is a data science project developed using Python and its popular data analysis and visualization libraries. The main purpose of this project is to explore and analyze happiness levels across different countries around the world.

This project uses the World Happiness Report 2024 dataset, which contains information about happiness scores and several social and economic factors. These factors include GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, and perceptions of corruption.

Using Python, NumPy, Pandas, Matplotlib, and Seaborn, the project performs data cleaning, data processing, statistical analysis, comparison, and visualization to discover meaningful patterns and insights from the dataset.

The analysis helps understand how different factors are associated with happiness and how happiness levels vary across countries and geographical regions.

## 🎯 Project Objectives

- To understand global happiness levels across different countries.
- To analyze the World Happiness Report 2024 dataset.
- To identify the happiest and least happy countries.
- To compare happiness scores among different geographical regions.
- To study the relationship between GDP per capita and happiness.
- To analyze the association of social support, health, freedom, and other factors with happiness scores.
- To perform data cleaning and preprocessing.
- To apply NumPy for numerical operations and statistical calculations.
- To use Pandas for data manipulation and analysis.
- To create meaningful visualizations using Matplotlib and Seaborn.
- To extract useful information and conclusions from real-world data.

## ✨ Project Features

- Load and explore a real-world happiness dataset.
- Display the first and random records.
- Check dataset dimensions, columns, and data types.
- Generate descriptive statistical summaries.
- Identify missing values and duplicate records.
- Clean the dataset by handling missing values.
- Find the highest, lowest, and average happiness scores.
- Display the top 10 happiest countries.
- Display the 10 least happy countries.
- Calculate region-wise average happiness scores.
- Compare happiness scores with GDP per capita.
- Analyze social support and healthy life expectancy.
- Perform sorting and conditional filtering.
- Create NumPy arrays and perform mathematical operations.
- Apply Pandas GroupBy, aggregation, pivot, merge, and join operations.
- Analyze correlations between numerical factors.
- Generate different charts and graphs.
- Export processed data into CSV and JSON formats.
- Display important findings from the analysis.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Python Version:** Python 3.14.6
- **IDE:** Visual Studio Code
- **Notebook Environment:** Jupyter Notebook
- **Numerical Computing:** NumPy
- **Data Analysis:** Pandas
- **Data Visualization:** Matplotlib
- **Statistical Visualization:** Seaborn

## 📂 Dataset Information

**Dataset Name:** World Happiness Report 2024

**Dataset File:** `World-happiness-report-2024.csv`

**Initial Dataset Size:** 143 Rows × 12 Columns

The dataset contains happiness-related information for different countries. It includes the following important columns:

| Column Name | Description |
|---|---|
| Country name | Name of the country |
| Regional indicator | Geographical region |
| Ladder score | Overall happiness score |
| Upperwhisker | Upper confidence interval |
| Lowerwhisker | Lower confidence interval |
| Log GDP per capita | Economic condition indicator |
| Social support | Social support level |
| Healthy life expectancy | Expected healthy lifespan |
| Freedom to make life choices | Freedom indicator |
| Generosity | Generosity indicator |
| Perceptions of corruption | Corruption perception indicator |
| Dystopia + residual | Additional happiness score component |

## 🔍 Project Modules

### 1. Data Loading and Exploration

- Import the required Python libraries.
- Load the CSV dataset using Pandas.
- Display the first few records using `head()`.
- Display random records using `sample()`.
- Check the dataset dimensions using `shape`.
- Examine column names using `columns`.
- Understand data types and non-null values using `info()`.
- Generate statistical summaries using `describe()`.

### 2. Data Cleaning and Preprocessing

- Check missing values using `isnull()`.
- Calculate the total number of missing values.
- Remove missing records using `dropna()`.
- Identify duplicate records using `duplicated()`.
- Remove duplicate records using `drop_duplicates()`.
- Convert suitable columns into categorical data types.
- Prepare clean data for further analysis.

### 3. Statistical Analysis

- Calculate average happiness scores.
- Identify maximum and minimum happiness scores.
- Calculate standard deviation using NumPy.
- Find the happiest country.
- Find the least happy country.
- Compare regional happiness averages.
- Analyze numerical values using statistical functions.

### 4. Country-wise Analysis

- Display the top 10 happiest countries.
- Display the 10 least happy countries.
- Sort countries by happiness scores.
- Filter countries with happiness scores greater than 7.
- Compare country-wise happiness factors.
- Create a dictionary and list of records for country information.

### 5. Region-wise Analysis

- Count the number of countries in each region.
- Calculate average happiness scores by region.
- Find the highest and lowest happiness regions.
- Calculate maximum and minimum regional happiness scores.
- Perform multiple aggregations using GroupBy.
- Create a region-wise pivot table.

### 6. Relationship Analysis

- Compare GDP per capita with happiness scores.
- Study the relationship between social support and happiness.
- Analyze healthy life expectancy.
- Examine freedom to make life choices.
- Compare generosity and perceptions of corruption.
- Calculate correlation between numerical variables.

## 🔢 NumPy Operations

NumPy is used for numerical computation and array-based analysis.

The following operations are performed:

- Create 1D and 2D arrays.
- Access array elements using indexing.
- Extract values using slicing.
- Perform addition, subtraction, multiplication, and division.
- Calculate mean, maximum, minimum, and standard deviation.
- Apply Boolean filtering and masking.
- Reshape arrays into different dimensions.
- Perform broadcasting operations.
- Analyze happiness scores using NumPy arrays.

## 🐼 Pandas Operations

Pandas is used for data manipulation, cleaning, and analysis.

The project covers:

- Series and DataFrame operations.
- DataFrame exploration and inspection.
- Missing value handling.
- Duplicate value handling.
- Sorting and filtering.
- GroupBy and multiple aggregations.
- Transform operations.
- Pivot table creation.
- Merging and joining datasets.
- Categorical data conversion.
- Date and time handling.
- Exporting data into CSV and JSON formats.

## 📊 Data Visualization

Matplotlib and Seaborn are used to represent the analysis through visual charts.

### Matplotlib Charts

1. **Bar Chart:** Displays the top 10 happiest countries.
2. **Bar Chart:** Displays the 10 least happy countries.
3. **Line Chart:** Shows average happiness scores by region.
4. **Scatter Plot:** Compares GDP per capita with happiness scores.
5. **Pie Chart:** Represents country distribution by region.
6. **Histogram:** Shows the distribution of happiness scores.
7. **Subplots:** Displays multiple charts in one figure.
8. **Stack Plot:** Compares selected happiness-related values.
9. **Saved Chart:** Exports the generated visualization as an image.

### Seaborn Charts

1. **Bar Plot:** Displays region-wise average happiness.
2. **Scatter Plot:** Shows the relationship between GDP and happiness.
3. **Heatmap:** Displays correlations between numerical variables.

## 🧠 Concepts Covered

The project also applies important Python programming concepts learned during the course.

### Python Fundamentals

- Variables and data types.
- Operators and expressions.
- Type casting.
- Input and output.
- Conditional statements.
- Loops and control statements.

### Strings and Collections

- String manipulation.
- Lists and list comprehension.
- Tuples and sets.
- Dictionaries.
- List of dictionaries.
- Mutable and immutable data types.

### Functions

- Built-in and user-defined functions.
- Lambda functions.
- `*args` and `**kwargs`.
- Recursion.
- Global variables.
- Multiple return values.
- Docstrings.
- Higher-order functions: `map()`, `filter()`, `reduce()`, and `sorted()`.

### Object-Oriented Programming

- Classes and objects.
- Constructors and destructors.
- Encapsulation.
- Inheritance.
- Polymorphism.
- Method overriding.
- Abstraction.
- Abstract classes and methods.
- `self` and `super()`.

### Exception and File Handling

- Try and except.
- Else and finally.
- Raising exceptions.
- Assertions.
- Text file operations.
- Reading and writing files.

### Modules and Packages

- Importing modules.
- Date and time modules.
- Math, random, and UUID modules.
- Creating and importing packages.
- `__name__ == "__main__"`.
- `dir()` function.

## 📁 Project Structure

    Global_Happiness_Final_Project/
    │
    ├── Global_Happiness_Analysis.ipynb
    ├── World-happiness-report-2024.csv
    ├── Cleaned_Global_Happiness.csv
    ├── Global_Happiness.json
    ├── Top_10_Happiest_Countries.png
    └── README.md

## ⚙️ Installation and Setup

### Requirements

- Python 3.14.6
- Visual Studio Code
- Jupyter Notebook
- Required Python libraries

### Step 1: Install Required Libraries

Open the VS Code terminal and run:

    pip install numpy pandas matplotlib seaborn

### Step 2: Open the Project

Open the `Global_Happiness_Final_Project` folder in Visual Studio Code.

### Step 3: Open Jupyter Notebook

Open the following notebook:

    Global_Happiness_Analysis.ipynb

### Step 4: Check Dataset Location

Make sure the dataset file is stored in the same project folder as the notebook.

### Step 5: Execute the Notebook

Run all notebook cells in sequence to perform data loading, cleaning, analysis, and visualization.

## 📤 Project Deliverables

The project generates the following outputs:

- Cleaned dataset in CSV format.
- Processed dataset in JSON format.
- Statistical analysis results.
- Country-wise and region-wise comparisons.
- Data visualization charts.
- Correlation analysis.
- Final findings and conclusions.
- Jupyter Notebook containing the complete analysis.

## 📷 Sample Output

The following outputs are generated by the project:

- Top 10 Happiest Countries chart.
- 10 Least Happy Countries chart.
- Average Happiness by Region chart.
- GDP vs Happiness scatter plot.
- Country Distribution by Region pie chart.
- Happiness Score Distribution histogram.
- Correlation Heatmap.
- Multiple charts using Subplots.

## 📌 Key Findings

The analysis helps discover:

- The overall average happiness score of the available countries.
- The country with the highest happiness score.
- The country with the lowest happiness score.
- Differences in happiness across geographical regions.
- The relationship between GDP per capita and happiness.
- The association between social support, health, freedom, and happiness.
- Correlations among different numerical factors.

The findings are based on the available 2024 dataset and describe associations rather than proving cause-and-effect relationships.

## 🌎 Real-World Applications

Global Happiness Data Analysis can be useful in several areas:

- **Government Planning:** Helps understand social and economic factors related to citizens' happiness.
- **Economic Research:** Supports the study of the relationship between economic conditions and well-being.
- **Social Research:** Helps analyze the importance of social support and freedom.
- **Healthcare Research:** Provides insights into the relationship between healthy life expectancy and happiness.
- **Data Science Learning:** Demonstrates how real-world datasets can be cleaned, analyzed, and visualized.
- **Comparative Studies:** Helps compare happiness levels among countries and regions.

## 🚀 Future Improvements

The project can be extended with the following improvements:

- Analyze happiness reports from multiple years.
- Compare changes in happiness over time.
- Develop an interactive dashboard using Streamlit or Power BI.
- Apply Machine Learning algorithms for happiness score prediction.
- Perform advanced statistical analysis.
- Add more geographical and economic comparisons.
- Create an interactive country-level analysis system.

## 🎓 Learning Outcomes

By completing this project, I gained practical experience in:

- Working with real-world datasets.
- Using Python for data analysis.
- Performing data cleaning and preprocessing.
- Applying NumPy for numerical operations.
- Using Pandas for data manipulation.
- Performing statistical and comparative analysis.
- Creating visualizations with Matplotlib and Seaborn.
- Understanding relationships between multiple variables.
- Interpreting analytical results.
- Presenting data-driven findings in a structured format.

## 📌 Project Status

**Status:** Completed

**Project Title:** Global Happiness Data Analysis

**Dataset:** World Happiness Report 2024

**Tools:** Python, NumPy, Pandas, Matplotlib, Seaborn, and Jupyter Notebook.

---

## 🙏 Thank You

Thank you for visiting my Global Happiness Data Analysis project!