# USE CASE: 5 Add a New Employee's Details

## GOAL IN CONTEXT
As an HR advisor I want to add a new employee's details so that I can ensure the new employee is paid.

## SCOPE
Company HR System.

## LEVEL
Primary task.

## PRECONDITIONS
HR Advisor has valid details for the new employee (e.g., name, birth date, job title, salary, department).

## SUCCESS END CONDITION
A new employee record is successfully created in the database.

## FAILED END CONDITION
The employee record is not created.

## PRIMARY ACTOR
HR Advisor.

## TRIGGER
HR Advisor receives information for a new hire and chooses to add them to the system.

## MAIN SUCCESS SCENARIO
1. HR advisor inputs the new employee's personal and job details.
2. HR advisor submits the information.
3. System validates the input data and creates a new employee record with salary details.
4. System confirms successful creation to the HR advisor.

## EXTENSIONS
1. **Invalid or missing employee data**:
    1. System highlights missing or incorrect fields and prompts the HR advisor to re-enter details.
2. **Employee ID already exists**:
    1. System informs HR advisor of duplicate entry and aborts operation.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0