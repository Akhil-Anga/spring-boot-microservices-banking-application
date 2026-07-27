# Spring-Boot-Microservices-Banking-Application

## Table of Contents

- [About](#about)
- [Architecture](#architecture)
- [Microservices](#microservices)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Future Enhancement](#future-enhancement)
- [Contribution](#contribution)
- [Contact Information](#contact-information)

## About

The Banking Application is built using a microservices architecture, incorporating the Spring Boot framework along with other Spring technologies such as Spring Data JPA, Spring Cloud, and Spring Security, alongside tools like Maven for dependency management. These technologies play a crucial role in establishing essential components like Service Registry, API Gateway, and more.

Moreover, they enable the development of independent microservices such as the user service for user management, the account service for account generation and other related functionalities, the fund transfer service for various transfer operations, and the transaction service for viewing transactions and facilitating withdrawals and deposits. These technologies not only streamline development but also enhance scalability and maintainability, ensuring a robust and efficient banking system.

## Architecture

- **Service Registry:** The microservices use the discovery service for service registration and service discovery. This helps the microservices to discover and communicate with other services without needing to hardcode the endpoints while communicating with other microservices.

- **API Gateway:** This application uses the API gateway to centralize the API endpoints, where all the endpoints have a common entry point. The API Gateway also facilitates security inclusion, handling the Authorization and Authentication for the application.

- **Database per Microservice:** Each microservice has its own dedicated database. For this application, we are incorporating the MySQL database for all microservices. This helps to isolate each of the services from each other, which facilitates each service having its own data schemas and allows for scaling each database when required.

## Microservices

- **User Service:** The user microservice provides functionalities for user management. This includes user registration, updating user details, viewing user information, and accessing all accounts associated with the user. Additionally, this microservice handles user authentication and authorization processes.

- **Account Service:** The account microservice manages account-related APIs. It enables users to modify account details, view all accounts linked to the user profile, access transaction histories for each account, and supports the account closure process.

- **Fund Transfer Service:** The fund transfer microservice facilitates various fund transfer-related functionalities. Users can initiate fund transfers between different accounts, access detailed fund transfer records, and view specific details of any fund transfer transaction.

- **Transactions Service:** The transaction service offers a range of transaction-related services. Users can view transactions based on specific accounts or transaction reference IDs, as well as make deposits or withdrawals from their accounts.

## Getting Started

To get started, follow these steps to run the application on your local environment:

- Make sure you have Java 17 installed on your system. You can download it from the official Oracle website.
- Select an Integrated Development Environment (IDE) such as Eclipse, Spring Tool Suite, or IntelliJ IDEA. Configure the IDE according to your preferences.
- Clone the repository containing the microservices onto your local system using Git. Navigate to the directory where you have cloned the repository.
- Navigate to each microservice directory within the cloned repository and run the application. You can do this by using your IDE or running specific commands depending on the build tool used (e.g., Maven or Gradle).
- Set up Keycloak for authentication and authorization. Refer to the detailed configuration guide provided [here](https://devscribbles.hashnode.dev/mastering-microservices-authentication-and-authorization-with-keycloak) for step-by-step instructions on configuring Keycloak for your microservices.
- Some microservices and APIs may depend on others being up and running. Ensure that all necessary microservices and APIs are up and functioning correctly to avoid any issues in the application workflow.

## Documentation

### Microservices Documentation

For detailed information about each microservice, refer to their respective README files:

- [User Service](./User-Service/README.md)
- [Account Service](./Account-Service/README.md)
- [Fund Transfer Service](./Fund-Transfer/README.md)
- [Transactions Service](./Transaction-Service/README.md)

### API Documentation

For a detailed guide on API endpoints and usage instructions, explore the comprehensive [API Documentation](https://app.theneo.io/student/spring-boot-microservices-banking-application). This centralized resource offers a holistic view of the entire banking application, making it easier to understand and interact with various services.

### Java Documentation (JavaDocs)

Explore the [Java Documentation](https://kartik1502.github.io/Spring-Boot-Microservices-Banking-Application/) to delve into detailed information about classes, methods, and variables across all microservices. These resources are designed to empower developers by providing clear insights into the codebase and facilitating seamless development and maintenance tasks.

## Future Enhancement

As part of the ongoing commitment to improving the banking application, several enhancements are planned to enrich user experience and expand functionality:

- Implementing a robust notification system to keep users informed about important account activities, such as transaction updates, account statements, and security alerts. Integration with email and SMS will ensure timely and relevant communication.
- Adding deposit and investment functionalities to enable users to manage their savings and investments directly through the banking application. Features such as fixed deposits, recurring deposits, and investment portfolio tracking will empower users to make informed financial decisions.
- And more...

## Contribution

Contributions to this project are welcome! Feel free to open issues, submit pull requests, or provide feedback to enhance the functionality and usability of this banking application. Please follow the basic PR specification while creating a pull request.

Let's build a robust and efficient banking system together using Spring Boot microservices!

Happy Banking!

## Contact Information

If you have any questions, feedback, or need assistance with this project, please feel free to reach out:

- **Name:** Venkata Sai Akhil Anga
- **Email:** venkatasaiakhilanga@gmail.com
- **GitHub:** [https://github.com/Akhil-Anga](https://github.com/Akhil-Anga)
- **LinkedIn:** [https://www.linkedin.com/in/akhil-anga](https://www.linkedin.com/in/akhil-anga)

We appreciate your interest in this project and look forward to hearing from you. Happy coding!

## About the Maintainer

Venkata Sai Akhil Anga is a Full Stack Developer with 5 years of experience designing and delivering scalable enterprise applications. Specializing in Java, Spring Boot, and cloud-native architectures, he has extensive experience in developing microservices and responsive web solutions. With a strong background in Agile development and API integration, he focuses on optimizing performance, security, and system scalability to deliver high-quality software solutions for enterprise environments.