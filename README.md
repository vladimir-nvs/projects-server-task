**Home Assessment Task for Java Junior Developer**

**Task Overview:**
Your task is to develop a Java application that manages project entities through a RESTful API. Additionally, you are required to containerize the application using Docker.

**Requirements:**

1. **Java Application:**
   - Create a Java application using a suitable framework (e.g., Spring Boot) to implement a RESTful API.
   - The application should include CRUD operations for managing projects.
   - A project should have at least a name, description, start date, and end date.

2. **Database:**
   - Use a relational database (e.g., MySQL, PostgreSQL) to store project data, or in-memory database (e.g., H2). Completely up to you.
   - Ensure that the application can perform basic CRUD operations on the projects.

3. **RESTful API Endpoints:**
   - Implement the following RESTful API endpoints:
      - `GET /projects`: Retrieve a list of all projects.
      - `GET /projects/{id}`: Retrieve details of a specific project.
      - `POST /projects`: Create a new project.
      - `PUT /projects/{id}`: Update an existing project.
      - `DELETE /projects/{id}`: Delete an existing project.

4. **Docker Container:**
   - Dockerize your Java application.
   - Create a Dockerfile to build the Docker image.
   - The Docker container should include all necessary dependencies, and the application should run inside the container.

5. **Documentation:**
   - Provide clear and concise documentation on how to build and run the Docker container locally.
   - Include instructions on how to use the REST API endpoints (e.g., using cURL or Postman).

**Submission Guidelines:**

1. **Code Submission:**
   - Submit the source code of your Java application along with any configuration files to public GitHub repo
   - Include the Dockerfile in the submission.

2. **Documentation Submission:**
   - Submit a README.md file that includes instructions for building and running the Docker container.
   - Include examples of API requests to demonstrate the functionality.

**Evaluation Criteria:**

1. **Functionality:**
   - CRUD operations should work correctly.
   - The REST API should follow best practices.
   - Proper HTTP status codes and error handling should be implemented.
   - The application should handle errors gracefully.

3. **Docker Containerization:**
   - The Docker container should be successfully built.
   - The container should be able to run the application without issues.

6. **Code Quality:**
   - Code should be well-organized and follow best practices.
   - Use meaningful variable and method names.
   - Include comments where necessary.

**Additional Notes:**

- Feel free to use any additional libraries or tools that you think would be beneficial.
- If you encounter any challenges or limitations during the process, document them in the README.md file.
- Make sure to respect best practices for secure coding and containerization.

Good luck! If you have any questions or need clarification on the requirements, feel free to reach out.
