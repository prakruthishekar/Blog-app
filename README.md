# Real-Time Blog Application

The Real-Time Blog Application is a comprehensive RESTful API project built using Spring Boot and related technologies. It allows users to manage blog posts, implement user authentication, and deploy the application on the AWS cloud.

## Technologies Used

- Java 8+
- Spring Boot
- Spring MVC
- Spring Data JPA (Hibernate)
- Spring Security
- JWT (JSON Web Token)
- Tomcat (Embedded server)
- MySQL Database
- Swagger (API documentation)
- Postman (REST API testing)
- Maven (Build tool)
- AWS (Deployment on production)

## Features

- CRUD Operations: Create, Read, Update, and Delete blog posts.
- Pagination and Sorting: Navigate and organize blog posts with ease using pagination and sorting.
- Search and Filtering: Find specific blog posts based on criteria using search and filtering functionalities.
- User Authentication: Secure login, sign-in, and signup with Spring Security and JWT.
- Data Validation: Ensure data integrity and consistency with robust data validation mechanisms.
- Role-based Security: Implement role-based access control and authorization for secure REST APIs.
- Database Interaction: Interact with the MySQL database efficiently using Spring Data JPA.
- API Documentation: Generate comprehensive API documentation with Swagger for easy integration and understanding.
- Deployment on AWS: Deploy the application on the AWS cloud for production use, ensuring scalability and reliability.

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone the repository.
2. Configure the MySQL database and update the application properties accordingly.
3. Build the project using Maven.
4. Run the application using your preferred IDE or the command line.
5. Access the APIs through the provided endpoints and test using Postman or any other REST API testing tool.

## Usage

1. Register a user account and obtain authentication credentials (JWT).
2. Use the obtained credentials to authenticate and access protected endpoints.
3. Perform CRUD operations on blog posts, manage user accounts, and utilize other available functionalities.

## Documentation

The API documentation for the Real-Time Blog Application is available in the Swagger UI. Follow the steps below to access it:

1. Start the application and ensure it is running locally.
2. Open a web browser and navigate to the Swagger UI endpoint (e.g., http://localhost:8080/swagger-ui.html).
3. Explore the available endpoints, request/response formats, and execute API calls directly from the Swagger UI.
