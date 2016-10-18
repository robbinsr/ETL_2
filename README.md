# ETL EXAMPLE STEP 2 #

You are reading the README.md file in the `ETL_2` repository for Russ Robbins. This repository shows files related to:

- understanding the NHIS 1994 household records' data fields' purposes, their contents, and their data types
- confirming meta-data in `06724-Codebook.pdf` (which is necessary since it wasn't developed by a business process I understand)
- standardizing NHIS 1994 household field names to make field names and the data to be loaded into Oracle more usable by future users 

---
Inputs to Step 2
===

 - `06724-Codebook.pdf` 
 - `06724-0001-Data.txt`
 - both at https://github.com/robbinsr/ETL_2/tree/master/transforming_household/from_step_1


Processing for Step 2
===

 - Importing fixed width '06724-0001-Data.txt' text file to empty new file `robbins_etl_06724-0001-Data-1994.xlsx`.
 - Standardizing field names and documenting in crosswalk file `robbins_etl_06724-0001-Data-Crosswalk-1994.xlsx`.
 - Importing `robbins_etl_06724-0001-Data-1994.xls` into empty new file `robbins_etl_06724-0001-Data-Analysis-1994.accdb`
 - Writing SQL queries in `robbins_etl_06724-0001-Data-Analysis-1994.accdb` to generate unique values per field.
 - Writing SQL queries in `robbins_etl_06724-0001-Data-Analysis-1994.accdb` to generate counts of unique values per field.
 - Comparing query results to `06724-Codebook.pdf` information about fields' unique values .
 - Comparing query results to `06724-Codebook.pdf` information about counts of fields' unique values.
 - Recording analysis results in `robbins_etl_06724-0001-Data-Analysis-1994.xlsx` 

Outputs of Step 2
===

**Pass through from Step 1**

 - `06724-Codebook.pdf` 
 - `06724-0001-Data.txt` 
 - Each of these files can be found at https://github.com/robbinsr/ETL_2/tree/master/transforming_household/to_step_3 

**New files**

- `robbins_etl_06724-0001-Data-1994.xlsx`
- `robbins_etl_06724-0001-Data-Crosswalk-1994.xlsx`
- `robbins_etl_06724-0001-Data-Analysis-1994.accdb`
- `robbins_etl_06724-0001-Data-Analysis-1994.xlsx`
- Each of these files can be found at https://github.com/robbinsr/ETL_2/tree/master/transforming_household/to_step_3

More information about step 2 can be found at `transforming_household` (and its subdirectories) at https://github.com/robbinsr/ETL_2/tree/master/transforming_household .

Please feel free to move to the ETL_3 repository at this point, or at a future moment of your convenience.
