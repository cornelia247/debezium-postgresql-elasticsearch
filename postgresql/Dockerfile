FROM debezium/postgres:15-alpine

COPY ./setup.sql /home/setup.sql
COPY ./seed.sql /home/seed.sql
COPY ./initdb.sh /docker-entrypoint-initdb.d/init-db.sh