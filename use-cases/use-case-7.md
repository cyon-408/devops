# USE CASE: 7 Update an Employee's Details

## GOAL IN CONTEXT
As an HR advisor I want to update an employee's details so that employee's details are kept up-to-date.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
Employee record exists in the database.

## SUCCESS END CONDITION
The employee's details are updated in the database.

## FAILED END CONDITION
The employee's details remain unchanged.

## PRIMARY ACTOR
HR Advisor.

## TRIGGER
HR Advisor receives updated information (e.g., promotion, salary raise, department transfer) for an existing employee.

## MAIN SUCCESS SCENARIO
1. HR advisor searches and selects the target employee.
2. System displays current details.
3. HR advisor modifies the required fields and saves the changes.
4. System validates and updates the database record.
5. System confirms successful update to the HR advisor.

## EXTENSIONS
1. **Employee record not found**:
    1. System informs HR advisor that the specified employee does not exist.
2. **Invalid data format entered**:
    1. System displays validation errors and requests correct input.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0