# USE CASE: 8 Delete an Employee's Details

## GOAL IN CONTEXT
As an HR advisor I want to delete an employee's details so that the company is compliant with data retention legislation.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
Employee record exists in the database and is eligible for deletion.

## SUCCESS END CONDITION
The employee's details are removed or archived according to data retention rules.

## FAILED END CONDITION
The employee record is not deleted.

## PRIMARY ACTOR
HR Advisor.

## TRIGGER
HR Advisor identifies an employee record that needs to be deleted due to legal compliance.

## MAIN SUCCESS SCENARIO
1. HR advisor searches and selects the employee record to delete.
2. HR advisor confirms deletion request.
3. System removes (or flags as deleted) the employee record from the database.
4. System notifies the HR advisor of successful deletion.

## EXTENSIONS
1. **Employee record not found**:
    1. System informs HR advisor that the record does not exist.
2. **Deletion restricted due to foreign key / dependency constraints**:
    1. System informs HR advisor that dependencies must be cleared first.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0