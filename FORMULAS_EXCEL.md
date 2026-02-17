# Excel Formulas for Payroll Calculator 2026

## Basic Formulas

1. **SUM**: `=SUM(A1:A10)` - Adds up numbers in a range.
2. **AVERAGE**: `=AVERAGE(B1:B10)` - Calculates the average of numbers.
3. **COUNT**: `=COUNT(C1:C10)` - Counts the number of cells that contain numbers.

## Conditional Formulas

4. **IF**: `=IF(D1>1000, "Above Average", "Below Average")` - Returns one value if a condition is true and another if it's false.
5. **SUMIF**: `=SUMIF(E1:E10, ">1000")` - Adds up cells that meet a specified criterion.

## Lookup Formulas

6. **VLOOKUP**: `=VLOOKUP(F1, H1:J10, 2, FALSE)` - Looks for a value in the first column and returns a value in the same row from a specified column.
7. **HLOOKUP**: `=HLOOKUP(G1, A1:E5, 3, FALSE)` - Searches for a value in the top row and returns a value in the same column from a specified row.

## Date and Time Formulas

8. **TODAY**: `=TODAY()` - Returns the current date.
9. **NOW**: `=NOW()` - Returns the current date and time.

## Text Manipulation Formulas

10. **CONCATENATE**: `=CONCATENATE(A1, " ", B1)` - Combines several text items into one.
11. **LEFT**: `=LEFT(A1, 5)` - Returns the leftmost characters from a text string.

## Financial Formulas

12. **PMT**: `=PMT(rate, nper, pv)` - Calculates the payment for a loan based on constant payments and a constant interest rate.

## Example Usage in Payroll Calculator

- **Calculating Deductions**: Use `=SUMIF(Deductions!A:A, "Deductions", Deductions!B:B)` to sum specific deductions.
- **Calculating Gross Income**: `=SUM(Earnings!B:B) - SUM(Deductions!B:B)` to calculate total gross income.