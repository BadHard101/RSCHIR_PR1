FROM mysql

# Пояснение. В этой папке лежит скрипт, который запускает *.sql
COPY init.sql /docker-entrypoint-initdb.d

EXPOSE 3306
