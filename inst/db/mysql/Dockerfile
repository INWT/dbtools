FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD root
ENV MYSQL_DATABASE test

ADD inst/db/*.sql /docker-entrypoint-initdb.d/
# ADD ./*.cnf /etc/mysql/conf.d/

EXPOSE 3306
