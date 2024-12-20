The Payroll Management System (PMS) is an essential platform for organizations to manage payroll operations effectively and securely. PMS streamlines employee management, payroll processing, tax compliance, and reporting while adhering to strict data security protocols. It is designed to function under a subscription model with a freemium trial period for customization based on client requirements.

Key Features:
> Employee Management: Manage personal details, job roles, promotions, and department assignments.
> Payroll Processing: Automate payroll calculations, tax deductions, and payment initiation.
> Time and Attendance Management: Track working hours, overtime, and absences with manager approvals.
> Tax Management: Calculate and withhold taxes with automatic compliance checks.
> Department and Position Management: Assign employees to roles and maintain department data.
> User Authentication: Role-based access control to ensure data security.
> Report Generation: Generate detailed payroll, attendance, and tax reports.
> Payment Processing: Streamlined salary disbursement with finance department approvals.

Database Design
Entity-Relationship Overview: Key relationships include:

> 1:1: Each employee has one bank account, user ID, and tax ID.
> 1:M: Departments managed by one employee, employees submitting multiple timecards.
> M:M: Employees holding multiple positions across departments.

<img width="539" alt="image" src="https://github.com/user-attachments/assets/6cd26773-59d7-4721-9788-088325137206" />

Example Tables:
Employee Table: Stores personal and job-related details.
Payroll Table: Tracks salary, deductions, and tax information.
Attendance Table: Logs hours worked, absences, and overtime.
