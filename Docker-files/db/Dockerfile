FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="KurosuSama"

ENV MYSQL_ROOT_PASSWORD="vpro123"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docekr-entrypoint-initdb.d/db_backup.sql