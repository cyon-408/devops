# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## GOAL IN CONTEXT
As an HR advisor I want to produce a report on the salary of employees of a given role so that I can support financial reporting of the organisation.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
Database contains employee, salary, and job title records.

## SUCCESS END CONDITION
A report of salaries for employees in the specified role is provided to the HR advisor.

## FAILED END CONDITION
No report is produced.

## PRIMARY ACTOR
HR Advisor.

## TRIGGER
HR Advisor requests salary information for a specific job title.

## MAIN SUCCESS SCENARIO
1. HR advisor extracts salary information for a given job title.
2. HR advisor provides report to financial department.

## EXTENSIONS
1. **Role does not exist**:
    1. System informs HR advisor that no records match the given role.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0