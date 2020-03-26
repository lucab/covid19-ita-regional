```
DROP TABLE "liguria";
\i ./pgsql/liguria/liguria.pgschema.sql
\copy "liguria" FROM './csv/liguria.csv' CSV DELIMITER ',' HEADER NULL 'NULL';
```
