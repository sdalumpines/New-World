# Midterm Lab Task 1
This page shows the steps that I did to Clean, Normalize, and putting relationships in a Data, with Screenshots of Before and After together with the Relationships of the Data.

## STEP 1. Data Cleaning
- Step One: Autofitted columns and rows
- Step Two: Identified and removed duplicated
- Step Three: Trimmed extra spaces
- Step Four: Eliminated blank spaces in Column D (Region Column)
- Step Five: spell check (corrected "Excelent" -> "Excellent"
- Step Six: Data validation for Region and Rating columns
- Step Seven: Added Sales column for Quantity and Price per Unit computation with IFERROR command
- Step Eight: Formatted Currency to Numbers for efficiency
- Step Nine: Replaced "inf" from Price per Unit to blank

## STEP 2. Normalization
- Step One: Gave ID's for Region, Rating, Product, and Sales
- Step Two: Created two new column to seperate Customer's names to first name and last name
- Step Three: Used "=VLOOKUP" function to ID Region and Rating. Created a new Temp sheet to tag names
- Step Four: Created six new sheets to group Customer, Region, Rating, Product, and Sales

## STEP 3. Power Query and Relational Data Model
- Step One: Loaded the five group in Power Query (Customer, Region, Rating, Product, Sales)
- Step Two: Cleaned the nulls to all sheets and removed duplicates from Region and Rating
- Step Three: "Save and Load to" then proceed to choose Relational
- Step Four: Pressed "Data Model" and pressed Diagram Model to ease the process then proceeded to Drag Primary Keys to Foreign Keys

## ScreenShots.
- Before:
- After:
- Relationships:
