# Task 2: Build a Basic RESTful Web Service

## Task Overview
In this task, you will start to build out the basics of a RESTful web service using Java Spring Boot. The goal is to create a system that can be queried by sending an HTTP GET request to http://localhost:8080/employees. The service should respond with a JSON representation of the list of all employees in the system.

### Background Information
In your first task, your manager asked you to explore how to use Java Spring Boot to build a RESTful web service that manages a list of employees. 

For this task, you will create a basic web service that responds to an HTTP GET request with a JSON representation of employee data. You will hard code the list of employees into your system, and it does not need to support requests to add new employees.

#### Components of the System:
- **Employee Class**: Includes private variables for the fields `first_name`, `last_name`, `employee_id`, `email`, and `title`, along with getter functions for each variable.
- **Employees Class**: Manages the full list of employees.
- **Controller Class**: Allows the user to request the full list of user data.

### Task Steps
To complete the task, follow these steps:

1. **Review Resources**: Begin by reviewing the provided resources for building a RESTful web service using Java Spring Boot. This includes tutorials and example repositories.
   
2. **Download Repository**: Download the source repository provided in the resources, which contains examples and templates for building the web service.

3. **Create Employee Class**: Define a resource class for the Employee, including private variables for `employee_id`, `first_name`, `last_name`, `email`, and `title`, along with getter functions for each variable.

4. **Create Employees Class**: Implement a class called Employees to manage the full list of employees. This class should support getting and setting the employee list.

5. **Create EmployeeManager Class**: Develop a class named EmployeeManager responsible for initializing the Employees class and hard-coding example employees into the system.

6. **Add Controller**: Implement a resource controller that supports an HTTP GET request at http://localhost:8080/employees. This controller should return all user data in a JSON format.

7. **Build and Launch Application**: Build an executable version of your application and launch the executable file.

8. **Test the Application**: Send an HTTP GET request to http://localhost:8080/employees to ensure that your application works as expected.

9. **Submission**: Once your application is working correctly, submit a zip file containing the core application files, including Employee.java, Employees.java, EmployeeController.java, EmployeeManager.java, and RestServiceApplication.java.

For more information about Java Spring Boot and RESTful development, review the provided resources.
