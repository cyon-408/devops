# USE CASE: 2 Produce a Report on the Salary of Employees in a Department

## GOAL IN CONTEXT
As an HR advisor I want to produce a report on the salary of employees in a department so that I can support financial reporting of the organisation.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
Database contains employee, department, and salary records.

## SUCCESS END CONDITION
A report of salaries for employees in the specified department is provided to the HR advisor.

## FAILED END CONDITION
No report is produced.

## PRIMARY ACTOR
HR Advisor.

## TRIGGER
HR Advisor specifies a department and requests a salary report.

## MAIN SUCCESS SCENARIO
1. HR advisor inputs or selects a specific department name/ID.
2. System extracts salary information for all employees belonging to that department.
3. HR advisor receives the department salary report.

## EXTENSIONS
1. **Department does not exist or has no employees**:
    1. System informs HR advisor that no records match the specified department.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0