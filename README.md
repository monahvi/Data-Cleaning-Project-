# Data Cleaning Project Queries

This repository contains SQL queries and scripts developed for a data cleaning project focused on a housing dataset from Nashville. The queries aim to enhance data quality, standardize formats, and improve overall data organization. The dataset is available in the "Nashville Housing Data for Data Cleaning.xlsx" file, and the corresponding SQL script, "Data Cleaning Project Queries.sql," documents the cleaning process.

## Queries Overview

### Standardize Date Format

- Convert the date format in the `SaleDate` column for consistency.

### Populate Property Address Data

- Fill in missing values in the `PropertyAddress` column based on matching `ParcelID` values.

### Break out Address into Individual Columns

- Split the `PropertyAddress` column into separate columns for address, city, and state.

### Break out Owner Address into Individual Columns

- Split the `OwnerAddress` column into separate columns for address, city, and state.

### Change Y and N to Yes and No

- Standardize values in the `SoldAsVacant` column to "Yes" or "No."

### Remove Duplicates

- Identify and remove duplicate records based on specific criteria.

### Delete Unused Columns

- Streamline the dataset by removing unnecessary columns.

## Usage

1. **Data Source:** Open the "Nashville Housing Data for Data Cleaning.xlsx" file to access the raw dataset.
2. **SQL Script:** Execute the queries provided in "Data Cleaning Project Queries.sql" to clean and transform the data in a SQL environment.

Feel free to adapt these queries to your specific dataset or contribute improvements to enhance the data cleaning process. Your feedback and contributions are highly appreciated!
