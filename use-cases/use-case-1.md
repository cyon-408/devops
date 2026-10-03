# USE CASE: 1 Produce a Report on the Salary of All Employees

## GOAL IN CONTEXT
As an HR advisor I want to produce a report on the salary of all employees so that I can support financial reporting of the organisation.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
Database contains employee and salary records.

## SUCCESS END CONDITION
A report of salaries for all employees is provided to the HR advisor.

## FAILED END CONDITION
No report is produced.

## PRIMARY ACTOR
HR Advisor.

## TRIGGER
HR Advisor requests salary information for all employees.

## MAIN SUCCESS SCENARIO
1. HR advisor requests salary information for all employees.
2. System extracts salary information for all active employees.
3. HR advisor receives the salary report.

## EXTENSIONS
1. **No active employees found**:
    1. System informs HR advisor that no employee records exist.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0