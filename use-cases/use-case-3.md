# USE CASE: 3 Produce a Report on the Salary of Employees in My Department

## GOAL IN CONTEXT
As a department manager I want to produce a report on the salary of employees in my department so that I can support financial reporting for my department.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
Department Manager is authenticated and assigned to a specific department in the system.

## SUCCESS END CONDITION
A report of salaries for employees in the manager's department is provided.

## FAILED END CONDITION
No report is produced.

## PRIMARY ACTOR
Department Manager.

## TRIGGER
Department Manager requests salary report for their department.

## MAIN SUCCESS SCENARIO
1. Department manager requests the salary report for their own department.
2. System identifies the manager's department and fetches salary details for all employees in that department.
3. Department manager receives the salary report.

## EXTENSIONS
1. **Manager is not assigned to any department**:
    1. System informs manager that department assignment is missing.
2. **No employees in department**:
    1. System informs manager that no employee records exist for their department.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0