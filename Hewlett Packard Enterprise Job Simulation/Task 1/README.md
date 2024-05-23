## Task 1: Create a Proposal for a RESTful Web Service

### Task Overview
In this task, the goal was to understand the basics of Java Spring Boot, HPE GreenLake, and RESTful Web Services.

### What was learned
- The basics of Java Spring Boot
- Introduction to HPE GreenLake
- Fundamentals of RESTful Web Services

### Background Information
In this Job Simulation, the role involved stepping into the position of a back-end developer tasked with designing a RESTful web service using Java Spring Boot and GreenLake Cloud Platform. Java Spring Boot is a tool for building standalone applications that can run independently of a platform, while GreenLake Cloud Platform provides data storage services.

### About this Task
For the first task, the manager asked to learn about Java Spring Boot and GreenLake Cloud Platform. The task involved exploring the technical documentation for each tool and then writing a proposal for a RESTful web service to manage a list of employees.

### Specific Requirements
The specific requirements for this service included the following:
- It should support the GET, POST, DELETE, and UPDATE commands. 
  - The GET command should return the full list of employees, while the POST, DELETE, and UPDATE commands should affect individual entries.
- Each entry should have the following fields: `first_name`, `last_name`, `employee_id`, `email`, and `title`.
- This data should be stored on a private cloud server.

### Task Completion Steps
To complete the task, the following steps were undertaken:

#### Step 1
Start by reviewing the information included in the Resources section. There were resources to provide the basics of Java Spring Boot and HPE GreenLake, along with information about RESTful Web Services and an example of how to build a REST API using Java Spring Boot to learn about the POST, GET, PUSH, and DELETE commands.

#### Step 2
After reviewing the documentation, consider the design of a web service that supports the stated requirements. Determine which tools would be used and how, what service calls the design should support, and how these calls should be structured.

#### Step 3
Write up the proposal addressing the topics mentioned in the background information. The proposal should be around 250-400 words, detailing the design of the web service.

### Proposal

In designing a RESTful web service using Java Spring Boot and HPE GreenLake Cloud Platform, the aim is to create a robust system for managing a list of employees. This service will support the essential CRUD operations: Create, Read, Update, and Delete. Each employee entry will include the following fields: `first_name`, `last_name`, `employee_id`, `email`, and `title`. The data will be securely stored on a private cloud server provided by the HPE GreenLake Cloud Platform.

#### Key Components of the Design:
1. **GET Request**: This endpoint will return the full list of employees. By making a GET request, the client will receive a JSON array of all employee objects stored in the system. This allows for easy retrieval and display of employee data.
   
2. **POST Request**: This endpoint will allow for the addition of new employee entries. When a POST request is made with the necessary employee data, the service will create a new employee record and store it in the cloud database. This ensures that new employees can be added to the system dynamically.

3. **DELETE Request**: This endpoint will facilitate the removal of employee entries based on the `employee_id`. By sending a DELETE request with the specific `employee_id`, the corresponding employee record will be deleted from the database. This functionality is crucial for maintaining an up-to-date employee list.

4. **UPDATE Request**: This endpoint will enable modifications to existing employee entries. By making an UPDATE request with the `employee_id` and the updated data fields, the service will update the relevant employee record in the database. This ensures that any changes to employee details can be easily managed.

#### Implementation Details:
- **Java Spring Boot**: This framework will be utilized for its simplicity and efficiency in building standalone applications. Spring Boot's RESTful capabilities will be leveraged to handle HTTP requests and responses, ensuring that the web service adheres to REST principles.
- **HPE GreenLake Cloud Platform**: This platform will provide the necessary cloud infrastructure for data storage. By using GreenLake, the service will benefit from secure, scalable, and reliable data storage solutions.

By integrating Java Spring Boot and HPE GreenLake Cloud Platform, the proposed web service will offer a seamless and efficient way to manage employee data. The service will be designed to handle various HTTP requests, ensuring that employee information can be easily added, retrieved, updated, and deleted as needed. This proposal outlines a clear path for developing a scalable and maintainable RESTful web service that meets the specified requirements.
