# Exploratory Data Analysis: Iris Dataset  
**Author**: Molly Shelhamer  
**Date**: July 16, 2025  

## Overview
This project is a structured introductory exploratory data analysis (EDA) of the classic Iris dataset. The objective is to inspect, describe, and visualize the dataset to extract meaningful insights and prepare for potential modeling tasks.

## Project Structure
- **Data**: Iris dataset, loaded directly via `seaborn.load_dataset('iris')`
- **Tools**:  
  - Python  
  - pandas  
  - seaborn  
  - matplotlib  

## Key Steps
1. **Imports**  
   Standard EDA libraries including pandas, seaborn, and matplotlib.  

2. **Data Loading**  
   The Iris dataset is loaded into a pandas DataFrame and its structure is previewed.  

3. **Initial Inspection**  
   Dataset dimensions, column data types, and high-level summary using `.info()`, `.head()`, and `.shape`.  

4. **Descriptive Statistics**  
   Summary statistics with `.describe()` to understand distribution and spread of numerical features.  

5. **Distribution Analysis**  
   - Histograms and count plots to explore distributions of numeric and categorical features.  
   - **Observation**: Sepal features follow a more normal distribution; petal features show greater variability across species.  

6. **Feature Engineering**  
   - Renamed `sepal_length` to `Sepal Length`.  
   - Created a new feature: `Sepal Area = Sepal Length × sepal_width`.  

7. **Visualizations**  
   - **Pairplot** colored by species to explore pairwise relationships.  
   - **Scatter plot** of Sepal Length vs. Sepal Area by species.

8. **Insights**  
   - Sepal measurements are generally consistent across species.  
   - Petal measurements vary significantly and may be more useful for classification tasks.

## Requirements
This project uses standard Python libraries. To run the notebook, ensure the following packages are installed:

```bash
pip install pandas seaborn matplotlib

