FROM mysql:8.0

COPY database.sql /docker-entrypoint-initdb.d

# docker run -p 3306:3306 -e MYSQL_ROOT_PASSWORD=*** rubru/jellytoring-db