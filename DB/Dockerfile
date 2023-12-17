# Use an official MariaDB as a parent image
FROM mariadb:10

# Set environment variables for MariaDB
ENV MYSQL_DATABASE=mydb
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=mypassword
ENV MYSQL_ROOT_PASSWORD=myrootpassword

# Copy a custom my.cnf file (if needed)
# COPY ./my.cnf /etc/mysql/my.cnf

# Expose the MariaDB port
EXPOSE 3306

# Run any initialization scripts (if needed)
# COPY ./init.sql /docker-entrypoint-initdb.d/
