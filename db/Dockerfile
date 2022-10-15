FROM mysql:5.7.25

LABEL "project"="database"

LABEL "Author"="Arbaj"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"

ENV MYSQL_DATABASE="accounts"

COPY db.sql docker-entrypoint-initdb.d/db_backup.sql



