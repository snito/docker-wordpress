FROM mysql:5.5

RUN mkdir /usr/src/app
WORKDIR /usr/src/app

COPY conf /etc/mysql/conf.d/my.cnf
COPY init.sql .
COPY init.sh .