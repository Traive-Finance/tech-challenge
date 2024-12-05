# **Traive Challenge - Backend Developer**

### **Overview**
Below, we have outlined a problem where you will design and develop an application to meet specific requirements. This is your opportunity to showcase your expertise! We will be assessing how you structure your project, organize your code, and apply concepts, best practices and technologies to deliver a robust solution.

### **Problem Statement**
You will create a **JSON API over HTTP** with the following requirements. The API will manage a collection of **Farms** and their associated **Crop Productions**, with data stored in a persistent and durable storage system of your choice.

**For senior-level (IC3) or higher positions**, we expect the solution to be implemented using **Golang**, which is our primary backend language at Traive.

**For positions below senior-level**, unless explicitly stated otherwise by one of our employees, you are free to choose from any of the following programming languages:
- Golang
- JavaScript or TypeScript
- Java or Kotlin
- C#
- Python

### **Requirements**
The API should support the following capabilities:

1. **Create a Farm** with nested Crop Productions
2. **Delete a Farm** by its ID
3. **List all Farms**

Here’s a brief description of the expected schema of the objects the API will support:

- **Farm Object** Each Farm object must include at least the following fields:
  - **ID**: Unique identifier.
  - **Farm Name**: Name of the farm.
  - **Land Area**: Numeric value representing the physical land area of the farm.
  - **Unit of Measure**: Unit for land area (e.g., “acre” or “hectare”).
  - **Address**: Mailing address of the farm.
  - **List of Crops / Productions**: A nested list of associated crop production records.
- **Production Record** Each production record must include:
  - **Crop Type**: Enum field with possible values being `RICE`, `BEANS`, `CORN`, `COFFEE`, and `SOYBEANS`.
  - **Is Irrigated**: Boolean field indicating if irrigation is used.
  - **Is Insured**: Boolean field indicating if the crop is insured.

### **Deliverables**
- A fully functional JSON API that meets the requirements.
- Persistent storage of data in a storage system of your choice.
- A clear and organized project structure that adheres to best practices for backend development.
  - Use of modular, well-documented code;
  - Separation of concerns;
  - Environment configuration using `.env` or equivalent mechanisms.


### **Stretch Goals**
The following are not required but will be considered a plus:

- **Unit and Integration Tests**: Demonstrate code reliability through automated testing.
- **Ease of Deployment**
  - Containerization using Docker (include a `Dockerfile` or `docker-compose` configuration).
  - Clear and easy setup instructions for deploying the application.
- **Production-Readiness**
  - Proper logging for debugging and monitoring.
  - Validation of input data and error handling.
  - Best practices (e.g., validation, sanitization, security best practices, etc.).
- **API Documentation**: Use OpenAPI or a similar tool to document your API endpoints.
- **General Documentation**: Provide a comprehensive README file with the following:
  - Project overview.
  - How to set up and run the application locally.
  - Deployment instructions.
  - How to run tests.
- **Pagination and Filters**: Implement pagination and filtering in the "List all Farms" endpoint to handle large datasets efficiently (e.g., filtering by crop type or land area).


## **Submission Guidelines**
Include all source code and documentation in a Git repository and send it us. We'll review it as soon as possible and get back to you!
P.S.: For discretion reasons, please avoid including `Traive` anywhere in your challenge!
