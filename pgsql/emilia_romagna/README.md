```
DROP TABLE "emilia_romagna";
\i ./pgsql/emilia_romagna/emilia_romagna.pgschema.sql
\copy "emilia_romagna" FROM './csv/emilia_romagna.csv' CSV DELIMITER ',' HEADER NULL 'NULL';
```
