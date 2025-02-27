# DevOps Project

This project is a DevOps setup for automating the build and deployment process.

## Build and Run with Docker

Follow these steps to build and run the Spring Boot application in a Docker container:

1. **Build the Docker image:**

   ```sh
   docker build -t spring-boot-backend .
   ```

2. **Run the Docker container:**

   ```sh
   docker run -p 8080:8080 spring-boot-backend
   ```
