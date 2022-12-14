FROM mysql:5.7

ENV MYSQL_DATABASE meubanco

ENV MYSQL_ROOT_PASSWORD Senha123

COPY banco.sql /docker-entrypoint-initdb.d/

EXPOSE 3306