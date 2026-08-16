# Social Media Data Analysis

## Project Overview

This project involves analysing a social media dataset containing 20,001 records and 22 variables. The dataset contains information about users, posts and engagement.

The aim of the project is to explore the dataset, ensure the data is suitable for analysis, identify patterns and trends, and develop meaningful insights into social media engagement.

## Dataset

The dataset contains 20,001 rows and 22 columns.

The variables include:

- Post ID
- User ID
- Username
- User Gender
- User Age
- Followers Count
- Following Count
- Account Creation Date
- Verified
- Location
- Topics
- Post Content
- Content Length
- Hashtags
- Has Media
- Post Date
- Device
- Language
- Likes
- Comments
- Shares
- Engagement Rate

## Data Types

### Numerical
- User Age
- Followers Count
- Following Count
- Content Length
- Likes
- Comments
- Shares
- Engagement Rate

### Categorical
- User Gender
- Verified
- Location
- Topics
- Has Media
- Device
- Language

### Dates
- Account Creation Date
- Post Date

### Text / Identifiers
- Post ID
- User ID
- Username
- Post Content
- Hashtags

## Data Cleaning and Validation

The first stage of the project involved checking the dataset for data quality issues.

### Missing Values

I used Microsoft Excel filters to check for:

- Blank cells
- N/A values
- Null values
- Unknown values

No standard missing values were identified through these filters.

However, during further inspection, an invalid character (`¬`) was identified in the Content Length column. This value was treated as a missing/invalid value and replaced with a blank cell before analysis.

### Duplicate Check

I checked for duplicate values using Microsoft Excel.

For Post IDs, I used:

`=IF(COUNTIF($A$A,A2)>1,"Duplicate","Unique")`

No duplicate Post IDs were identified.

Post IDs were treated as unique identifiers rather than analytical variables.

## Progress So Far

Completed:

- [x] Inspected dataset structure
- [x] Identified 20,001 rows and 22 columns
- [x] Classified variables by data type
- [x] Checked for missing values
- [x] Identified and cleaned an invalid Content Length value
- [x] Checked for duplicate Post IDs
- [x] Validated the dataset for basic consistency

## Next Steps

- Conduct exploratory data analysis
- Analyse social media engagement patterns
- Investigate relationships between variables
- Create data visualisations
- Identify meaningful trends and insights
- Summarise findings and conclusions

## Tools

- Microsoft Excel
- Data analysis and statistical techniques
- SQL 
