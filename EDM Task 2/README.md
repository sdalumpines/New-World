# Midterm Lab Task 2 - Data Cleaning and Transformation using POWER QUERY
This task is suppose to train us in cleaning a .csv (Comma-Seperated Values) and tranforming it with Power Query. We'll be doing cleaning uneccessary Columns and rows, fixing errors and giving dependencies.

## PART 1 Data Cleaning process
- Step 1: Launch Power Query
- Step 2: Duplicate the Raw Data
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
- Step 2: 
- Perform 3 NF
- Mapped the Normalized tables as a Physical Data Model
## STEP 3 Here's the screenshot of my output before I started data cleaning (See screenshot)
<img src="images/1.JPG" alt="Alt Text" width="400" height="300">

## STEP 4 Here's the screenshot of my output after I started data cleaning (See screenshot)
![Sample Output](images/1.JPG)
## Here's the Physical Data Model
