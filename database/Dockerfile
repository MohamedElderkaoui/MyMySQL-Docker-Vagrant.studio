# Use an official MySQL image as a base image
FROM mysql:latest

# Set environment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=root_password
ENV MYSQL_DATABASE=mydb
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=user_password

# Copy the SQL script to initialize the database
COPY ./init.sql /docker-entrypoint-initdb.d/
