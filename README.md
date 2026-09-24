Superstore Sales Data – Power Query & Data Cleaning
Objective

To import the Superstore Sales dataset into Power BI, perform data cleaning and transformation using Power Query, and load the cleaned data into the Power BI data model.

Dataset

The dataset contains Superstore sales information including:

Order ID
Order Date
Ship Date
Ship Mode
Customer ID
Customer Name
Segment
Country
City
State
Category
Sub-Category
Sales
Quantity
Discount
Profit
Other order and customer details
Tasks Performed
1. Import Superstore CSV
Imported the superstore_raw.csv file into Power BI.
Opened the dataset in Power Query Editor.
Promoted the first row as column headers.
Checked and assigned appropriate data types.
2. Text Formatting

Standardized text formatting for categorical attributes using Power Query.

The following columns were cleaned:

Category
Sub-Category
Segment
City
State

Used Capitalize Each Word to maintain consistent text formatting.

3. Date Transformation

The Order Date column was converted to the appropriate Date data type.

The following custom date columns were created:

Year
Month
Day

These transformations were performed using Power Query UI transformations and generated Power Query M Code.

4. Power Query M Code

Power Query automatically generated M Code for the transformations.

Examples include:

Date.Year([Order Date])
Date.Month([Order Date])
Date.Day([Order Date])

The M Code was verified using the Advanced Editor.

5. Data Cleaning

The dataset was checked for:

Incorrect data types
Inconsistent text formatting
Date formatting issues
Unwanted errors or blank rows

Conclusion

The Superstore Sales dataset was successfully imported into Power BI and transformed using Power Query. Text formatting was standardized, categorical attributes were cleaned, date-related columns were created, and Power Query M Code was used to perform and verify the transformations. The cleaned dataset was then loaded into the Power BI data model using Close & Apply.
