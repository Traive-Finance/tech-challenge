# **Traive Challenge - Frontend Developer**

### **Overview**

Below, we have outlined a problem where you will design and develop an application to meet specific requirements. This is your opportunity to showcase your expertise! We will be assessing how you structure your project, organize your code, and apply concepts, best practices and technologies to deliver a robust solution.

### **Problem Statement**

You will create an **application** that will manage a collection of **Farms** and their associated **Crop Productions**, with data persisting via [json-server](https://www.npmjs.com/package/json-server) through REST API.

## Running Local Server

Enter The `frontend` folder and install the dependencies by `npm i`. After that, you can simply run `npm start` and the `json-server` library will support you with the necessary endpoints and methods. Feel free to access the [documentation](https://www.npmjs.com/package/json-server) to understand supported endpoints and query parameters.

### **Requirements**

The App should support the following capabilities:

1. **Create a Farm** with nested Crop Productions.
2. **Delete a Farm** by its ID.
3. **List all Farms** from the most recent to the oldest.

To guide your development Here’s a brief possible API Contract of the expected schema that our potential server would support:

- **Farm** Each Farm object must include at least the following fields:
  - **ID**: Unique identifier. `required`
  - **Farm Name**: Name of the farm.
  - **Land Area**: Numeric value representing the physical land area of the farm. `required`
  - **Unit of Measure**: Unit for land area (e.g., “acre” or “hectare”). `required`
  - **Address**: Mailing address of the farm.
  - **List of Crop Productions**: A nested list of associated crop production records. `required`
- **Crop Production** Each crop production must include:
  - **ID**: Unique identifier. `required`
  - **Crop Type**: A reference to the crop types from the database. `required`
  - **Is Irrigated**: Boolean field indicating if irrigation is used.
  - **Is Insured**: Boolean field indicating if the crop is insured.
- **Crop Type**
  - **ID**: Unique identifier. `required`
  - **name**: Name of the crop type. `required`

### **Deliverables**

- A fully functional JSON API that meets the requirements.
- Persistent storage of data in a storage system of your choice.
- A clear and organized project structure that adheres to best practices for frontend development.

### **Stretch Goals**

The following are not required but will be considered a plus:

- **Enhanced List Experience**
  - Search
  - Paginated Results
  - Dynamic Page sizes
- **Code Reliability through Testing**
  - Unit tests.
  - E2E tests.
- **Ease of Deployment**
  - CI/CD integration to deploy changes.
- **Production-Readiness**
  - Validation of input data and error handling.
  - Smooth user experience (including proper feedbacks when user interacts with the product)
- **General Documentation**
  - Project Overview.
  - Deployment instructions.
  - Local Development instructions.
  - Testing instructions.

## **Submission Guidelines**

Include all source code and documentation in a Git repository and send it us. We'll review it as soon as possible and get back to you!
_P.S.: For discretion reasons, please avoid including `Traive` anywhere in your challenge!_
