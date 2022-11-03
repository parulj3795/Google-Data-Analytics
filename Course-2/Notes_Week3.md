# Week 3

## Spreadsheets

* The first steps a data analyst takes when working with data in a spreadsheet are to sort and filter the data.
* To perform calculations in a spreadsheet, data analysts use formulas and functions, such as SUM, AVERAGE, and COUNT.
* Spreadsheets are an important tool in every data analyst’s toolkit. They help you organize, clean, and analyze data. The sharing and commenting features in Google Sheets let you communicate and collaborate with teammates — a key part of your role as a data analyst.
* Spreadsheet titles should be short, clear, and state exactly what the data in the spreadsheet is about.
* Data analysts use formulas and functions to save time and effort by automating commands.

**Operator** - A symbol that names the type of operation or calculation to be performed.

**Cell Reference** - A cell or range of cells in a worksheet that can be used in a formula.

**Range** - A collection of two or more cells.

* Absolute referencing is marked by a dollar sign ($). For example, =$A$10 has absolute referencing for both the column and the row value. Absolute references will not change when you copy and paste the formula in a different cell. The cell being referenced is always the same.

* Resolving **#DIV/0!** error - =IFERROR(A1/B1,"Not Applicable")
* Resolving **ERROR!** (parsing error) - A formula can't be interpreted as input
* **N/A** error - Data in a formula can't be found in the spreadsheet. Use VLOOKUP
* **NAME?** error - A formula or function name isn't understood. Eg. VLOOOKUP instead of VLOOKUP.
* **NUM!** error - A formula or function calculation can't be performed as specified.
* **VALUE!** error - A general error that could indicate a problem with a formula or referenced cells.
* **REF!** - A formula is referencing a cell that is no longer valid or has been deleted.  