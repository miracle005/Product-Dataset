# Data Cleaning and Optimization Report

## Introduction

The data set is a product dataset, which is so ragged, dirty. The report outlines the data cleaning and title optimization process performed on the dataset. The dataset contained multiple fields related to product information including product Id, product title, description,and other attributes. The goal was to improve data quality by handling inconsistency, missing values, duplicate and remove values while optimizing product title usability and to be readable by SEO and provide a clean dataset.

## Data Cleaning 

The dataset was Inspected for inaccuracies and inconsistencies and the following issues were observed 

- ### Inconsistent Formatting:
  The column names were all capitalized. They were extra spaces and special character in the title column.
  
- ### Duplicates:
   I removed product entry that are the same or appeared twice
  
- ### Missing Values:
   product description, Category and product_type_id and product Length has a lot of missing values, which made the data incomplete.
  
- ### Invalid rating:
  Some product_type_id had invalid rating of “0”.

 To address the issues observed, the following steps were taken the resolve these issues
  
- Standardization of formatting: I Standardized the column names (Title), Removed extra spaces and special character.
  
- Removal of Duplicates: I identified and removed duplicated entries
  
- Handling Missing Values: I filled missing product category and descriptions with “Not Available”, and I also imputed missing value in the productLenght using the median value. 

- Invalid Ratio: I corrected invalid rating int the product_type_id and ensured numerical field were correctly formatted.
