Postgres DB Restore
++++++++++++++++++++

pg_restore -i -h localhost -p 5432 -U db_user -d db_name -v "file.backup"
