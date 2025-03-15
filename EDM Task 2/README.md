# Midterm Lab Task 2 - Data Cleaning and Transformation using POWER QUERY
This task is suppose to train us in cleaning a .csv (Comma-Seperated Values) and tranforming it with Power Query. We'll be doing cleaning uneccessary Columns and rows, fixing errors and giving dependencies.

## PART 1 Data Cleaning process
- Step 1: Launch Power Query
- Step 2: Duplicate the Raw Data (for Backup; optional)
- Step 3: Remove the Parenthesis and what's inside in the "Salary Estimate" Column
- Step 4: Create two new Column named "Min Sal" and "Max Sal" by selecting "Salary Estimate" column, choosing to "Column from Examples" and type in the first digits at for the "Min Sal" and the last digits for "Max Sal" 
- Step 5: Adding Column with "Custom Column" and inputted a formula to Simplify Job Roles/Type
- Step 6: Inputted a formula again to give commas and seperate the City/State to their Abbreviation to be used for Step 7
- Step 7: Split the column "Location" to seperate the City/State and their Abbreviation
- Step 8: Replace "Anne Arundel" with "MA" in the "Location Correction 2" Column and renamed the Column "State Abbreviation"
- Step 9: Splitted the "Size" Column to "MinCompanySize" and "MaxCompanySize" with the same process done in Step 4
- Step 10: Removed the "-1" and "Unknown" cells in "Competitor", "Revenues", and "Industry" columns
- Step 11: Removed the Ratings in the Company using "Split Columns" feature and Removed Job Description

## PART 2 Reshaping and Grouping the tables: 
- Step 1: Duplicate the New Raw Data from PART 1 and renamed it "Sal By Role Type dup"
- Step 2: Click choose columns and select "Role Type", "Min Sal", and "Max Sal"
- Step 3: Change Data Type of "Min Sal", and "Max Sal" to Currecny and Multiply it by 1000
- Step 4: Group the rows by role type and get the min sal and max sal average
- Step 5: Create a Reference from New Raw Data from PART 1 and renamed it "Sal By Size ref"
- Step 6: Do Step 2 to 4 but for "Size" instead of "Role Type"
- Step 7: Insert states_mapping.xlsx
- Step 8: Merge Queries and select States Abbreviation from Step 7, then select states sheet and Select Column 2
- Step 7: Create a Reference from New Raw Data from PART 1 and renamed it "Sal By State ref"
- Step 8: Do Step 2 to 4 but for "States Full Name" instead of "Role Type"

## ScreenShots
New Raw Data before:
New Raw Data after:
Sal by Role Type dup:
Sal by Size ref:
Sal by State ref:
Dependencies:


