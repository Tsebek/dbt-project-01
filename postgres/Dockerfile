# Use an official PostgreSQL image
FROM postgres:13.13-bullseye

# Set environment variables
ENV POSTGRES_USER postgres
ENV POSTGRES_PASSWORD postgres

# Copy SQL scripts to initialize the database and schema
COPY ./sql-scripts /docker-entrypoint-initdb.d
