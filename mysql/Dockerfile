# Derived from official mysql image (our base image)
FROM mysql

# Add a database
ENV MYSQL_DATABASE company

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/




