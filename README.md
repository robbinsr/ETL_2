# ETL EXAMPLE STEP 2 #

You are reading the README.md file in the `ETL_2` repository for Russ Robbins. This repository shows files related to:

- understanding the household records' data fields' purposes, their contents, and their data types
- confirming meta-data in `06724-Codebook.pdf` (which was provided by an external party)
- standardizing field names to make field names and the data more usable by future database users 

---
Inputs to Step 2
===

 - `06724-Codebook.pdf` in https://github.com/robbinsr/ETL_1/tree/master/DS1_Household 
 - `06724-0001-Data.txt` in https://github.com/robbinsr/ETL_1/tree/master/DS1_Household/DS0001

Processing for Step 2
===

 - Importing fixed width '06724-0001-Data.txt' text file to `robbins_etl_06724-0001-Data-1994.xlsx`.
 - Standardizing field names shown crosswalk file `robbins_etl_06724-0001-Data-Crosswalk-1994.xlsx`.
 - Importing `robbins_etl_06724-0001-Data-1994.xls` into `robbins_etl_06724-0001-Data-Analysis-1994.accdb`
 - Writing SQL queries to generate unique values per field.
 - Writing SQL queries to generate counts of unique values per field.
 - Comparing query results to `06724-Codebook.pdf` information about fields' unique values .
 - Comparing query results to `06724-Codebook.pdf` information about counts of fields' unique values.
 - Recording analysis results in `robbins_etl_06724-0001-Data-Analysis-1994.xlsx` 

Outputs of Step 2
===

 - `06724-Codebook.pdf` in https://github.com/robbinsr/ETL_2/tree/master/DS1_Household 
 - `06724-0001-Data.txt` in https://github.com/robbinsr/ETL_2/tree/master/DS1_Household/DS0001

and 

- `robbins_etl_06724-0001-Data-1994.xlsx`
- `robbins_etl_06724-0001-Data-Crosswalk-1994.xlsx`
- `robbins_etl_06724-0001-Data-Analysis-1994.accdb`
- `robbins_etl_06724-0001-Data-Analysis-1994.xlsx`
- Each of these files can be found at: https://github.com/robbinsr/ETL_2/tree/master/DS1_Household/DS0001

