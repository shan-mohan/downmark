# Boundary Documentation

HR application owns the employee details that gets stored in below master table. The details stored
here are shared with downstream modules like (Payroll, Operations, Appraisal and Payments).

|Schema|TableName|ColumnName      |ColumnType|ColumnSize|
|------|---------|----------------|----------|----------|
|SCH1  |Employee |Emp_ID          |BigInt    |8         |
|SCH1  |Employee |Emp_Name        |VARCHAR   |35        |
|SCH1  |Employee |Emp_Designation |VARCHAR   |30        |
|SCH1  |Employee |Emp_Address     |VARCHAR   |30        |
|SCH1  |Employee |Emp_City        |VARCHAR   |30        |
|SCH1  |Employee |Emp_Department  |VARCHAR   |30        |
|SCH1  |Employee |Emp_Salary      |VARCHAR   |30        |
|SCH1  |Employee |Emp_Start_Date  |VARCHAR   |30        |
|SCH1  |Employee |Emp_End_Date    |VARCHAR   |30        |
