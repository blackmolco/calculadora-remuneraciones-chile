# Chilean Payroll System 2026

## Overview
This README provides comprehensive instructions for utilizing the Chilean payroll system for the year 2026. The system is designed to assist in calculating employee remunerations accurately and efficiently.

## Sheets Structure
The payroll system consists of the following key sheets:

1. **Employee Data Sheet**  
   - Columns:  
     - Employee ID  
     - Name  
     - Address  
     - Position  
     - Base Salary  
     - Contract Type  
     - Start Date  

2. **Payroll Calculation Sheet**  
   - Columns:  
     - Employee ID  
     - Gross Salary  
     - Deductions  
     - Net Salary  

3. **Deductions Sheet**  
   - Columns:  
     - Employee ID  
     - Type of Deduction  
     - Amount  
     - Reason  

4. **Summary Sheet**  
   - Shows aggregated data such as total gross salary, total deductions, and total net salary for all employees.

## Formulas Used
- **Gross Salary Calculation**:  
   `=Base Salary + Overtime + Bonuses`
- **Deductions Calculation**:  
   `=SUM(Deductions Sheet!C:C)`  
   (Sums all deductions listed in the Deductions Sheet)
- **Net Salary Calculation**:  
   `=Gross Salary - Total Deductions`

## Usage Guide
1. **Input Employee Data**:  
   - Fill in the Employee Data Sheet with accurate details of each employee.  
   - Ensure all required fields are completed.

2. **Calculate Payroll**:  
   - After entering employee data, navigate to the Payroll Calculation Sheet.  
   - Use provided formulas to calculate gross salary and deductions automatically.

3. **Review Deductions**:  
   - Refer to the Deductions Sheet to list any deductions applicable to employees.  
   - Ensure this information is accurate before finalizing payroll.

4. **Generate Summary**:  
   - Use the Summary Sheet to view aggregated payroll data.  
   - Review totals for compliance and record-keeping purposes.

5. **Export/Print**:  
   - Once all data is verified and calculated, export or print the necessary sheets as needed for payroll distribution.

## Additional Information
- Ensure to review the latest updates to Chilean labor laws as they may affect payroll calculations.
- Backup your data regularly to prevent loss of information.