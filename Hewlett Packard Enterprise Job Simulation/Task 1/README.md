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
The proposal should describe the design of a RESTful web service using Java Spring Boot and HPE GreenLake Cloud Platform. The service will support CRUD operations (Create, Read, Update, Delete) on a list of employees, with each employee having `first_name`, `last_name`, `employee_id`, `email`, and `title` fields. The service will utilize a private cloud server for data storage and implement RESTful principles to ensure efficient and scalable interaction with the client applications.

#### Key Components of the Design:
- **GET Request**: To fetch the full list of employees.
- **POST Request**: To add a new employee entry.
- **DELETE Request**: To remove an employee entry based on `employee_id`.
- **UPDATE Request**: To modify the details of an existing employee entry.

The service will leverage Java Spring Boot for rapid development and deployment, ensuring that the application is easy to manage and scale. HPE GreenLake Cloud Platform will provide the robust and secure data storage needed to maintain employee information.
