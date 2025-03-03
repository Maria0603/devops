# DevOps Project

This project is a DevOps setup for automating the build and deployment process.

## Build and Run with Docker

Follow these steps to build and run the Spring Boot application in a Docker container:

1. **Navigate to project directory:**

   Example:

   ```sh
   cd /c:/Masha/via/devops/
   ```

3. **Start the Docker containers:**

   ```sh
   docker-compose up --build
   ```

   Go to localhost to see the frontend
    ```sh
   localhost:3000
   ```

5. **Stop the Docker containers:**

   ```sh
   docker-compose stop
   ```
    **Stop and remove the Docker containers:**

   ```sh
   docker-compose down
   ```
