# ETL EXAMPLE STEP 02 #

You are reading the README.md file in the `etl_example_step_02` repository for Russ Robbins. This repository shows files related to:

- understanding the data fields' purposes, their contents, and their data types
- confirming meta-data in `06724-Codebook.pdf` (which was provided by an external party)
- standardizing field names to make field names and the data more usable by future database users 

---
Inputs to Step 02
===

 - `06724-Codebook.pdf` in https://github.com/robbinsr/etl_example_step_0/tree/master/DS1_Household 
 - `06724-0001-Data.txt` in https://github.com/robbinsr/etl_example_step_0/tree/master/DS1_Household/DS0001

Processing for Step 02
===

 - Importing fixed width '06724-0001-Data.txt' text file to `robbins_etl_06724-0001-Data-1994.xlsx`.
 - Standardizing field names shown crosswalk file `robbins_etl_06724-0001-Data-Crosswalk-1994.xlsx`.
 - Importing `robbins_etl_06724-0001-Data-1994.xls` into `robbins_etl_06724-0001-Data-Analysis-1994.accdb`
 - Writing SQL queries to generate unique values per field.
 - Writing SQL queries to generate counts of unique values per field.
 - Comparing query results to `06724-Codebook.pdf` information about fields' unique values .
 - Comparing query results to `06724-Codebook.pdf` information about counts of fields' unique values.
 - Recording analysis results in `robbins_etl_06724-0001-Data-Analysis-1994.xlsx` 

Outputs of Step 02
===

 - `06724-Codebook.pdf` in https://github.com/robbinsr/etl_example_step_0/tree/master/DS1_Household 
 - `06724-0001-Data.txt` in https://github.com/robbinsr/etl_example_step_0/tree/master/DS1_Household/DS0001

and 

- `robbins_etl_06724-0001-Data-1994.xlsx`
- `robbins_etl_06724-0001-Data-Crosswalk-1994.xlsx`
- `robbins_etl_06724-0001-Data-Analysis-1994.accdb`
- `robbins_etl_06724-0001-Data-Analysis-1994.xlsx`
- Each of these files can be found at: https://github.com/robbinsr/etl_example_step_02/tree/master/DS1_Household/DS0001

