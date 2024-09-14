### Languages and Tools

- **Python**: Used for data cleaning and analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib/Seaborn**: For generating visualizations.
- **Jupyter Notebook**: For developing the Python code.

# Internet Connectivity Data Analysis: Data Cleaning and Summarization

## Overview

This project focuses on the cleaning, preparation, and exploration of a dataset provided by UNICEF related to the digital connectivity of school-age children. The data is analyzed to identify trends, patterns, and relationships between attributes such as region, income group, and internet access at home. The project was developed as part of the **Practical Data Science with Python** course, and includes comprehensive data preparation steps and exploratory analysis, using Python in a Jupyter Notebook environment.

### Key Features

1. **Data Cleaning**:
   - The dataset provided by UNICEF contains information about the percentage of children with internet access at home, categorized by region, income group, residence (rural/urban), and more.
   - Several data cleaning steps were taken, including handling missing values, outliers, redundant white spaces, and invalid data formats. 
   - Functions such as `value_counts()`, `info()`, and user-defined cleaning methods were employed to ensure a clean and reliable dataset.

2. **Exploratory Data Analysis**:
   - The cleaned dataset was analyzed to gain insights into internet connectivity among school-age children in different regions and income groups.
   - Visualizations were generated to represent the distribution of connectivity across regions, income groups, and residence types.
   - The analysis included comparing internet access across various regions and identifying top-performing countries in terms of connectivity.

3. **Data Summarization**:
   - Statistical summaries were performed on key attributes to understand the spread and distribution of the data.
   - Relationships between categorical and numerical variables were explored through grouped bar charts and line plots.

### System Design and Methods

- **Data Cleaning**:
   - The cleaning process involved dealing with various types of errors in the dataset, including redundant white spaces, outliers, and invalid values.
   - Missing values were handled using techniques such as filling with mean/median values and dropping unnecessary columns.
   - Specific attributes like `ISO3`, `Country`, `Region`, `Sub Region`, and `Income Group` were manually reviewed and corrected as needed.

- **Exploratory Data Analysis (EDA)**:
   - The analysis focused on key attributes such as `Region`, `Income Group`, and `Total Percentage of School-age Children with Internet Access at Home`.
   - Visualizations were created to represent the percentage of children with internet access by region and income group.
   - Trends in internet connectivity over time were also explored.

### Tasks Completed

1. **Data Cleaning**:
   - Loaded and cleaned the dataset using Python’s Pandas library.
   - Removed invalid values, handled missing data, and corrected inconsistencies in the dataset.

2. **Data Exploration**:
   - Generated visualizations for the distribution of children’s internet access by region, income group, and type of residence (rural/urban).
   - Identified the top 10 countries with the highest internet connectivity for school-age children.

3. **Report Generation**:
   - A comprehensive report summarizing the data cleaning process and exploratory analysis was created in PDF format. This report highlights the main findings of the project.

### Files in the Repository

- **`code.ipynb`**: Jupyter Notebook containing the Python code for data cleaning and exploration.
- **`report.pdf`**: Detailed report documenting the data cleaning process, exploration findings, and visualizations.
- **`dataset.zip`**: The original dataset provided by UNICEF, used for the analysis.

### How to Run the Project

1. **Set Up Jupyter Notebook**:
   - Install Anaconda if you haven’t already, and use the Jupyter Notebook environment for running the Python code.
   
2. **Run the Notebook**:
   - Open the `code.ipynb` notebook in Jupyter.
   - Execute the cells step by step to clean the data and generate the visualizations.
   
3. **View the Report**:
   - Open `report.pdf` to view a summary of the data cleaning and exploration process.

### Data Source

The dataset used for this project is sourced from UNICEF’s global database on school-age digital connectivity. The dataset contains information on the internet connectivity of children aged 3-17 years across different regions and countries.
