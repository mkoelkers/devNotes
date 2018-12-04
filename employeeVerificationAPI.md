# Make Employee verification API

- Create EmployeeVerification DTO
- Create EmployeeVerification Controller
  - Takes in EmployeeVerification DTO
  - Call EmployeeVerification Viewhandler
    - Create EmployeeVerification View Handler
        - takes in DOB, fName, lName, Gender
        - Queries to find matching employee
        - Return the employee to the controller or NULL
  - return the found employee 