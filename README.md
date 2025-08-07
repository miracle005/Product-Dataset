# Data Cleaning and Optimization Report

## Introduction

The data set is a product dataset, which is so ragged, dirty. The report outlines the data cleaning and title optimization process performed on the dataset. The dataset contained multiple fields related to product information including product Id, product title, description,and other attributes. The goal is to improve data quality by handling inconsistency, missing values, duplicate and remove values while optimizing product title usability and to be readable by SEO and provide a clean dataset.

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

## Short Title Creation 

To enhance SEO and usability, a methodology was developed to shorten the title while preserving essential information. The short short-title was generated through the following steps: 
Using Excel,

Removed unnecessary words from the title using Substitute

Truncated titles to a maximum length of 50 characters  

Using the Left and Right Formula, I was able to extract some meaningful characters

I ensured that the title still represented the product accurately.

### Example of Short-title 

| Original Title | Short Title |
|----------------|-------------|
| Ungifted: My Life and Journey | Ungifted Life Journey|
| Boys Girls Excavator Design T-Shirt Twins Kids Work Zone Slogan Tops Cotton Tees Grey 5 Years | Boys Girls Excavator Design T- on Tees Grey 5 Years |
|Twisted Swirl Vintage Blue Phone Case Compatible with iPhone 13, Orange Fluid Abstract Design Cover for Men Girl Women, Unique St TPU Bumper Case Cover | Twisted Swirl iphone 13 Vintage Blue Phone Case |
|ArtzFolio Tulip Flowers Blackout Curtain for, & Room | Eyelets & Tie Back | Canvas Fabric | Width 4.5feet -54inch) Height 5 feet -60 inch); 2PCS | Artzfolio Tuplip Blackout Curtain -2 pcs |

## Clean Dataset Overview 

After I completed the data cleaning and the title optimization process, these key statistics were observed: 
 
Total number of products = 3469. 

Average Product length = 1162.496467. 

After The Cleaning and Optimization process, the following were observed :

99.9% reduction in missing values

95% reduction in invalid rating

<img width="490" height="300" alt="Screenshot 2025-08-07 220452" src="https://github.com/user-attachments/assets/7da7c9d2-fa28-42e3-a702-655135122b17" />

This bar chart indicates the 8 Top most Product Type indicating the frequency of different Product Type IDS. The Highest Count Belongs to Product Type ID 206, meaning the product appeared most frequently in the dataset suggesting that this Products are more popular or dominant than the others.

<img width="488" height="293" alt="Screenshot 2025-08-07 220805" src="https://github.com/user-attachments/assets/74fd635c-0c4b-4f0a-a04a-f524ed22f108" />

The Column chart indicates the top 6 short title after cleaning the dataset. After Cleaning the dataset, I had to reduce the character to 50 character maximum into to make it more readable and meaningful for SEO.

<img width="490" height="298" alt="Screenshot 2025-08-07 221100" src="https://github.com/user-attachments/assets/ed2e5d83-101b-471b-9742-972b4fa4acd4" />


This Column Chart indicates Top 6 uncleaned product dataset. The dataset at this time had a lot of redundances which made it hard for SEO to read. This title had up a lot of character that made it difficult and cumbersome. 

## Conclusion

The data cleaning and title optimization process enhanced the dataset quality making it more readable, structured, usable and optimize for search engine. These would lead to efficient data utilization and product discoverability for further analysis. 




 
 







