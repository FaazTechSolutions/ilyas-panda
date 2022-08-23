# Clearance
-----------
#### Add Direction in Component setup as
- Credit
- Debit
- Nil
#### Based on Component Direction Update Clearance Amount
#### Once Clearance Approved, will do following
- Create Clearance and Clearance Lines with Component Details
- Settle Salary as Paid by settlement
- Settle Loan then delete and re-create loan.
- Create Accrual Settlement Transaction for Vacation
•	Add GL Account Id , Financial Item Id in Component for Financial Integration

•	In Every Component Updates will reflect the clearance amount

# EOS
------
#### EOS will calculate based on EOS Profile Setup
•	Show following
- EOS profile
- Total kingdom days
- Amount
- Break Up Lines

# Vacation
-----------
•	Show following information
- Vacation Days
- Vacation Eligible Days
- Amount
•	Calculation Based on Equation
•	Get Vacation Eligibility from Accrual Balance-Need to work with finance

# Food
-------
•	Food should calculate for Individual employee
•	User Can include/exclude Food Deduction
•	Show following
- Lodging Days
- Food Count
- Amount

# Ticket
---------
•	Show the Ticket Amount as Text box

# Salary
-----------
•	Show following
- Due Salary Amount
- Salary Payment
•	Once Clearance approved change salary status as Paid by Settlement
•	If Timesheet in progress, stop clearance process

# Loan
-------
•	Show Following
- Due loan
- Deduction Amount
•	User Can include/exclude Loan Deduction
•	If user choose include selection, make Deduction amount as Due Loan

# Other Payment/Other Deduction
--------------------------------
•	Remove Payment Days option
•	User will update the Payment/Deduction

# Government Fees
------------------
•	Make setup to mapping between Component and Expense type
•	Based on Iqama Remaining Days , Calculate Expense based on Expense Setup in Individual module
•	Save the Expense Break up in Reference Fields
•	Show Following
- Amount
- Expense Break up

# AR Transaction
------------------
•	AR Transaction Penalty amount will create as Invoice
•	Amount will not reflect in Clearance

