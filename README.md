# Employee Management System
This project is a simple Employee Management System built with Java Spring Boot, this version uses Spring Data REST and Spring Data JPA. It provides a RESTful API where clients can perform CRUD operations on the `Employee` entity.
This was mainly made for practise with refactoring an existing app to make use of some Spring features like Spring Data JPA and Spring Data REST. As you can see in the files, this saved me writing a lot of boiler plate code. 

## Features
- Retrieve all employees (`GET /employees`)
- Retrieve an employee by ID (`GET /employees/{employeeId}`)
- Add a new employee (`POST /employees`)
- Update an existing employee (`PUT /aemployees`)
- Delete an employee (`DELETE /employees/{employeeId}`)

## REST API
The REST API is exposed on `localhost:8080` and provides the following endpoints:

- `GET /employees`: Returns a list of all employees.
- `GET /employees/{employeeId}`: Returns the employee with the specified employeeId.
- `POST /employees`: Create a new employee.
- `PUT /employees`: Update an existing employee.
- `DELETE /employees/{employeeId}`: Delete the employee with the specified employeeId.

Note: For add and update operations, the employee data should be sent as a JSON in the request body.
