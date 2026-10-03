# USE CASE: 6 View an Employee's Details

## GOAL IN CONTEXT
As an HR advisor I want to view an employee's details so that the employee's promotion request can be supported.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
Employee record exists in the database.

## SUCCESS END CONDITION
The selected employee's details are displayed to the HR advisor.

## FAILED END CONDITION
No employee details are displayed.

## PRIMARY ACTOR
HR Advisor.

## TRIGGER
HR Advisor searches for an employee to review their profile.

## MAIN SUCCESS SCENARIO
1. HR advisor enters an employee ID or name to search.
2. System retrieves and displays full details (personal info, job title, department, salary history).
3. HR advisor reviews the details.

## EXTENSIONS
1. **Employee ID / name not found**:
    1. System displays an error message stating that no matching employee was found.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0