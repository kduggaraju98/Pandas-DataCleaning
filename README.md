**Data Cleaning with Pandas**

This project demonstrates the process of cleaning and preparing raw customer call list data for analysis using Python's Pandas library. The aim is to transform messy and inconsistent data into a clean, usable format for further analysis and decision-making.

**Key Operations Performed**

1) Duplicate Removal: Identified and removed duplicate entries to ensure data integrity.

2) Column Removal: Dropped irrelevant or non-informative columns, optimizing the dataset for analysis.

3) String Cleaning: Stripped non-alphanumeric characters from fields such as Last_Name and Phone_Number.

4) Phone Number Formatting: Standardized the format of phone numbers for consistency.

5) Missing Value Handling:

    - Replaced NaN values with blank entries to handle missing data gracefully.

    - Dropped rows with missing or invalid critical values, such as phone numbers or marked as "Do Not Contact."

6) Address Splitting: Separated the Address field into Street Address, State, and ZipCode for better data segmentation.

7) Categorical Value Standardization:

    - Simplified values in Paying Customer and Do_Not_Contact fields (e.g., replacing "Yes" with "Y").

8) Index Reset: Reset indices after row removals for better data structure.

**Key Steps**

1) Import raw data from an Excel file.

2) Perform a sequence of cleaning tasks:

3) Removing duplicates.

    - Cleaning and formatting string fields.

    - Handling missing or irrelevant data.

    - Splitting complex fields into multiple columns.

4) Finalize the cleaned dataset for further analysis or export.

**Outcome**

The resulting dataset is clean, structured, and ready for analytics, ensuring better insights and data-driven decision-making.
