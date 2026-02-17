#  Exploratory Data Analysis (EDA) – House Prices Dataset  

## Overview  

This project applies Exploratory Data Analysis (EDA) techniques to a real estate dataset.  
The objective is to understand the dataset structure, identify patterns, and determine the key factors that influence house prices.  

---

## Dataset Description  

The dataset includes property-related attributes such as:  

- Location  
- Price (in rupees)  
- Carpet Area  
- Number of Bathrooms  
- Furnishing Status  
- Ownership  
- Transaction Type  
- Additional property characteristics  

---

## EDA Process  

The following steps were performed:  

1. Loaded the dataset using **Pandas**.  
2. Inspected column names, data types, and summary statistics.  
3. Cleaned and converted numerical fields where necessary.  
4. Visualized the distribution of house prices using histograms.  
5. Explored relationships between price and other variables using scatter and regression plots.  
6. Analyzed average prices across different locations.  
7. Generated a correlation matrix for numerical features.  

---

## Key Findings  

- House prices vary significantly depending on the **location**.  
- Numerical variables such as **Carpet Area** and **Bathrooms** show limited direct correlation with price.  
- Categorical features appear to play an important role in determining property value.  

---

## Visualization Libraries Used  

###  Matplotlib  
Matplotlib is a low-level plotting library that provides full control over visualization customization. It is highly flexible and suitable for creating detailed and customized plots.  

###  Seaborn  
Seaborn is built on top of Matplotlib and provides a higher-level interface for creating attractive statistical visualizations with less code. It offers better default styling and built-in statistical plots.  

###  Main Difference  
- **Matplotlib** → More control and customization.  
- **Seaborn** → Easier to use with better default design and statistical features.  

Both libraries were used to effectively visualize patterns and relationships within the dataset.  

---

## Tools & Technologies  

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- VS Code  

---

## Conclusion  

EDA provided valuable insights into the dataset and highlighted important factors affecting house prices.  
The analysis establishes a strong foundation for future predictive modeling and machine learning applications.  
