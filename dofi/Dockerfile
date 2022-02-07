FROM mariadb

COPY database/*.sql /tmp/

ENV MARIADB_USER miusuario0

ENV MARIADB_PASSWORD mipassword0

ENV MARIADB_ROOT_PASSWORD mipassword0

COPY database/nation.sql /docker-entrypoint-initdb.d/
