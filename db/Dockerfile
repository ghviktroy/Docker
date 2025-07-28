FROM mysql:8.0

ENV MYSQL_ROOT_PASSWORD=rootpass
ENV MYSQL_DATABASE=webdb
ENV MYSQL_USER=webuser
ENV MYSQL_PASSWORD=webpass

COPY init.sql /docker-entrypoint-initdb.d/
