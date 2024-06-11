# Data_Cleaning_SQL
Data cleaning with SQL

This project demonstrates the process of cleaning and transforming data stored in a SQL Server database using SQL queries.

## Description

The project involves cleaning a dataset of Nashville housing data, which includes the following steps:

1. **Standardizing the Date Format**: The `SaleDate` column is converted from a datetime format to a date format.
2. **Populating Property Address Data**: Missing property addresses are populated using the `ParcelID` and `UniqueID` columns.
3. **Breaking out Address into Individual Columns**: The `PropertyAddress` and `OwnerAddress` columns are split into separate columns for address, city, and state.
4. **Changing 'Y' and 'N' to 'Yes' and 'No' in 'Sold as Vacant' Field**: The values in the `SoldAsVacant` column are updated to display 'Yes' and 'No' instead of 'Y' and 'N'.
5. **Removing Duplicates**: Duplicate rows are identified and removed using a common technique involving window functions and CTEs.
6. **Deleting Unused Columns**: Unused columns are removed from the final dataset.

## Technologies Used

- SQL Server
- Microsoft SQL Server Management Studio (SSMS)

## Usage

1. Open the `Data Cleaning_SQL.sql` file in Microsoft SQL Server Management Studio (SSMS).
2. Connect to your SQL Server database.
3. Run the SQL queries in the file to perform the data cleaning process.

## Contribution

This project is open-source and contributions are welcome. If you find any issues or have suggestions for improvements, please feel free to create a new issue or submit a pull request.

