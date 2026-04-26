# Pull the official MySQL image from the Docker Hub
FROM mysql:8.0

# Set environment variables for MySQL
ENV MY_SQL_ROOT_PASSWORD = demopassword
ENV MY_SQL_DATABASE = demodb

# Copy the initialization script to the Docker image
COPY init.sql /docker-entrypoint-initdb.d/

# Expose the default MySQL port
Expose 3307