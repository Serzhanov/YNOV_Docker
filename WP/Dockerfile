# Use an official WordPress image as a parent image
FROM wordpress:latest

# Set environment variables for WordPress database connection
ENV WORDPRESS_DB_HOST=mariadb
ENV WORDPRESS_DB_NAME=mydb
ENV WORDPRESS_DB_USER=myuser
ENV WORDPRESS_DB_PASSWORD=mypassword

# Expose the WordPress port
EXPOSE 80

# Add any additional configurations or plugins (if needed)
# COPY ./my-config-file.php /var/www/html/wp-content/my-config-file.php
# COPY ./my-plugin.zip /var/www/html/wp-content/plugins/my-plugin.zip
