FROM mysql:8.0.11

# Copy the database initialize script:
# Contents of /docker-entrypoint-initdb.d are run on mysqld startup
ADD my.cnf /etc/mysql/my.cnf
#ADD Dump/ /docker-entrypoint-initdb.d/


# Default values for passwords and database name. Can be overridden on docker run
ENV MYSQL_ROOT_PASSWORD=root
# ENV MYSQL_DATABASE=bins
#ENV MYSQL_USER=root
#ENV MYSQL_PASSWORD=root
#ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes