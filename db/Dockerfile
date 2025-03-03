# filepath: /c:/Masha/via/devops/db/Dockerfile
FROM postgres:13

# Set environment variables for PostgreSQL
ENV POSTGRES_DB=viatabloid
ENV POSTGRES_USER=viatabloiduser
ENV POSTGRES_PASSWORD=viatabloidpassword

# Copy the schema.sql file to the Docker container
COPY schema.sql /docker-entrypoint-initdb.d/