FROM mysql:8.0

ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=mydb
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=userpassword

COPY custom.cnf /etc/mysql/conf.d/

EXPOSE 3306

CMD ["mysqld"]