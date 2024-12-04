# Prodigy_DS_01
Analyzing World Total Population using Python and Excel for Data Cleaning

## Prodigy InfoTech Data Science Internship Task 1:
**Task-01**:  
Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or genders in a population.

Welcome to my submission for Task 1 of the Data Science Internship at **Prodigy Infotech**. In this task, I have performed Exploratory Data Analysis (EDA) on a dataset provided, focusing on creating a visualization to represent the distribution of a categorical or continuous variable.

## Dataset
The dataset used for this task is the **world_population_dataset**. This dataset contains records of population from the year 1960 to 2023, including data on total population, male population, and female population for various countries.

## Tools and Libraries Used
- **Jupyter Notebook**: A powerful tool for creating and sharing documents that contain live code, equations, visualizations, and narrative text.
- **Pandas**: A library for data manipulation and analysis, especially useful for handling tabular data.
- **Numpy**: A library for numerical computing in Python, often used for working with large arrays and matrices of numerical data.
- **Matplotlib & Seaborn**: Libraries for data visualization, used to create plots such as bar charts and histograms to visualize the data.

## Exploratory Data Analysis (EDA)

During the EDA process, I performed the following steps:

### 1. Data Cleaning
- **Missing Values**: Checked for and handled any missing values in the dataset.
- **Duplicates**: Identified and removed any duplicate rows that might have skewed the analysis.
- **Column Name Adjustments**: Removed unnecessary columns and fixed column names (such as stripping leading/trailing spaces) to make the data easier to work with.
- **Data Conversion**: Converted certain columns to appropriate data types for analysis (e.g., converting population numbers to integers).

### 2. Data Filtering
- **Filtering by Population Indicator**: The dataset contains various population indicators, such as total population (`SP.POP.TOTL`) and male population (`SP.POP.TOTL.MA.IN`). I filtered the data to focus on the relevant population indicators.
  
### 3. Visualization
- **Bar Chart**: I created a bar chart to visualize the distribution of total population across countries for the year 2022. This chart represents the top 10 countries with the highest population.
  
- **Stacked Bar Chart**: Additionally, I visualized the distribution of male and female populations for the year 2022 to compare the gender ratio.

### 4. Sorting and Selection
- **Top and Bottom Countries**: I extracted and displayed the top 10 countries with the highest and lowest populations for both total population and male population in 2022 and 2023. This was achieved by sorting the dataset based on population values and using `.head()` to select the top 10 or bottom 10 countries.

### 5. Code Implementation
The following code snippet showcases the data cleaning and visualization processes performed during the analysis:

### 6. Conclusion
In this analysis, I performed data cleaning, filtering, and visualization to analyze the total population and male population for different countries. The visualization provides insights into the distribution of populations across countries for the year 2022. By sorting and selecting the top and bottom countries, I was able to identify the countries with the highest and lowest populations in both total and male populations.

This analysis helps in understanding the population trends globally and can be used for further demographic studies.
In conclusion, this EDA process provided valuable insights into the distribution of the selected variable in the dataset. This analysis lays the foundation for further exploration and modeling tasks in the data science workflow.
